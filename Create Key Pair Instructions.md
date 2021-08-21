You can create a new key pair from here: https://console.aws.amazon.com/iamv2/home?#/users


### 1. Click on Create User.
![Create User](https://user-images.githubusercontent.com/929833/130280884-76106fc6-badc-4472-8fc5-ac2b040a5343.png)

### 2. Give it a name and select Programmatic Access
![Name User and Programmatic Access](https://user-images.githubusercontent.com/929833/130280972-0ae5ed7f-f65b-4958-a78b-2d61e6bb44c3.png)

### 3. You can attach existing policies to your user.
![Attach Existing Policies Directly](https://user-images.githubusercontent.com/929833/130281115-04480eba-3c33-4e43-b863-852f338a3058.png)


### 4. Search for the following policies and select them.

* AWSPriceListServiceFullAccess (To query pricing details of instance types)
* AmazonEC2FullAccess(To query instance details, stop, start, terminate etc)
* AmazonS3FullAccess(To query bucket information)

You can also attach readonly policies for EC2 and S3, but you wouldn't be able to stop, start, instances or drag drop files into your S3 buckets and etc.

![Selecting a Policy](https://user-images.githubusercontent.com/929833/130281534-edb893e1-0f2f-4844-9f80-ee5bca209148.png)

### 5. Tag your user
![Tags](https://user-images.githubusercontent.com/929833/130281584-eb21315e-903c-411d-a2d8-c4a6effd7575.png)

### 6. Final review and make sure you have the proper policies attached and create the user.
![Final Review](https://user-images.githubusercontent.com/929833/130281793-5a851efd-8f84-4d88-bb20-90ae1af6dec2.png)

### 7. Copy the access key and secret key of the new user and paste them in the Compute Manager app in Settings -> Keys or simply press `Cmd + ,`
![keys](https://user-images.githubusercontent.com/929833/130281860-637e3422-5297-4ab6-b6a9-21840e47f48d.png)

### 8. You can see your new user in IAM Console.
![Created User](https://user-images.githubusercontent.com/929833/130281941-19cc0b45-4eac-4d1d-94db-8f3d13150ab9.png)

### 9. You can also update and change policies attached to an existing user.
![Manage your user update policies and etc](https://user-images.githubusercontent.com/929833/130282023-bf28c8fe-a5d0-4919-b026-9a1fd12dc700.png)

### 10. In the security credentials tab you can create a new key pair or make an existing key pair inactive or delete it altogether.
![Security Credentials create a new key pair and etc](https://user-images.githubusercontent.com/929833/130282088-8fddbad4-36d8-45a1-a280-94796f7962f8.png)
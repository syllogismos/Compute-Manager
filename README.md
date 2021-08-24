## Compute Manager

### [How to set up Keys](https://github.com/syllogismos/Compute-Manager/blob/main/Create%20Key%20Pair%20Instructions.md)

The user you create needs the following policies attached. 
* `AWSPriceListServiceFullAccess`
* `AmazonEC2FullAccess`
* `AmazonS3FullAccess`

You can instead use readonly policies for EC2 and S3, but you will limit the apps functionality. This app does not track any of your information and the only queries you will be doing are to the aws api, using your keys.

![EC2](https://user-images.githubusercontent.com/929833/130689598-c5b66345-1181-49f2-a648-5dfabcc283d9.png)
![S3](https://user-images.githubusercontent.com/929833/130689612-026ac06c-5066-4dd3-b91c-8030c874f7d9.png)
![Instance Types](https://user-images.githubusercontent.com/929833/130689623-58d6fd3e-7ea0-4ce9-92a0-506b03bffc80.png)
![Keys](https://user-images.githubusercontent.com/929833/130689628-6f93b831-78b7-4ade-8251-60c2e0332223.png)









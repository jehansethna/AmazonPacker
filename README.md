Packer Project to create custom AMIs in Amazon.
This project create a RedisImage in Amazon.

In order to launch the AMI creation process, follow the steps given below - 

1. CLone this repository using either SSH or HTTPS.
2. `cd AmazonPacker`
3. `packer validate RedisImage.json` to validate whether th .json file follows the required format.
4. `packer build -var 'aws_access_key=YOUR ACCESS KEY' -var 'aws_secret_key=YOUR SECRET KEY' RedisImage.json' 
5. Login to your Amazon AWS account to check whether the Image was created successfully.

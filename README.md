Step 0: enable cloudtrail and create an s3 bucket for its output
Step 1: Create a VPC; Public CIDR 10.0.0.0/31; one ip address availible for our small bookstore server.
Step 2: Create free tier ec2 instance with a public ip address; Enable SSH; use Amazon Linux 2; AWS Cloudwatch very important for monitoring cloud; Use aws cloudwatch to prevent someone ddossing us and causing big AWS bills; launch with args from file Amazon Linux 2 launch parameters(will auto load project code from github)
Step 3: Create a database

step x: create ec2 for following sections of the program as it is the most scalable / cost effective / secure way to build an application: seperate password server. probably dont need a scalable staff end server. scalable customer basket server for all the physical and online orders. account server
step x1: create the databased and authentication using aws services. api gateway to do http, lambda to do the backend functions,

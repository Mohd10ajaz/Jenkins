This template will install Git, Jenkins server, jenkins plugins, nginx. 
Nginx will route traffic from default jenkins port 8080 to port 80.
Make sure to change VPC ID, SUbnet ID, KeyName, default IP range to 0.0.0.0/0 in the template
Go with the below AWS command
# aws cloudformation create-stack --stack-name <nameofyourstack> --capabilities CAPABILITY_IAM --template-body file://<yourfilename.json>

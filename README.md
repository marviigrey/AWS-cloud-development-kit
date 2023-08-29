In this project we will be creating a cloud development kit using AWS and golang, before we start we will need a couple of things to handle this project. Here are the project pre-requisite:

1. AWS account and IAM user
2. AWS CLI
3. IDE with golang extensions installed.
4. Node.js- The aws CDK makes use of node js
5. AWS-CDK tool kit.
6. Golang.

Firstly:
1. Log in to your console and create an IAM user with the name "AWS-CDK"
2. Create an access key for your AWS-CDK user.
3. The next step is to choose our terminal and workspace. For this project  i will be using the AWS cloud9 because it has the aws-cli, go, aws-cdk and node installed on it already. Definitely the best choice
   for this project.

In this project we also learn how to use the CDK tool kit to synthesize an AWS Cloud-
Formation template for a starter app and how to deploy the application into our account.
----------------------------------------------------------------------
Steps: 
1. we create a directory called "cdk-workshop", this will be our workspace this project .

2. we initialize our workspace and create a new CDK go project by running:

    cdk init sample-app --language go

 After running the above command al list of files will be created:
    - cdk-workshop.go: which is where our application main stack is defined, it includes the
      entrpoint of our cdk-application.
      
    - cdk-workshop_test.go: thiis file contains a sample test of the custom cdk stack created 
      in the cdk-workshop package.
     
    - cdk.json: serves as a configuration file for your CDK application. It is used to
      provide configuration settings and options to the CDK CLI (Command Line Interface) 
      when you deploy your CDK app.
    
    - go.mod: is used to manage the project's dependencies. It's a central part of Go's module 
       system, introduced to help manage and version dependencies more effectively.
       
    - .gitignore: file specifies which files and directories should be ignored by git.   
   
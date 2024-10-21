# ci_cd__architect_using_aws_services
this project provides knowledge related to how ci-cd works in aws using aws services like codecommit, codebuild , codedeploy  and codepipeline

## Aim : To set a test-environment to check our index.html file

### Steps
#### Step-1.
Upload code to codecommit repository
#### Step-2.
Create a codebuild operation by adding buildspec.yml file
#### Step-3.
Use codedeploy to deploy ur code to ec2 instance 
#### Step-4.
This whole process can be automated using the codepipeline
#### Conclusion
This codepipline will check for updates in codecommit and automatically start the integration and deployment of the code

# Note-
codedeploy agent should is installed manually on ec2 entance to sure that there is no problem related to the version compatibilty issue (file used agent.txt)




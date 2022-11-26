[PipeLine Process](./Documentation/Pipeline.md)

![ARC](./Documentation/pipeline%20Diagram.png)

Continuous Integration
1- The developer commit and push his code to the GitHub repository
2- Then circleci paltform is triggered 
Inside CircleCi 
1- Install Node.js & Install Aws CLI / EB
2- Setting the environment Variables and start the pipeline.
3- Read the config.yml file Which is consist of 2 jobs
4- Configure Aws and start the 2 jobs which are build job and deploy job 

for the udagram/Backend: after installing package and build script and getting the environment variables from circle ci 
and archiving the zip file then it deploy by uploading the archive file to s3 using AWS CLI and elastic beanstalk.

for the udagram/Frontend: after installing package and build script then it deploy by uploading the files to s3 using AWS CLI.

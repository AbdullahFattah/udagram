# Dependencies used
## AWS
### S3
### ElasticBeanstalk
### Amazon RDS
### Node
### NPM


# Pipeline process

#### CircleCi is connected to the GitHub repo of the project, as soon as a change is made to the repo files, CircleCi detects it as starts the workflow process which goes as follows;
#### CircleCi starts with installing the project dependencies and builds the project's frontend and api, after that part is done, a manual approval is required by the user in order to carry on with the process, when the user approves, the deployment starts, in which the frontend files are deployed to the S3 bucket, and the API is deployed to ElasticBeanstalk.
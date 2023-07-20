# hello-node

## Assignment:

Create a new repository
1. Add sample code to your repository including the dockerfile on it
2. Update your repository Readme.md file to have step-by-step how to create an image until it will be deployed to AWS ECR


# Answer:
## Steps to building and pushing Image to Private ECR

Command to build an image
> $docker image build -t <IMAGE_NAME>:<IMAGE_TAG> .
> $docker image build -t <IMAGE_NAME>:<IMAGE_TAG> .

Command example with my image
> $docker image build -t simple-app-image .

Command to tag an image
> $docker image tag <IMAGE_NAME>:<IMAGE_TAG>  <REPOSITORY_URI>:<IMAGE_TAG>

Command example with our image and repository
> $docker image tag simple-app-image:latest  xxxxxxxxxxxx.dkr.ecr.us-east-2.amazonaws.com/ecr-tutorial-image:latest




[![CircleCI](https://circleci.com/gh/JeamBeamCim/capstone-project.svg?style=svg)](https://circleci.com/gh/JeamBeamCim/capstone-project)
## Cloud DevOps Engineer Capstone Project

[Github Repo](https://github.com/JeamBeamCim/capstone-project)

### Configure environment variables on CircleCI

Environment variables for CircleCI deployment

| Variable                  | Description                                     |
|---------------------------|-------------------------------------------------|
| `AWS_ACCESS_KEY_ID`       | Used by the AWS CLI                             |
| `AWS_SECRET_ACCESS_KEY`   | Used by the AWS CLI                             |
| `AWS_DEFAULT_REGION`      | Used by the AWS CLI. Project value: "us-east-1" |
| `ENVIRONMENT_NAME`        | capstone-project                                |
| `DOCKER_USERNAME`         | Dockerhub username                              |
| `DOCKER_PASSWORD`         | Dockerhub password                              |
| `IMAGE_NAME`              | Docker image name (capstone-project)            |

Manually upload local created docker image via `upload_docker.sh`
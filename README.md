# Gitlab Runner Auto Register

Gitlab Runner that auto registers based on environment.

Heavily based on: https://github.com/ayufan/gitlab-ci-multi-runner/tree/master/dockerfiles/ubuntu

## Build

    docker build -t gitlab-runner-auto-register .

## Run

    docker run -e "CI_SERVER_URL=https://gitlab.example.com/" -e "REGISTRATION_TOKEN=XXXXXXXXXXXXXX" -e PRIVILIGED_MODE={true|false} gitlab-runner-auto-register 

## Environment Variables

For more information about the the environment variables:

https://github.com/ayufan/gitlab-ci-multi-runner/blob/master/docs/commands/README.md#gitlab-runner-register


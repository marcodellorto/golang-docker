# https://hub.docker.com/r/marcodellorto/golang

[![Github Actions CI](https://github.com/marcodellorto/golang-docker/actions/workflows/ci.yaml/badge.svg)](https://github.com/marcodellorto/golang-docker/actions/workflows/ci.yaml)
[![Docker Pulls](https://badgen.net/docker/pulls/marcodellorto/golang?icon=docker&label=Pulls)](https://hub.docker.com/r/marcodellorto/golang)

## Description
The `marcodellorto/golang` repository hosts Docker images tailored for seamless local development environments using VSCode's devcontainer feature. Each image is preconfigured with the essential components required for Go programming, ensuring a hassle-free setup process for developers. These images are also suitable for integration into CI/CD pipelines.

## Supported Go Versions

Images are built for the latest three supported Go versions:

- Go 1.26
- Go 1.25
- Go 1.24

Go 1.23 and earlier are no longer built or maintained by this repository.

## Contents
Contained within this repository are Docker images equipped with:
- **Go Programming Environment:** Pre-installed Go language tools and dependencies for efficient development.
- **VSCode Devcontainer Setup:** Configured settings and dependencies to facilitate integration with Visual Studio Code's devcontainer feature.
- **Additional Utilities:** Optional add-ons or tools that enhance the development workflow for Go projects.
- **AI Coding Assistants:** Dedicated `claude` and `codex` image targets with the corresponding command-line tools pre-installed.

## Usage Instructions

You can utilize these Docker images for your VSCode devcontainer setup, [here](https://github.com/marcodellorto/golang-devcontainer) you can find a skeleton of an already configured project that uses these images.

Assistant-specific images follow these tag patterns:

- `marcodellorto/golang:<go-version>-bookworm-claude`
- `marcodellorto/golang:<go-version>-bookworm-codex`

## Additional Information

Maintainer: [Marco Dell'Orto](https://github.com/marcodellorto/golang-docker)

Support/Issues: Report issues or seek support on the repository's [issue tracker](https://github.com/marcodellorto/golang-docker/issues).

## Disclaimer
These images are provided as-is, and users are encouraged to review the configurations and adjust them according to their specific requirements and security considerations.

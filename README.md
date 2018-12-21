### `Purpose`

Practice with production grade workflow with continuous integration and deployment with AWS<br>
Tools used include Docker, Travis CI, AWS Elastic Beanstalk

### `Dockerfile`

Used to create a container for production running on a server ready for users to come visit. Uses the node:alpine base image, copies package.json, and installs dependencies and then builds with a separate nginx image as well.

Contains no dependencies or test suites.

### `Travis integration`

Include .travis.yml file. Tell Travis to run docker, build image via Dockerfile.dev, how to run test suites, and then deploy code to AWS

### `Docker-Compose`

Set up networking infrastructure between multiple containers and making running containers easier

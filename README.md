# React App With Docker

[![Build Status](https://travis-ci.com/nomanaadma/docker-react.svg?branch=master)](https://travis-ci.com/nomanaadma/docker-react)

> React App Setup with docker using travis CI/CD pipeline to deploy in AWS Elasticbeanstalk

## Prerequisites

```
1.Make sure you have docker and docker compose installed in system
```

## Tech Stacks
* [Docker](https://www.docker.com) - Containerize app
* [Docker-Compose](https://docs.docker.com/compose) - Local development environment to run tests and builds by using volumes and networks
* [NGINX](https://www.nginx.com/) - Web Server
* [Create React App](https://github.com/facebook/create-react-app) - Bootstrapping
* [Node](https://hub.docker.com/_/node) - Backend
* [Travis-ci](https://travis-ci.com/) - CI/CD Pipelines
* [AWS Elastic Beanstalk](https://aws.amazon.com/elasticbeanstalk/) - Build, Deploy, And Manage App

## Development
Run following command in your terminal 

```bash
docker compose up --build
```

remove --build argument if you are rerunning the app witout making any change in dockerfile and docker-compose.yml file

and you are good to go visit http://localhost:3000

## Screenshots
See the screenshots folder for detailed instructions.

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the GNU General Public License - see the [LICENSE](LICENSE) file for details
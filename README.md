# Pre-requisitos

Para correr este proyecto de manera exitosa se deben instalar las siguientes herramientas.

* .net core 3.1 https://dotnet.microsoft.com/download
* python 3.8 https://www.python.org/downloads/
* AWS CLI https://docs.aws.amazon.com/cli/latest/userguide/install-cliv2.html
* AWS SAM https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install.html
* Docker https://docs.docker.com/engine/install/


# Correr el proyecto localmente

## compilar
sam build --use-container

## invocar lambda local
sam local invoke --config-env {env}

## Iniciar un server en localhost para correr la API
sam local start-api --config-env --port 5000

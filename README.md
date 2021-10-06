# Software a instalar:

- [DBeaver](#dbeaver)
- [IBM Cli](#ibm-cli)
- [AWS Cli](#aws-cli)
- [PGAdmin](#pgadmin)
- [Robo 3T](#robo-3t-recomendable) (y/o [Mongo Compass](#mongo-compass)]
- [Postman](#postman)
- [VSCode](#vscode)
- [Docker Desktop](#docker)
- [Node JS - nvm](#node-js)
- [Python 3](#python-3)

## Detalle

- ### IBM Cli

  (https://cloud.ibm.com/docs/cli?topic=cli-install-ibmcloud-cli&locale=es)
  
- ### AWS Cli

  (https://docs.aws.amazon.com/es_es/cli/latest/userguide/install-cliv2-windows.html)

- ### DBeaver

  (https://dbeaver.io/)

- ### PgAdmin

  (https://www.pgadmin.org/)
  
- ### Cliente para Mongo

  Cualquiera de los siguientes:

  - #### Robo 3T (Recomendable)
    (https://robomongo.org/download)
  - #### Mongo Compass
    (https://www.mongodb.com/try/download/community)

- ### Postman

  (https://www.postman.com/downloads/)

- ### VSCode

  (https://code.visualstudio.com/)

- ### Docker

  (https://www.docker.com/products/docker-desktop)

  (añadir usuario al grupo "docker-users")

  - Consideraciones

    - Será necesario reiniciar para finalizar la instación.

    - Debe ejecutarse al iniciar el sistema.

- Docker Compose (incluído en Docker Desktop para Windows)

  - Mismas consideraciones que con Docker. Si se ejecuta en Windows no es necesario.

- ### Python 3

  (https://www.python.org/downloads/)

- ### Node JS (NVM)

  - Usando NVM
    (En linux: https://github.com/nvm-sh/nvm)
    (En windows: https://github.com/coreybutler/nvm-windows -> https://github.com/coreybutler/nvm-windows/releases [1.1.8 / nvm-setup.zip])

    NVM instala fácilmente versiones de node js y npm, permitiendo cambiar entre versiones sin problema.

    Para instalar una versión específica:
    `nvm install v14.17.3`

    Para configurarla la versión a usar en el directorio actual:
    `nvm use v14.17.3`

    Para configurarla la versión por defecto en todo el sistema:
    `nvm alias default v14.17.3`

    La cuestión es que nvm añade la versión de node js configurada a la variable de entorno PATH. En este caso se necesitará permiso de admistrador: indispensable su consideración si el cambio es frecuente.
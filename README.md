# nuxt-oracle

> Nuxt.js project

## Build Setup

``` bash
# install dependencies
$ npm install # Or yarn install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, checkout the [Nuxt.js docs](https://github.com/nuxt/nuxt.js).

## Instalar Instantclient

Descargar instantclient de la página de oracle y agregar las siguientes variables:
Agregar al path

```
$ set OCI_LIB_DIR=C:\oracle\product\12.1.0\dbhome_1\oci\lib\msvc
$ set OCI_INC_DIR=C:\oracle\product\12.1.0\dbhome_1\oci\include

$ set OCI_INC_DIR=C:\oracle\instantclient_12_2
$ set OCI_LIB_DIR=C:\oracle\instantclient_12_2

$ set OCI_INCLUDE_DIR=C:\oracle\instantclient_12_2/sdk/include
$ set OCI_VERSION=12
$ set NLS_LANG=AMERICAN_AMERICA.UTF8

$ agregar al path el instant client
```

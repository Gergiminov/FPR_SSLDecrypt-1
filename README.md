# FPR_SSLDecrypt

> FPR_SSLDecrypt CiscoFirePowerDemo

## Build Setup

``` bash

# install dependencies
$ npm run install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```



# generate ssl keys
$ openssl req -new -newkey rsa:4096 -x509 -sha256 -days 365 -nodes -out server.crt -keyout server.key
```

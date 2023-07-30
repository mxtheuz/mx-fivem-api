# API that Admin Tools uses...

API that the Admin Tools site (posted here on github under the name 'mx-fivem-api-site') uses to collect and update data.
Note that it does not have package.json, it will be necessary to install the libraries manually: @vrpjs/server, imgbb-uploader, mysql, axios, express, cors, body-parser.

# How to install

## First | Creating package.json

```
npm init -y
```

## Secondg | Installing all dependencies

```
npm install @vrpjs/server imgbb-uploader mysql axios express cors body-parser
```

## Third | Put the project at FiveM server

Second, you need to install the script and put at "resources" in your FiveM Server's base path.

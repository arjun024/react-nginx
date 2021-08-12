# React + Nginx using Paketo

## Building

`pack build reactimg -b gcr.io/paketo-buildpacks/nodejs -b gcr.io/paketo-buildpacks/nginx -e "BP_NODE_RUN_SCRIPTS=build"`

## Running

`docker run --init -it -p 8080:8080 reactimg`

## Viewing

`curl http://localhost:8080`

# Sitecore Reforge Black Box CM example

For more details, see the main repository [Sitecore Reforge](https://github.com/sitecoreops/sitecore-reforge).

## Features

- Minimal compose setup for running a Sitecore Reforge Black Box CM

## Run

1. `$env:REGISTRY="<REGISTRY>/"` to set your source registry if images are not present locally.
1. `docker login` or whatever is needed to authenticate to your source registry.
1. `docker-compose up -d`

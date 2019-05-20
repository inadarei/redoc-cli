# redoc-cli
Docker Image for Redoc CLI

## Usage:

### Building an HTML:

```
docker run -v ${PWD}:/apidocs inadarei/redoc-cli 
```

### Starting an API server

```
docker run -d -p 3939:8000 --rm --name redoc-api-docs inadarei/redoc-cli redoc-cli serve -w -ssr -p 8000 api.yaml
```

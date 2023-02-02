# CONTRIBUTING

## HOW TO BUILD DOCKER
```
docker build -t IMAGE_NAME .
```

## HOW TO RUN DOCKER LOCALLY

```
docker run -dp 5000:5000 -w /app -v "$(pwd):/app" IMAGE_NAME sh -c "flask run --host 0.0.0.0"
```


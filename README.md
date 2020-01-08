# Flask Docker Build Image 

This docker image runs with python flask and application is running on 5000 with localhost !

Build Docker image:
```
docker build -t sunlnx/flask-app:latest .
```

Run application:

```
docker run -d -p 5000:5000 sunlnx/flask-app:latest
```

This repo also containes *Jenkinsfile* where you can deploy your code using Jenkins pipeline and try to build your images

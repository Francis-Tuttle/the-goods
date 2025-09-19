1. Make your changes to the Dockerfile
2. Update the version numbers in the commands in this very README
3. Run the commands:

```
docker build -t us.gcr.io/francis-tuttle-prj/the-goods:1.3.0 --platform linux/amd64 .
docker push us.gcr.io/francis-tuttle-prj/the-goods:1.3.0
```

# Triggering the workflow

Run below to trigger the workflow
```
argo submit -n argo --watch pipeline/build-and-push.yaml --parameter-file params/emailservice.yaml
```
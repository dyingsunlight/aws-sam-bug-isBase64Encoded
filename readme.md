## Reproduce by command:
```
sam local start-api --template template.json --port 8090
```

After aws sam cli ready, visit `http://127.0.0.1:8090/hello-world` will see a broken image.

If deploy the code into aws cloud lambda, the code will work as expect to show a simply red background image.

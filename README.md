# Divio Demo App

This is a simple nginx server with an index.html saying hello and showing the number (and type) of services
currently attached.

## Run locally

To build and run locally:
```bash

docker build -t derlin/hello-silicon-chalet .
docker run -v 8080:80 derlin/hello-silicon-chalet
```

You can now access the app at http://localhost:8080

## Deploy on Divio

Deploy it on [divio](https://divio.com) easily:

0. Fork this repository
1. Create an account on [divio](https://control.divio.com)
2. Click "add application"
3. Select "I already have a repository"
4. Connect to Github and select your forked repository
5. Choose a plan and "Create application"

Now, you can just hit "Deploy" on the live environment. If you want to add a service, go to the
services tab.

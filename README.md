# distribution-system-demo
First Minimal Viable Product for demo purpose. This application is far from finished version. Most of feture is missing, like logout feature.

## Run
To run this project you need docker in your system.

### Run All Aplication with Docker Compose
```
$ docker compose up -d
```

Note: Sometimes you need to run engine manually after run docker compose up, because the engine run before postgres finish setup the database.

After all container up, you can access application from http://localhost:3000.
You can login to application with user **admin** and password **s3cr3t**. First time user login to application, user should change password to new password.
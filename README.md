# File server
File browser server running as a docker container exposed on port 8080. The image base is on apache httpd:2.4-alpine

# Building
```bash
echo FILE_DIR=./ > .env
docker-compose up -d
```

# Testing
Visit your browser at [http://localhost:8080/](http://localhost:8080/)

# Deploy
Reverse proxy from port 80 to http://localhost:8080/
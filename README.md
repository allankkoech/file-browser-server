# File server
File browser server running as a docker container exposed on port 8080. The image base is on apache httpd:2.4-alpine

# Building
```bash
echo FILE_DIR=./ > .env
```
docker-compose up -d

# Testing
http://localhost:8080/


```bash
docker build -t demo-java:1.0.0 .
docker run -d --name demo -p 8080:8080 --memory=512m demo-java:1.0.0
```

# Bookinfo Review Service

Review service has been developed on Java

# How to run with Docker

```bash
# Build Docker Image for reviews service
docker build -t reviews .

# Run reviews service on port 8082
docker run -d --name reviews -p 8082:8082 reviews
```
* Test with path /reviews/1 and /health

## Website

[Opsta (Thailand) Co., Ltd.](https://www.opsta.co.th)
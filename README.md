## sitkmutt-bookinfo-reviews

# How to run reviews service

# How to run with Docker

```bash
# Build Docker Image for reviews service
docker build -t reviews .

# Run details service on port 8081
docker run -d --name reviews -p 8082:8082 reviews
```
* Test with path /reviews/1 and /health

## Website

[Opsta (Thailand) Co., Ltd.](https://www.opsta.co.th)
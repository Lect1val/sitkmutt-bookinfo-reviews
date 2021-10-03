# Bookinfo Review Service

## How to run with Docker

```bash
# Build Docker Image for Detail service
docker build -t reviews .

# Run details service on port 8082
docker run -d --name reviews -p 8082:9080 reviews
```
* Test with path `/reviews/1` and `/health`
# Goroku

### 
```
cd helloworld
gcloud functions deploy go-http-function \
    --gen2 \
    --runtime=go121 \
    --region=asia-northeast1 \
    --source=. \
    --entry-point HelloHTTP \
    --trigger-http \
    --allow-unauthenticated
```
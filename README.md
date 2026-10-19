# containerization-docker

express + mongodb hello-world packaged with a dockerfile and docker compose.

## stack

express · mongoose · typescript · docker · docker compose

## run locally

```bash
docker compose up --build        # api on :3000, mongodb on :27017
npm install && npm run build     # without docker
```

## env

none. compose sets everything it needs.

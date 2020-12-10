# desafio-docker-go #Full Cycle Developer @CodeEducation

## Build
docker build --no-cache --pull --rm -f "dockerfile-go.docker" -t desafio-go:1.0.0 .
docker run desafio-go:1.0.0

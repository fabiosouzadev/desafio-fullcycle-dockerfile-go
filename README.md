<h1 align="center">
  <br>
  <img src="https://raw.githubusercontent.com/fabiosouzadev/desafio-fullcycle-dockerfile-go/main/docs/screen.png" alt="screen" width="200">
  <br>
  Desafio Dockerfile Golang
</h1>

## Desafio

- Criar uma imagem docker de um app em [golang](https://go.dev/) que imprime `Full Cycle Rocks!!`
- Imagem com menos de 2Mb

## 🚀 Buildando a imagem

```bash
# Clone this repository
$ git clone https://github.com/fabiosouzadev/desafio-fullcycle-dockerfile-go

# Go into the repository
$ cd desafio-fullcycle-dockerfile-go

# Build image
$ docker build <nome-da-imagem> .

# Run the app
$ docker run <nome-da-imagem>
```

## ☕ Usando a imagem do [Docker Hub](https://hub.docker.com/)

```bash
docker run fabiosouzadev/desafio-fullcycle-dockerfile-go
```

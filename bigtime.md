## build

```shell
$ ./build.sh
```

## run

```shell
$ source .env
$ docker-compose up
```

Open application in your browser with private IP !! (not localhost), ex.

```shell
$ open "http://$(ipconfig getifaddr en0):8888"
```

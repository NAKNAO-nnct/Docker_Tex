# Docker \* LaTex

Qitta  
https://qiita.com/nontan18/items/579daf033a4644f2285a

## How to install

```shell
$ docker build -t mylatexlive .
$ docker-compose up -d
$ docker exec -it texlive_texlive_1 sh
(docker)$ mktexlsr
(docker)$ browser-sync start --server --files "/root/work/\*" &
```

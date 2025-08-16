# login -> build -> push
## docker login  

```bash
export CR_PAT=xxxx
echo $CR_PAT | docker login ghcr.io -u USERNAME --password-stdin
```

## build

```bash
docker build -t ghcr.io/masahide/7dtd-server:v0.7.3 .
```

## push

```bash
docker push ghcr.io/masahide/7dtd-server:v0.7.3
```



# Docker example

1.build

```
docker image build -t example/echo:latest .
```

2.run

```
docker container run -t -p 9000:8080 example/echo:latest
```

3.stop

```
docker container stop $(docker container -ls -q)
```

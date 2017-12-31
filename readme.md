# JSHint Docker Image

```
docker pull nickromano/jshint-docker
docker run --rm --volume `pwd`:/code nickromano/jshint-docker
```

Pass command line options - http://jshint.com/docs/cli/
```
docker pull nickromano/jshint-docker
docker run --rm --volume `pwd`:/code nickromano/jshint-docker --config myconfig.json .
```

## build, push
```
$ ./gradlew build docker
$ docker push psjtest00/gs-spring-boot-docker
```

## 실행
```
$ docker pull psjtest00/gs-spring-boot-docker
$ docker run -p 8080:8080 -t psjtest00/gs-spring-boot-docker
```

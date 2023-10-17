

해당하는 이미지를 가지고 컨테이너 생성 후 실행

	-d : 컨테이너를 백그라운드에서 실행시 새로운 컨테이너과 
	-name : 컨테이너 실행 시 이름

```
docker run [OPTIONS] IMAGE [COMMAND] [ARG...]
```

이미지를 만들기

```
docker build
```


이미지 삭제

```
dcoker rmi [이미지 이름/id]
```

docker hub에 있는 이미지 불러오기

```
docker pull [이미지 이름]
```

docker hub에 이미지 업로드

```
docker push [이미지 이름]
```


1. **컨테이너 관리**
    - `docker ps`: 실행 중인 도커 컨테이너를 나열합니다.
    - `docker ps -a`: 모든 도커 컨테이너를 나열합니다 (실행 중인 것과 중지된 것 모두).
    - `docker run [옵션] [이미지 이름]`: 새로운 도커 컨테이너를 시작합니다.
    - `docker stop [컨테이너 이름/ID]`: 도커 컨테이너를 중지합니다.
    - `docker start [컨테이너 이름/ID]`: 중지된 도커 컨테이너를 시작합니다.
    - `docker rm [컨테이너 이름/ID]`: 도커 컨테이너를 삭제합니다.
2. **기타 유용한 명령어**
    - `docker exec -it [컨테이너 이름/ID] [명령]`: 실행 중인 컨테이너에서 명령어를 실행합니다.
    - `docker logs [컨테이너 이름/ID]`: 컨테이너의 로그를 확인합니다.
    - `docker network ls`: 도커 네트워크 목록을 나열합니다.
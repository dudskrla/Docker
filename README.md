# Docker

## 📂 2022-06-13
### docker network 생성 
```
docker network create --gateway 172.50.0.1 --subnet 172.50.0.0/16 post_ocr_parsing
```

### api_info.json 파일 추가 
```
# 2022-06-13\BE\app\api_info.json 경로에 파일 추가
```

### 프로그램 실행

2022-06-13 디렉토리에서   
```
docker-compose up --build
```

주소창에 `localhost:8501`를 입력하여 접속 

## 📂 2022-06-13-network-experiment
docker network를 따로 생성하는 명령어를 입력하지 않아도,
docker compose 과정에서 FE와 BE가 같은 네트워크에 포함되도록 변경

### api_info.json 파일 추가 
```
# 2022-06-13-network-experiment\BE\app\api_info.json 경로에 파일 추가
```

### 프로그램 실행

2022-06-13-network-experiment 디렉토리에서   
```
docker-compose up --build
```

주소창에 `localhost:8501`를 입력하여 접속 
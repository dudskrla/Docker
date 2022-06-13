# Docker

## docker network 생성 
```
docker network create --gateway 172.50.0.1 --subnet 172.50.0.0/16 post_ocr_parsing
```

## api_info.json 파일 추가 
```
# 2022-06-13\BE\app\api_info.json 경로에 파일 추가
```

## 프로그램 실행

2022-06-13 디렉토리에서   
```
docker-compose up --build
```

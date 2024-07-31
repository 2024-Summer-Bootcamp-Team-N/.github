# 📌 AI 공인중개사와 함께 집을 구해보는 서비스: HouseAdvisor

![메인페이지](https://github.com/user-attachments/assets/6152a9cb-8dbf-41db-afa0-bbc561dee7e7)

## Table of Contents
* [Medium](#-medium)
* [Demo Video](#-demo-video)
* [System Architechture](#-system-architechture)
* [Tech Stack](#-tech-stack)
* [ERD](#-erd)
* [API](#-api)
* [Monitoring](#-monitoring)
* [How to start](#-how-to-start)
* [Team Members](#-team-members)

## ✨ Medium
[[2024 Summer Silicon Valley BootCamp] HouseAdvisor](https://medium.com/@suhach0523/2024-summer-silicon-valley-bootcamp-houseadvisor-00f281c60bad)

## 📹 Demo
### 사용자가 원하는 매물 정보 입력
![필터링페이지](https://github.com/user-attachments/assets/728fe363-9412-47e9-8b01-1d6df5699604)
### 매물 정보 페이지
![매물 정보 페이지](https://github.com/user-attachments/assets/b9590338-e559-4ae6-a92b-c1a6907ab724)
### 상담페이지
![상담페이지](https://github.com/user-attachments/assets/2f088cd6-a7d3-4175-9d47-91fb72d4deef)
### 계약서페이지
![계약서페이지](https://github.com/user-attachments/assets/110ea3bf-a96d-4310-8c1e-892ea192c482)

## 🐋 System Architechture
![Team-N 시스템 아키텍처](https://github.com/user-attachments/assets/4951fa02-57f0-4200-b216-1e42ee3c2528)

## 💡 Tech Stack
|Area|Tech Stack|
|:---:|:---:|
|<b>Frontend</b>|<img src="https://img.shields.io/badge/react-61DAFB?style=for-the-badge&logo=react&logoColor=black"> <img src="https://img.shields.io/badge/typescript-%23007ACC.svg?style=for-the-badge&logo=typescript&logoColor=white"> <img src="https://img.shields.io/badge/vite-%23646CFF.svg?style=for-the-badge&logo=vite&logoColor=white"> <img src="https://img.shields.io/badge/Tailwind CSS-06B6D4?style=for-the-badge&logo=Tailwind CSS&logoColor=white"> <img src="https://img.shields.io/badge/ESLint-4B32C3?style=for-the-badge&logo=ESLint&logoColor=white"> <img src="https://img.shields.io/badge/Prettier-FFCC00?style=for-the-badge&logo=prettier&logoColor=white"> <img src="https://img.shields.io/badge/axios-5A29E4?style=for-the-badge&logo=axios&logoColor=white">|
|<b>Backend</b>|<img src="https://img.shields.io/badge/django-%23092E20.svg?style=for-the-badge&logo=django&logoColor=white"> <img src="https://img.shields.io/badge/DJANGO-REST-ff1709?style=for-the-badge&logo=django&logoColor=white&color=ff1709&labelColor=gray"> <img src="https://img.shields.io/badge/mysql-4479A1?style=for-the-badge&logo=mysql&logoColor=white"> <img src="https://img.shields.io/badge/Amazon%20S3-569A31?style=for-the-badge&logo=Amazon%20S3&logoColor=white"> <img src="https://img.shields.io/badge/amazon%20rds-527FFF?style=for-the-badge&logo=amazonrds&logoColor=white"> <img src="https://img.shields.io/badge/Rabbitmq-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white"> <img src="https://img.shields.io/badge/celery-%23a9cc54.svg?style=for-the-badge&logo=celery&logoColor=ddf4a4">|
|<b>AI</b>|<img src="https://img.shields.io/badge/openai-412991?style=for-the-badge&logo=openai&logoColor=white">|
|<b>DevOps</b>|<img src="https://img.shields.io/badge/docker-2496ED?style=for-the-badge&logo=docker&logoColor=white"> <img src="https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white"> <img src="https://img.shields.io/badge/amazon%20ec2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white"> <img src="https://img.shields.io/badge/jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white">|
|<b>Monitoring</b>|<img src="https://img.shields.io/badge/Prometheus-E6522C?style=for-the-badge&logo=Prometheus&logoColor=white"> <img src="https://img.shields.io/badge/grafana-%23F46800.svg?style=for-the-badge&logo=grafana&logoColor=white"> <img src="https://img.shields.io/badge/elastic stack-005571?style=for-the-badge&logo=elasticstack&logoColor=white">
|<b>etc</b>|<img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white"> <img src="https://img.shields.io/badge/Slack-4A154B?style=for-the-badge&logo=slack&logoColor=white"> <img src="https://img.shields.io/badge/Notion-000000?style=for-the-badge&logo=notion&logoColor=white"> <img src="https://img.shields.io/badge/-Swagger-%23Clojure?style=for-the-badge&logo=swagger&logoColor=white"> <img src="https://img.shields.io/badge/figma-%23F24E1E.svg?style=for-the-badge&logo=figma&logoColor=white">

## 💾 ERD
![Team-N ERD](https://github.com/user-attachments/assets/665c888c-9548-4f2d-ad32-149c5d7effa7)

## 🔑 API
![API 명세서](https://github.com/user-attachments/assets/02a94f7a-1b24-4160-8aa6-7d96c48bd20f)

## 💻 Monitoring

## 🚀 How to start
#### 준비물(비용이 발생할 수 있음)
* [Kakao API key 발급받기](https://developers.kakao.com/)
* [OpenAI API key 발급받기](https://platform.openai.com/)
* [AWS S3 Bucket 만들기](https://aws.amazon.com/ko/s3/getting-started/)
#### 1. Clone The Repository
```

```
#### 2. ENV Setting
* /.env (docker-compose.yml 파일과 같은 디렉토리에 생성)
```

```
#### 3. Run Docker
```
docker compose up --build
```

## 👥 Team Members
|Name|최수하|김민기|권혁진|김종완|김민균|문재준|송수민|
|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
|Profile|![최수하](https://github.com/suhach0523.png)|![김민기](https://github.com/kimm0302.png)|![권혁진](https://github.com/blueiz920.png)|![김종완](https://github.com/kimjwooo.png)|![김민균](https://github.com/dirak4545.png)|![문재준](https://github.com/jjjjjoon.png)|![송수민](https://github.com/LilyS222.png)|
|Role|Leader, Frontend|Backend, DevOps|Frontend|Frontend|Backend|Backend|Backend|
|GitHub|[@suhach0523](https://github.com/suhach0523)|[@kimm0302](https://github.com/kimm0302)|[@blueiz920](https://github.com/blueiz920)|[@kimjwooo](https://github.com/kimjwooo)|[@dirak4545](https://github.com/dirak4545)|[@jjjjjoon](https://github.com/jjjjjoon)|[@LilyS222](https://github.com/LilyS22)

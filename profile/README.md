# Pawong - 전국 유기동물을 특징으로 검색하세요!
[![포옹 ](https://img.shields.io/badge/www.pawong.co.kr-orange)](https://www.pawong.co.kr)  [![발표 자료](https://img.shields.io/badge/발표%20자료-blue)](https://drive.google.com/file/d/1UzJ34UyYbOXChAJ4u866ssVpilTE9n3w/view) 

---

Pawong(포옹)은 유기동물 입양 희망자를 위해 각 유기동물을 특징으로 검색할 수 있도록 제공하는 서비스입니다.
더불어 실종 동물이 보호소로 안치되기 전에 조기 발견되도록 실종 동물 공고를 등록할 수 있는 기능을 제공합니다.
포옹 서비스를 이용해 반려 동물을 사지 말고, 입양하는 문화를 만들어가요!

## 주요 기능
🔎 유기 동물 검색 기능
- 전국 유기동물 보호소에 등록된 데이터를 통합 및 주기적 업데이트
- AI 모델을 활용해 정제된 유기동물 데이터를 자연어로 검색

📝 실종 동물 공고 등록 및 채팅 기능
- 반려동물 주인이 동물을 잃어버린 경우 게시글 작성
- 실종된 동물로 추정되는 동물을 발견한 경우에도 게시글 작성
- 사용자간 채팅을 구현

💡 실시간 알림 기능
- 실종된 동물과 유사한 이미지와 특징을 갖는 유기동물 공고 및 실종동물 게시글이 올라오는 경우 사용자에게 실시간 알림 및 메일링 구현
- 새로운 채팅에 대한 실시간 알림 구현

---

## 구현된 페이지 화면
### 🐾 메인 페이지
![pawong-main-final](https://github.com/user-attachments/assets/a0c383f3-9caa-409d-8c54-8775833148ca)

### 🐾 유기동물 리스트 페이지
![pawong-search](https://github.com/user-attachments/assets/0af8e695-f7ef-4bdb-8254-0635314e0d07)

### 🐾 실종동물 공고 페이지
![boards](https://github.com/user-attachments/assets/298d32a4-1912-457d-b4f4-9791569c0118)

<img width="1122" alt="lostanimal_register_screenshot" src="https://github.com/user-attachments/assets/18c3e4c1-7fd8-48ad-ae41-012b2032de50" />

<img width="806" alt="Screenshot 2025-06-05 at 2 56 19 PM" src="https://github.com/user-attachments/assets/d5f28e9a-2675-4eab-8123-055a893097d8" />

<img width="805" alt="Screenshot 2025-06-05 at 2 56 27 PM" src="https://github.com/user-attachments/assets/d21cc83b-69c1-43eb-818f-4cc672805a7b" />

### 🐾 채팅 및 실시간 알림 기능
<img width="760" alt="chats_screenshot" src="https://github.com/user-attachments/assets/ea9e8c47-db28-4330-914c-20d239bac9bd" />

![all_alertss](https://github.com/user-attachments/assets/ed5b980a-8877-4da9-a762-316341837a23)

### 메일링 기능
![mailing](https://github.com/user-attachments/assets/1cf6ebd8-02e0-4122-8214-f230f51d9c4e)

---

## 🛠️ 활용한 기술 스택
+ Backend
  + Spring Boot
  + Spring Data JPA (ORM)
  + Spring Security + OAuth2 + JWT
  + Spring Batch
  + STOMP Websocket
  + Kafka (Message Broker)
+ Database
  + MySQL (RDB)
  + ElasticSearch (Search Engine)
  + Redis (Cache)
+ Frontend
  + React.js
  + Vite.js
+ Third-party services
  + ChatGPT (chat-completion, vector-embeddings, CLIP model)
  + HuggingFace (embedding)
  + Firebase Cloud Messaging
  + Kakao API (Map, OAuth Login)
  + wsrv (Image URL Proxy serving)
+ DevOps
  + Nginx 
  + Docker & Docker-compose
  + Github Actions (CI/CD)
  + NHN Cloud - compute instance (Deployment)
  + NHN Cloud - RDS (Database)
  + AWS Lambda (Image embedding trigger)
  + AWS S3 (Static image hosting)
  + Prometheus, Grafana, Node Exporter, Promtail (Monitoring)
+ Co-op
  + Notion
  + Jira
  + Github
  + Discord

## 시스템 아키텍처

![image](https://github.com/user-attachments/assets/0453c604-d393-46f6-9ffa-a6d2450734d8)


# 4온 약 어때?

# **💊 의약품 간편 검색 서비스, 4온 약 어때? 💊**

![Untitled](https://github.com/user-attachments/assets/8425163b-411e-4c1a-a712-90762eb3f31e)

의약품에 대한 신뢰성 있는 정보를 제공하는 서비스

사이트 도메인: [**https://4onmedicine.kro.kr**](https://4onmedicine.kro.kr/)

멋쟁이 사자처럼 12기 해커톤

## 🔎 Introduction(소개)

---

![Untitled 1](https://github.com/user-attachments/assets/9f17a9f3-47f9-4c97-9108-1476b9774f3b)

### 기획 배경

1) 일반인이 의약품에 대한 정보를 얻기 쉽지 않고 과정이 복잡합니다.

2) 처방전에 의약품에 대한 정보가 없거나, 있더라도 누락된 정보가 있을 수 있습니다.

3) 한번에 건강 정보를 획득할 수 있는 획득처가 없습니다.

### 서비스 특징

1) 일반인이 의약품 정보를 쉽게 검색, 접근할 수 있습니다.

2) 처방전을 업로드하면 이미지 분석을 통해 처방전에 있는 의약품 정보를 전달합니다.

3) gpt Api를 통해 전반적인 건강 관련 정보를 얻을 수 있습니다.

## 🖥️ 페이지(page)

---

### 1) 메인페이지(MainPage)

<img width="1450" alt="%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2024-08-06_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9 15 50" src="https://github.com/user-attachments/assets/f02ed492-87c2-4d5a-9150-c719b5e40a39">

웹사이트에 접속시 처음 보이는 페이지입니다. 본 페이지에서 의약품을 검색하거나, 처방전을 업로드하기 위한 페이지로 이동할 수 있습니다. 또한, 우측 하단 채팅 버튼을 입력하여 gpt와 대화하며, 건강에 대한 정보를 얻을 수도 있습니다.

### 2) 채팅페이지(ChattingPage)

<img width="853" alt="%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2024-08-06_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9 17 44" src="https://github.com/user-attachments/assets/136a42c6-424a-49ea-baee-80a0c2178e13">
<img width="800" alt="%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2024-08-06_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9 19 22" src="https://github.com/user-attachments/assets/3a8eb85d-b3a8-4130-b36e-e12fb0dfd2cc">

웹사이트 우측 하단 채팅 버튼을 누르면 보이는 페이지입니다. 본 페이지의 하단 인풋에 건강에 대한 질문을 입력하면 gpt가 질문에 대한 답변을 제공합니다.

### 3) 의약품 상세 페이지(MedicinePage)

<img width="956" alt="%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2024-08-06_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9 20 54" src="https://github.com/user-attachments/assets/46f59186-8a7c-4c6a-a227-27b225a3f6da">

메인페이지에서 의약품 정보를 검색해 클릭하면 보이는 페이지입니다. 검색한 의약품에 대한 이미지와 효능, 사용법, 주의사항, 상호작용에 대한 정보를 얻을 수 있습니다.

### 4) 처방전 업로드페이지(PrescriptionPage)

<img width="907" alt="%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2024-08-06_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9 22 32" src="https://github.com/user-attachments/assets/8ee79f4c-5a1d-421c-bbf8-089528f45f98">

사이트 상단 네비게이션바에서 처방전 검색을 클릭하면 보이는 페이지입니다. 처방전 이미지를 업로드하면 처방전에 작성된 의약품의 보험코드를 추출해여 의약품 상세페이지로 이동해 의약품에 대한 정보를 제공합니다.

## 데모(Demo)

### 1) 검색창을 통한 의약품 검색

<img width="858" alt="%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2024-08-06_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9 25 58" src="https://github.com/user-attachments/assets/17972e3f-d6d8-4bd1-baa3-bc2d37ef2c99">

카테고리에서 ‘약’을 선택하고 의약품을 클릭합니다.

<img width="926" alt="%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2024-08-06_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9 27 59" src="https://github.com/user-attachments/assets/b4334cb4-7550-4bdd-9059-d7396391031a">

검색한 의약품 페이지로 이동해 해당 의약품에 대한 정보를 얻을 수 있습니다.

### 2) 처방전을 통한 의약품 검색

<img width="530" alt="%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2024-08-06_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9 29 24" src="https://github.com/user-attachments/assets/e0b78c15-20f3-48a6-b824-4b377d292bec">

<img width="485" alt="%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2024-08-06_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9 32 57" src="https://github.com/user-attachments/assets/716a664e-79fa-4bed-8ea6-2777e9efaabd">


처방전 검색 페이지에서 우측 이미지와 같이 보험코드가 적힌 처방전을 촬영 후 업로드합니다. 본 데모에서는 ‘타세놀8시간이알서방정’과 ‘타이레놀8시간이알서방정’이 적힌 처방전을 업로드하였습니다.

<img width="1035" alt="%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2024-08-06_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9 34 18" src="https://github.com/user-attachments/assets/71d502a6-bee9-45d5-8591-a9d3876df2a9">


처방전에 나와있는 의약품인 ‘타세놀8시간이알서방정’과 ‘타이레놀8시간이알서방정’에 대한 정보를 얻을 수 있습니다. 처방전에 대한 의약품 상세 페이지는 슬라이드로 구현되어 슬라이드를 넘겨 처방전에 작성된 모든 의약품에 대한 정보를 얻을 수 있습니다.

### 3) 채팅

<img width="126" alt="%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2024-08-06_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9 37 53" src="https://github.com/user-attachments/assets/7aa02133-ea3b-445a-9891-c55f2b13d5db">
<img width="824" alt="%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2024-08-06_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9 38 20" src="https://github.com/user-attachments/assets/e635f17a-a380-422c-8a77-369dd509acfb">

모든 페이지의 우측 하단에 있는 채팅 버튼을 클릭하고, 다음 채팅 페이지로 이동합니다.

<img width="826" alt="%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2024-08-06_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9 38 55" src="https://github.com/user-attachments/assets/c9cd8722-b945-435f-aae5-68f38e1705fe">

채팅 페이지 하단 인풋에 건강과 관련된 질문을 작성하고 엔터키를 누릅니다. 본 데모에서 ‘목감기에 좋은 약을 추천해줘'라는 글을 작성합니다. 그 후 gpt가 질문에 대한 답변을 제공합니다.

## **📜 아키텍쳐(Architecture)**

![Untitled 2](https://github.com/user-attachments/assets/e824e28d-d6f1-4775-bd3c-e44ba82d1f9e)

## 💡 기술 스택(Tech Stack)

<img width="519" alt="%E1%84%89%E1%85%B3%E1%84%8F%E1%85%B3%E1%84%85%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A3%E1%86%BA_2024-08-06_%E1%84%8B%E1%85%A9%E1%84%92%E1%85%AE_9 42 57" src="https://github.com/user-attachments/assets/5c8cf86c-d6ff-4615-89bf-15bd3d9be83f">

- 프론트 파트(Front part): react
- 백엔드 파트(Backend part): Spring Boot, Flask
- 배포(Deployment): GoogleCloud, Amazon AWS, Docker, Nginx, Github Actions
- 이 외(Other): Swagger

## **📌** 깃허브 주소

- 프론트 레포지토리(Frontend Repository): [https://github.com/hollydrug/front](https://github.com/hollydrug/front)
- 백엔드(스프링) 레포지토리(Backend(Spring) Repository): [https://github.com/hollydrug/backend](https://github.com/hollydrug/backend)
- 백엔드(플라스크) 레포지토리(Backend(Flask) Repository): [https://github.com/hollydrug/backend2](https://github.com/hollydrug/backend2)

## **📂** 디렉토리 구조

---

### 1) 프론트 디렉토리(frontend directory)

```bash
front/
├── public/
│   ├── favicon.ico
│   ├── index.html
│   └── robots.txt
├── src/
│   ├── assets/
│   │   ├── logo.png
│   │   └── styles.css
│   ├── components/
│   │   ├── Header.tsx
│   │   ├── Footer.tsx
│   │   └── SearchBar.tsx
│   ├── pages/
│   │   ├── Home.tsx
│   │   ├── SearchResults.tsx
│   │   └── Prescription.tsx
│   ├── App.tsx
│   ├── index.tsx
│   └── routes.tsx
├── .env
├── .eslintrc.cjs
├── .gitignore
├── package-lock.json
├── package.json
├── README.md
└── vite.config.js
```

### 2) 백엔드 디렉토리(backend directory)

```bash
.
├── Dockerfile
├── Dockerfile-nginx
├── build
├── build.gradle
├── gradle
├── gradlew
├── gradlew.bat
├── nginx
│   └── conf.d
│       └── nginx.conf
├── settings.gradle
└── src
    ├── main
    │   ├── java
    │   │   └── com
    │   │       └── medicine
    │   │           └── backend
    │   │               ├── BackendApplication.java
    │   │               └── medicine
    │   │                   ├── config
    │   │                   │   ├── CorsMvcConfig.java
    │   │                   │   └── SwaggerConfig.java
    │   │                   ├── controller
    │   │                   │   ├── FlaskController.java
    │   │                   │   └── MedicineController.java
    │   │                   └── dto
    │   │                       ├── ChatRequest.java
    │   │                       ├── ImgMedicineDetail.java
    │   │                       ├── ImgPayload.java
    │   │                       ├── MedicineDetail.java
    │   │                       └── MedicineInfo.java
    │   └── resources
    │       └── application.properties
    └── test
        └── java
            └── com
                └── medicine
                    └── backend
                        └── BackendApplicationTests.java
```

## 🧑🏻‍💻 팀원(Team Member)

| https://github.com/HANTAEDONG | https://github.com/huzan2 | https://github.com/cjh-19 | https://github.com/LEEJH1029 | https://github.com/jangwonjun |
| --- | --- | --- | --- | --- |
| <img width = "300" src ="https://avatars.githubusercontent.com/u/132195232?s=96&v=4"> | <img width = "300" src ="https://avatars.githubusercontent.com/u/95648841?s=96&v=4"> | <img width = "300" src ="https://avatars.githubusercontent.com/u/66457014?s=96&v=4"> | <img width = "300" src ="https://avatars.githubusercontent.com/u/67615226?s=96&v=4"> | <img width = "300" src ="https://avatars.githubusercontent.com/u/41234293?s=96&v=4"> |
| Frontend Developer | Frontend Developer | Backend Developer, CI/CD | Backend Developer | Backend Developer |

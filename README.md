<h2 align="center">언제 어디서든 함께 운동해요!</h2>
<h3 align="center"><a>🐱SmartFit🐱</a></h3>

<div align="center">
  </br></br>
  <img src="https://img.shields.io/badge/java-007396?style=for-the-badge&logo=java&logoColor=white"> 
  <img src="https://img.shields.io/badge/python-3776AB?style=for-the-badge&logo=python&logoColor=white"> 
  <img src="https://img.shields.io/badge/html5-E34F26?style=for-the-badge&logo=html5&logoColor=white"> 
  <img src="https://img.shields.io/badge/css-1572B6?style=for-the-badge&logo=css3&logoColor=white"> 
  <img src="https://img.shields.io/badge/javascript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black"></br>
  <img src="https://img.shields.io/badge/mariaDB-003545?style=for-the-badge&logo=mariaDB&logoColor=white">
  <img src="https://img.shields.io/badge/spring-6DB33F?style=for-the-badge&logo=spring&logoColor=white"> 
  <img src="https://img.shields.io/badge/flask-000000?style=for-the-badge&logo=flask&logoColor=white">
  <img src="https://img.shields.io/badge/github-181717?style=for-the-badge&logo=github&logoColor=white">
  <img src="https://img.shields.io/badge/git-F05032?style=for-the-badge&logo=git&logoColor=white">
</div>
</br>

![image](https://github.com/user-attachments/assets/06f68d38-c998-4b1e-999e-2f42c4954026)

<strong>스마트핏</strong>, 언제 어디서든 함께하세요! Smart Fit, stay with us anytime, anywhere!
</br></br></br></br>

## 왜 스마트핏인가 ? Why SmartFit ? 

https://github.com/user-attachments/assets/46146f09-98d0-4285-8f9c-3a7eaae4cead

건강을 유지하고자 헬스장을 방문하지만, 헬스장은 시간 제약과 비싼 비용으로 발걸음이 돌아서게 된다. 특히 현대인들에게는 더더욱 말이다. 집에서는 올바르지 못한 자세로 운동이 되는지 마는지 모르는 경우가 태반이다.
하지만 언제 어디서든 운동을 할 수 있다면 말이 다르지 않을까? 스마트핏은 이런 점을 분석하여 개발했다.

스마트핏은 언제 어디서나 사용자가 달성하고자 하는 운동 목표를 설정하고 사전 학습된 모델을 통해 사용자 자세의 미세한 오류를 자동으로 인식하고, AI를 통해 즉각적으로 올바른 자세를 교정해준다. 
또한 사용자들의 운동 동기를 지속적으로 고취시키고 성과를 극대화할 수 있도록 지원한다.

Everyone visit the gym to stay healthy, but the gym turns around due to time constraints and high costs, especially for modern people. Most people at home do



n't know if they exercise in the wrong position.
But wouldn't it be different if you could exercise anytime, anywhere? Smart Fit was developed by analyzing these points.

With SmartFit, we set the exercise goals that users want to achieve anytime, anywhere, automatically recognize microscopic errors in the user's posture through pre-trained models, and propose the correct posture immediately through AI. 
It also continuously inspires users' motivation to exercise and helps them maximize performance.

<br><br>

---

## 시연 영상 및 운동 자세 비교 (Demo Videos and Exercise Posture Comparison)

### 스쿼트: 잘못된 자세 vs 올바른 자세

- **잘못된 스쿼트 자세 (Squat Incorrect Posture)**
![image](https://github.com/user-attachments/assets/a6c4a819-4efe-4900-ac06-44e6fc5b0507)
![image](https://github.com/user-attachments/assets/cd97cb13-b2bf-4b9d-a875-7dbca3943051)
![image](https://github.com/user-attachments/assets/1ed0eae0-9763-4b18-a2f3-19455ccd80cb)
</br>

- **올바른 스쿼트 자세 (Squat Correct Posture)**
![image](https://github.com/user-attachments/assets/387a3e4d-0861-45c5-a519-d1179415ba25)
</br>

### 푸쉬업: 잘못된 자세 vs 올바른 자세

- **잘못된 푸쉬업 자세 (Push-up Incorrect Posture)**
![image](https://github.com/user-attachments/assets/3b5cdee4-8f78-4413-b7f0-bae9f3db8905)
![image](https://github.com/user-attachments/assets/f92cbf2a-e7b3-4df2-a862-02fd9b01b6a5)
</br>

- **올바른 푸쉬업 자세 (Push-up Correct Posture)**
![image](https://github.com/user-attachments/assets/c44a95e7-1f56-4252-9962-4b227761081c)

<br>

# 모델 Model
![image](https://github.com/user-attachments/assets/cc6db52d-a5d1-40ad-858b-7538a9a203a1)



<br/>

# 백엔드 Backend
</br></br>
## 파일 구조 File Structure
![backend drawio](https://github.com/user-attachments/assets/0bea7117-adc3-4233-99fa-70ee42885fad)

</br></br>
## 프로젝트 실행 방법 How to Project Apply
</br>

### Flask Server 실행

1. 파이썬 설치 유무를 확인합니다.

2. 파일 내에 가상환경을 설정합니다.

Mac
```
pip install flask
```
Window
```
Window
python -m venv myenv
```


3. Flask 서버를 실행합니다.

```
cd model/web_test
```

```
python app.py
```

### SpringBoot 서버 실행방법

1. 파일 내에 있는 build.gralde의 코끼리 버튼이나, 직접 실행하여 build를 완료합니다.


2. Applcation을 실행합니다.

### 로컬 브라우저 방문


localhost:8080로 접속하면 서비스를 이용할 수 있습니다.

<br/>

## API 엔드포인트 

- /admin = admin페이지로 매핑
- /admin/addExercise = 운동추가, 추가 후 관리자 대시보드로 리다이렉트
- /admin/updateExercise/{fitid} = 운동수정
- /admin/deleteExercise/{fitid} = 운동 삭제

- /exercise = exerciseForm으로 이동
- /exerciseResult = Flask 서버와 연동

- /, /test = test 페이지로 매핑
- /login = 로그인 기능, enumType이 Admin이면 admin페이지,
user면 main페이지로 매핑
- /register = 회원가입 기능
- /myPage = 사용자 이름, 가입날짜 등 유저정보 확인
- /aboutUs = 페이지소개
- /setting = 운동 설정하는 페이지

  
# 프론트
![image](https://github.com/user-attachments/assets/7724d28c-b08e-43c1-8b63-ab46d100347c)
![image](https://github.com/user-attachments/assets/61bfd05a-344a-411e-99d7-9eefb0a986b4)

<br/>
---

<br/>

# Branch Rule

- master : 제품으로 출시될 수 있는 브랜치
- develop : 다음 출시 버전을 개발하는 브랜치
- feature : 기능을 개발하는 브랜치
- release : 이번 출시 버전을 준비하는 브랜치
- hotfix : 출시 버전에서 발생한 버그를 수정하는 브랜치

# Commit Message Rule

- feat (기능 구현)
- fix (버그 수정)
- docs (문서 작업 / README.md 등)
- style (코드 스타일, 세미콜론 누락 등 / 코드의 로직에 영향을 주지 않아야 한다.)
- refactor (코드 리팩토링)
- test (테스트 코드)
- chore (프로그램 실행과 관련 없는 작업, 빌드 시스템, 패키지 매니저 설정 등)
  <br/>



<br/>

# 추후 개발 기능정의서

- 개인화된 운동 프로그램 추천

: 사용자의 운동 기록과 목표를 기반으로 개인 맞춤형 운동 프로그램을 자동으로 생성하고 추천할 예정입니다.

- 소셜 피드 및 경쟁 기능

: 사용자가 친구나 다른 사용자들과 운동 기록을 공유하고, 서로 경쟁할 수 있는 소셜 피드와 리더보드를 도입할 예정입니다.

- 음성 피드백 기능

: 운동 중에 실시간으로 음성 피드백을 제공하여 사용자가 바로 자세를 수정할 수 있도록 지원하는 기능을 도입할 예정입니다.

- 운동 성과 분석 보고서

: 주간 또는 월간 단위로 사용자의 운동 성과를 분석하여 그래프나 차트 형태의 보고서를 제공하는 기능을 추가할 계획입니다.

- 다양한 운동 종목 지원

: 현재 제공하는 운동 외에도 요가, 필라테스, 고강도 인터벌 트레이닝(HIIT) 등 다양한 운동 종목을 지원할 계획입니다.

<br/>

---

<br/>

# Developers

<div align='center'>
<table>
    <thead>
        <tr>
            <th colspan="5">SmartFit Makers</th>
        </tr>
    </thead>
    <tbody>
        <tr>
          <tr>
            <td align='center'><img src="https://github.com/user-attachments/assets/fc4956d2-c46e-4316-884a-979c5c90ac2d" width="100" height="100"></td>
            <td align='center'><img src="https://github.com/user-attachments/assets/44394c72-19e2-4d84-87a2-d6523da9a28a" width="100" height="100"></td>
            <td align='center'><a href="https:/github.com/Suuuuuuuuuumin"><img src="./images/sumin.png" width="100" height="100"></td>
          </tr>
          <tr>
            <td align='center'><a href="https:/github.com/iksang0110">정익상</a></td>
            <td align='center'><a href="https:/github.com/Takeeatez">최이지</a></td>
            <td align='center'><a href="">오수민</a></td>
          </tr>
          <tr>
            <td>AI 파이썬 모델 구축<br/>Contact: wjddlrtkd0110@naver.com<br/>Github : dlrtkd0110</td>
            <td>Backend</br>Contact : choeiji13@gmail.com Github : Takeeatez</td>
            <td>Frontend<br/>Contact : osm374@gmail.com <br/>Github : Suuuuuuuuuumin</td>
          </tr>
        </tr>
    </tbody>
</table>
</div>


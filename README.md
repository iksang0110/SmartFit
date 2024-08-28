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

건강을 유지하고자 헬스장을 방문하지만, 헬스장은 시간 제약과 비싼 비용으로 발걸음이 돌아서게 된다. 특히 현대인들에게는 더더욱 말이다. 집에서는 올바르지 못한 자세로 운동이 되는지 마는지 모르는 경우가 태반이다.
하지만 언제 어디서든 운동을 할 수 있다면 말이 다르지 않을까? 스마트핏은 이런 점을 분석하여 개발했다.

스마트핏은 언제 어디서나 사용자가 달성하고자 하는 운동 목표를 설정하고 사전 학습된 모델을 통해 사용자 자세의 미세한 오류를 자동으로 인식하고, AI를 통해 즉각적으로 올바른 자세를 교정해준다. 
또한 사용자들의 운동 동기를 지속적으로 고취시키고 성과를 극대화할 수 있도록 지원한다.

Everyone visit the gym to stay healthy, but the gym turns around due to time constraints and high costs, especially for modern people. Most people at home don't know if they exercise in the wrong position.
But wouldn't it be different if you could exercise anytime, anywhere? Smart Fit was developed by analyzing these points.

With SmartFit, we set the exercise goals that users want to achieve anytime, anywhere, automatically recognize microscopic errors in the user's posture through pre-trained models, and propose the correct posture immediately through AI. 
It also continuously inspires users' motivation to exercise and helps them maximize performance.

<br><br>

---

## 시연 영상 및 운동 자세 비교 (Demo Videos and Exercise Posture Comparison)

### 스쿼트: 잘못된 자세 vs 올바른 자세

- **잘못된 스쿼트 자세 (Squat Incorrect Posture)**

    <div align="center">
        <img src="./images/SquatX1.jpg" alt="Squat Incorrect 1" width="400">
        <img src="./images/SquatX2.jpg" alt="Squat Incorrect 2" width="400">
        <img src="./images/SquatX3.jpg" alt="Squat Incorrect 3" width="400">
    </div>

- **올바른 스쿼트 자세 (Squat Correct Posture)**

    <div align="center">
        <img src="./images/SquatO.jpg" alt="Squat Correct" width="400">
    </div>

### 푸쉬업: 잘못된 자세 vs 올바른 자세

- **잘못된 푸쉬업 자세 (Push-up Incorrect Posture)**

    <div align="center">
        <img src="./images/Push-upX1.jpg" alt="Push-up Incorrect 1" width="400">
        <img src="./images/Push-upX2.jpg" alt="Push-up Incorrect 2" width="400">
        <img src="./images/Push-upX3.jpg" alt="Push-up Incorrect 3" width="400">
        <img src="./images/Push-upX4.jpg" alt="Push-up Incorrect 4" width="400">
    </div>

- **올바른 푸쉬업 자세 (Push-up Correct Posture)**

    <div align="center">
        <img src="./images/Push-upO.jpg" alt="Push-up Correct" width="400">
    </div>

<br>

# 모델 Model

- Model Architecture

  ![Model Architecture](./images/modelArchitecture.png)


<br/>

# 백엔드 Backend
</br></br>
## 파일 구조 File Structure
![backend drawio](https://github.com/user-attachments/assets/0bea7117-adc3-4233-99fa-70ee42885fad)


## 프로젝트 설치 방법 How to Project Install



## 프로젝트 실행 방법 How to Project Apply
</br>

## Flask Server 실행

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

## SpringBoot 서버 실행방법

1. 파일 내에 있는 build.gralde의 코끼리 버튼이나, 직접 실행하여 build를 완료합니다.


2. Applcation을 실행합니다.

## 로컬 브라우저 방문


localhost:8080로 접속하면 서비스를 이용할 수 있습니다.

<br/>

# 프론트

- System Architecture

  ![System Architecture](./images/systemArchitecture.png)

- Task Flow

  ![Task Flow](./images/taskFlow.png)

- Screen Flow

  ![Screen Flow](./images/screenFlow.png)
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

---

<br/>

# TO DO LIST

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
            <th colspan="5">SmartFit</th>
        </tr>
    </thead>
    <tbody>
        <tr>
          <tr>
            <td align='center'><a href="https:/github.com/iksang0110"><img src="./images/iksang.png" width="100" height="100"></td>
            <td align='center'><a href="https:/github.com/Takeetnez"><img src="./images/ez.png" width="100" height="100"></td>
            <td align='center'><a href="https:/github.com/Suuuuuuuuuumin"><img src="./images/sumin.png" width="100" height="100"></td>
          </tr>
          <tr>
            <td align='center'>정익상</td>
            <td align='center'>최이지</td>
            <td align='center'>오수민</td>
          </tr>
          <tr>
            <td>담당 : 모델 구축<br/>이메일 : wjddlrtkd0110@naver.com<br/>깃허브 : dlrtkd0110</td>
            <td>최이지</td>
            <td>담당 : Frontend<br/>이메일 : osm374@gmail.com <br/>깃허브 : Suuuuuuuuuumin</td>
          </tr>
        </tr>
    </tbody>
</table>
</div>


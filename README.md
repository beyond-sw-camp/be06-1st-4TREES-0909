<br></br>
---

<div align="center">
  <img src="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/82444759/adebff05-9206-4b6a-8ae2-475590c542e7"  align="center"/>
</div>

<div align="center">

<h1> 🤼‍♂️Team 4TREES</h2>

|                                                      🐯강태성(Leader)                                                      |                                                     🐶김우혁 (Backend)                                                     |🐺서재은(Backend)|🐱안귀나(Backend)|
|:---------------------------------------------------------------------------------------------------------------------:|:---------------------------------------------------------------------------------------------------------------------:|:---:|:---:|
|                                       [kangkings](https://github.com/kangkings)                                       |                                        [sue06004](https://github.com/sue06004)                                        |[seo-jae-eun](https://github.com/seo-jae-eun)|[gwina314](https://github.com/gwina314)|
| ![image](https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/82444759/4fb54008-8707-42ce-afe1-7629d5b4d3f0) | ![image](https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/82444759/d75c4e0d-8457-480c-9711-4b127811eb02) |![image](https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/82444759/00202b26-27e4-4696-9570-829af4388e37)|![image](https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/82444759/74d7bf68-0bf2-4082-8b9e-e36a43b2e555)
</div>


<br>

---

## 📌 프로젝트 주제

### 1-1 프로젝트 개요
>'직접 모집, 업체간 경쟁 입찰'이라는 방식으로
> 구매자가 주도하는 능동적인 형태의 공동구매 서비스


### 1-2 프로젝트 배경

최근 코로나 사태 이후 높은 물가가 지속되어 소비자들의 구매욕구가 낮아지고 있다.
이에 따라 각종 커머스 업체들은 무료배송 요건 충족 및 할인 등을 내걸고
2인구매와 같은 공동구매 형식의 서비스를 도입하기 시작했으며 이에 대한
소비자들의 만족도가 높을 뿐만 아니라, 이용 경험 또한 늘고 있는 것으로 조사되었다.
<div align="center">
<img src="https://file.mk.co.kr/meet/neds/2022/03/image_readtop_2022_203973_16469787734964652.jpg" style="zoom:50%" ></img>
</div>

토스는 더 나아가 2인 이상의 공동구매를 진행하여 규모의 경제 달성 및 저렴한 가격까지 실현하는 등
관련 시장 진출에 박차를 가하고 있으며 올웨이즈라는 공동구매 플랫폼은 5개월 만에
회원수 100만명을 돌파하는 등 뚜렷한 성장세를 보이고 있다.
<div align="center">
<img style="zoom:85%" src="https://file.mk.co.kr/meet/neds/2022/03/image_readbot_2022_203973_16469787734964654.jpg" align="center"></img>
</div>

<div>

### 1-3 기존 공동구매의 문제점
- 기존 플랫폼은 일반적인 커머스에서 구매자 숫자만 바뀌는 기존 커머스 플랫폼에 종속된 형태적 한계가 있음
<br></br>
- 업체간 투명한 경쟁을 막아 금액적, 품질적 마지노선이 플랫폼에 의해 정해지기 때문에 소비자들의 이익 실현이 방해 받음

### 관련 기사:

<a href="https://www.logibridge.kr/product/daily177">토스 최저가 공동구매 서비스</a>

<a href="https://pabii.com/news/278755/">대형마트의 공동구매 사례들</a>

<a href="https://www.mk.co.kr/economy/view.php?sc=50000001&year=2022&no=203973">배달비·미술품부터 로봇까지… 공구, 어디까지 해봤니?</a>


</div>



### 1-4 서비스 흐름
<div align="center">
<img src="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/82444759/93fbc229-00ee-4c1c-8ce9-75094de61f9f" style="zoom: 60%"></img>
</div>

---

## 📚 기술 스택

&nbsp;&nbsp;&nbsp;<img src="https://img.shields.io/badge/MariaDB-003545?style=flat&logo=MariaDB&logoColor=white"/></a>
&nbsp;&nbsp;&nbsp;<img src="https://img.shields.io/badge/Haproxy-6DB33F?style=flat&logo=haproxy&logoColor=white&color=green"/></a></a>
<img src="https://img.shields.io/badge/github-181717?style=flat&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/git-F05032?style=flat&logo=git&logoColor=white">

---

## 🖥️ 시스템 아키텍처

<div align="center">
<img src="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/82444759/ba3469c1-3044-4b2f-96db-5779d2af2aca" style="zoom: 50%"></img>
</div>

### 예상 문제상황
- 기한 만료 및 공구 모집 실패에 따른 공동구매의 잦은 상태 변화(수정)
  <br></br>
- 상품정보 등록 및 삭제와 더불어 공동구매 등록 및 삭제까지 기존 커머스 대비 높은 생성, 수정 수요
  <br></br>
- 입찰자의 몰림 현상 발생 가능성
  <br></br>

### 대응책
- HAPROXY를 이용한 DB 부하 분산 및
  <br></br>
- Replication 구성을 통한 데이터 동기화

---
## 📄 요구사항 정의서
<a href="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/wiki">요구사항 정의서</a>

---

## 📋 ERD

<div align="center">
<img src="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/82444759/66f992d1-5753-420d-8081-fee692fb5591" style="zoom: 50%"></img>
</div>

---

## ✨ DR(재난 복구)

- 모니터링 시스템 및 Haproxy 로그, DB로그 분석을 통한 장애 감지 및 진단.
<br></br>
- HW,SW,네트워크등 문제 원인 파악 후 복구
  <br></br>
- 다운된 DB서버와 기존서버의 Replication 재설정을 통한 데이터 복제 및 동기화
  <br></br>
- 다운된 서버 재 활성화

---

## SQL 실행 결과

<details>
<summary>일반 유저 회원 가입</summary>
<div>
<figure align="center"> 
  <img src="z"/>
    <p>~~~ 조회</p>
 </figure>
</div>
</details>

<details>
<summary>업체 유저 회원 가입</summary>
<div>
<figure align="center"> 
  <img src="z"/>
    <p>~~~ 조회</p>
 </figure>
</div>
</details>

<details>
<summary>일반 유저 로그인</summary>
<div>
<figure align="center"> 
  <img src="z"/>
    <p>~~~ 조회</p>
 </figure>
</div>
</details>

<details>
<summary>업체 유저 로그인</summary>
<div>
<figure align="center"> 
  <img src="z"/>
    <p>~~~ 조회</p>
 </figure>
</div>
</details>

<details>
<summary>결제 수단 추가</summary>
<div>
<figure align="center"> 
  <img src="z"/>
    <p>~~~ 조회</p>
 </figure>
</div>
</details>

<details>
<summary>배송지 추가</summary>
<div>
<figure align="center"> 
  <img src="z"/>
    <p>~~~ 조회</p>
 </figure>
</div>
</details>

<details>
<summary>공구 등록 및 조회</summary>
<div>
<figure align="center"> 
  <img src="z"/>
    <p>~~~ 조회</p>
 </figure>
</div>
</details>

<details>
<summary>입찰 등록 및 입찰 대기 조회</summary>
<div>
<figure align="center"> 
  <img src="z"/>
    <p>~~~ 조회</p>
 </figure>
</div>
</details>

<details>
<summary>공구 참여</summary>
<div>
<figure align="center"> 
  <img src="z"/>
    <p>~~~ 조회</p>
 </figure>
</div>
</details>

<details>
<summary>구매자 정보 조회</summary>
<div>
<figure align="center"> 
  <img src="z"/>
    <p>~~~ 조회</p>
 </figure>
</div>
</details>




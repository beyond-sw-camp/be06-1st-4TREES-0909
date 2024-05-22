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

## 📚 기술 스택

### OS:
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black"/> <img src="https://img.shields.io/badge/Vmware-607078?style=flat&logo=Vmware&logoColor=white"/>  <img src="https://img.shields.io/badge/CentOS-262577?style=flat&logo=CentOS&logoColor=white"/>

### DB:
<img src="https://img.shields.io/badge/MariaDB-003545?style=flat&logo=MariaDB&logoColor=white"/>

### Load Balancer:
<img src="https://img.shields.io/badge/HAPROXY-blue?style=flat&logo=googlepubsub&logoColor=white"/>

### VCS:
<img src="https://img.shields.io/badge/github-181717?style=flat&logo=github&logoColor=white">
<img src="https://img.shields.io/badge/git-F05032?style=flat&logo=git&logoColor=white">


## 🖥️ 시스템 아키텍처

<div align="center">
<img src="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/82444759/5f2eb344-23ed-4348-987e-7037cacf735d"></img>
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

## 📄 요구사항 정의서
- Wiki: <a href="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/wiki#4trees-erd-0909-%EC%84%9C%EB%B9%84%EC%8A%A4">요구사항 정의서</a>


## 📋 ERD

- Wiki: <a href="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/wiki#4trees-erd-0909-%EC%84%9C%EB%B9%84%EC%8A%A4">ERD</a>
<div align="center">
<img src="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/69503955/bcfb63d3-44ba-4b8a-b45b-08609fb9a263" style="zoom: 50%"></img>

</div>

## ✨ DR(재난 복구)

### 로그 분석
> - Haproxy 로그, DB로그 분석을 통한 장애 감지 및 진단.

### 문제 파악 및 복구
> - HW,SW,네트워크등 문제 원인 파악 후 복구

### Replication 재설정
> - 다운된 DB서버와 기존서버의 Replication 재설정을 통한 데이터 복제 및 동기화

### 재 활성화
> - 다운된 서버 재 활성화


## SQL 개발

### 실행결과

<details>
<summary>일반 유저 회원가입</summary>
<div>

```
INSERT INTO USER
(user_type, user_name, user_email, user_password, user_phone_number, user_birth, user_sex, user_point, user_status, user_email_status, user_phone_status)
VALUES
('inapp', '홍길동', 'hong1@gmail.com', 'qwer1234',' 010-1111-1111', '990111', '남', '0', '활동', true, true);
```

<figure align="center">
  <img src="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/82444759/f380ffa3-afec-4792-acf9-cd1ef131d363"/>
    <p>일반 유저 회원가입</p>
 </figure>
</div>
</details>

<details>
<summary>업체 유저 회원가입</summary>
<div>

```
INSERT INTO COMPANY
(company_name, company_email, company_password, company_birth, company_sex, company_phone_number, company_address, company_account,company_bank,company_depo_name,company_reg_num,company_ip, company_email_status, company_phone_status)
values
('mathew', 'handsome@gmail.com', 'qwer1234', '1980-11-11', '남', '010-9223-3172', '4층 1강의실', '162478-12-142123', '부산은행', 'mathew', '127345222', '022220', true, true );

```

<figure align="center">

  <img src="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/82444759/0fbe158f-0e20-43b4-999b-793675e9393a"/>
    <p>업체 유저 회원가입</p>
 </figure>
</div>
</details>

<details>
<summary>일반 유저 로그인</summary>
<div>

```
SELECT user_email, user_password 
FROM USER 
WHERE user_email = 'hong1@gmail.com';

```

<figure align="center"> 

  <img src="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/82444759/681ac42d-8c89-4654-906e-0ea45282b9b6"/>
    <p>email을 기준으로 조회</p>
 </figure>
</div>
</details>

<details>
<summary>업체 유저 로그인</summary>
<div>

```
SELECT company_email , company_password
FROM COMPANY
WHERE company_email = 'dlflq11@gmail.com';

```

<figure align="center">

  <img src="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/82444759/71d453b8-db0b-4fed-8bdb-c99eeb93035b"/>
    <p>email을 기준으로 조회</p>
 </figure>
</div>
</details>

<details>
<summary>결제 수단 추가</summary>
<div>

```
INSERT INTO PAYMENT_METHOD 
(payment_method_idx, user_idx, payment_method_name, card_company, card_number, card_cvc, card_y_enddate, card_m_enddate, card_pwd) 
VALUES 
(4, 4, '국민카드', '국민', '6547-8915-7534-7878', '565', '25', '01', '9874');

```

<figure align="center"> 

  <img src="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/82444759/f57f553c-df9b-412b-b39b-335d9f2242c5"/>
    <p>결제 수단 추가</p>
 </figure>
</div>
</details>

<details>
<summary>배송지 추가</summary>
<div>

```
INSERT INTO `gonggu`.`ADDRESS` 
(`address_info`, `user_idx`)
VALUES 
('서울특별시 동작구 장승배기로 171 404호', '1');

```

<figure align="center"> 

  <img src="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/82444759/e9965693-edda-4494-be5c-b9120cbf76d6"/>
    <p>배송지 추가</p>
 </figure>
</div>
</details>

<details>
<summary>공구 등록</summary>
<div>

```
INSERT INTO GROUP_BUY
(category_idx, user_idx, gpby_title, gpby_content, gpby_quantity) 
VALUES 
(2, 1, "딸기 1kg 선제좀", "맛있는 딸기 1kg 싸게 삽니다.", 20);

```

<figure align="center"> 

  <img src="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/82444759/d9126147-3d62-4457-9cbc-633684742599"/>
    <p>최초 공구 등록</p>
 </figure>
</div>
</details>

<details>
<summary>진행중인 공구 조회</summary>
<div>

```
SELECT * 
FROM GROUP_BUY 
WHERE gpby_status = "진행";

```

<figure align="center"> 

  <img src="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/167496262/499effe0-1e0d-4476-93ce-815972cfe027"/>
    <p>입찰이 끝나고 모집 진행중인 공구 조회</p>
 </figure>
</div>
</details>


<details>
<summary>입찰 대기 조회</summary>
<div>

```
SELECT gpby_title, gpby_content, gpby_status, user_name 
FROM GROUP_BUY 
LEFT JOIN USER ON GROUP_BUY.user_idx = USER.user_idx
WHERE gpby_status = '입찰 대기';

```

<figure align="center"> 

  <img src="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/167496262/18404542-50b0-4767-87f2-e2e81fd578bc"/>
    <p>상태가 '입찰 대기'인 공구 조회</p>
 </figure>
</div>
</details>

<details>
<summary>입찰 등록</summary>
<div>

```
INSERT INTO `gonggu`.`BID` 
(`product_idx`,`gpby_idx`, `bid_price`)
VALUES 
(1, 1, 1000);

```

<figure align="center"> 

  <img src="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/167496262/d6f84281-c4a8-4e53-92f6-0412612b17a6"/>
    <p>입찰 등록</p>
 </figure>
</div>
</details>

<details>
<summary>공구 참여</summary>
<div>

```
INSERT INTO `ORDER` 
(user_idx, gpby_idx, order_address, order_count, order_card_company, card_number, card_cvc, card_y_enddate, card_m_enddate, card_pwd) 
VALUES 
('3', '2', '서울특별시 동작구 보라매로', '10', '현대카드','5235-9981-1255-1237', '487', '25', '01', '4567');

```

<figure align="center"> 

  <img src="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/167496262/5c4f8b91-f13d-4a4a-9292-56297c75d064"/>
    <p>주문정보 작성하여 공구 참여</p>
 </figure>
</div>
</details>

<details>
<summary>구매자 정보 조회</summary>
<div>

```
SELECT U.user_name, U.user_email, O.order_address, O.order_count, P.product_idx, product_name
FROM COMPANY_INFO CI JOIN PRODUCT P ON CI.com_info_idx = P.company_idx
JOIN BID B ON P.product_idx = B.product_idx
JOIN `ORDER` O ON B.gpby_idx = O.gpby_idx
JOIN USER U ON O.user_idx = U.user_idx
JOIN GROUP_BUY GB ON GB.gpby_idx = B.gpby_idx 
WHERE B.bid_select = true and  GB.gpby_status = "입찰 완료" and CI.com_info_idx = 4;

```

<figure align="center"> 

  <img src="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/167496262/e789e43c-5105-4989-943f-0655a6b29c3d"/>
    <p>주문 완료한 구매자들의 정보를 조회</p>
 </figure>
</div>
</details>

<details>
<summary>결제</summary>
<div>

```
SELECT
order_idx, user_idx, order_count, order_card_company, card_number, card_cvc, card_y_enddate, card_m_enddate, card_pwd
FROM `ORDER` 
WHERE order_idx=2;

UPDATE `ORDER`
SET order_status="완료"
WHERE order_idx=2;

```

<figure align="center"> 

  <img src="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/167496262/26eea8c1-0507-426a-8cca-380cba43108a"/>
    <p>주문 정보에 등록된 정보로 결제 처리</p>
 </figure>
</div>
</details>

<details>
<summary>관심 공구 등록</summary>
<div>

```
INSERT INTO FAVORITES
(gpby_idx, user_idx)
VALUES
(1,1),(1,3),(1,5);

```

<figure align="center"> 

  <img src="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/167496262/ad2612da-a531-408b-addc-03ede3447636"/>
    <p>공구 관심 등록</p>
 </figure>
</div>
</details>

<details>
<summary>Q 등록</summary>
<div>

```
INSERT INTO QnA
(user_idx,product_idx,qna_title,qna_content)
values
(2,6, '불량제품', '불량품인데 환불 되나요?');

```

<figure align="center"> 

  <img src="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/167496262/ec798102-c5d1-4e12-998d-7e600da20224"/>
    <p>질문 등록</p>
 </figure>
</div>
</details>

<details>
<summary>A 등록</summary>
<div>

```
UPDATE QnA SET qna_answer = "불가능 합니다."
WHERE product_idx = 5 AND user_idx = 1;
UPDATE QnA SET qna_answer_date = current_time()
WHERE product_idx = 5 AND user_idx = 1;

```

<figure align="center"> 

  <img src="https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/167496262/3e46032b-e9c1-4ae9-9e4c-ada2df08f0f0"/>
    <p>답변 등록</p>
 </figure>
</div>
</details>

### 성능 개선

- INDEX
  ![image](https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/167496262/0282e672-5b99-4ab9-b3dd-0cf9513a693a)


- SP
![image](https://github.com/beyond-sw-camp/be06-1st-4TREES-0909/assets/82444759/74596b10-86dc-47ba-a490-fb49fe5973a4)

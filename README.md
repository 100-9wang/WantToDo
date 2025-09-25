# 원두(WantToDo) 프로젝트

---

## 프로젝트 개요
**프로젝트명:** 원두(WantToDo)  
**프로젝트 기간:** 2024.12.27 ~ 2025.03.05  
**프로젝트 유형:** 4인 팀 프로젝트  

**한 줄 소개:**  
> Spring Framework와 Oracle DB 기반 웹 애플리케이션으로,  
> 사용자의 MBTI 성향에 따라 맞춤형 상품 추천과  
> 날씨 기반 어울리는 상품 추천으로  
> 사용자의 구매 편의성을 제공하는 플랫폼입니다.

---

## 역할
| 역할 | 상세 |
|------|------|
| 환경 및 기획 설계 | 프로젝트 초기 환경 구성 및 기획 의도 설계 |
| 프로젝트 병합 | 전체 프로젝트 병합 및 오류 분석/해결 |
| SQL 최적화 | Oracle SQL 인덱싱, 프로시저 최적화 |
| UI/UX | 공통 UI/UX 제작 |
| 권한 관리 | 사용자 권한 분리 및 기능 제어 |
| 예외 처리 | 에러 발생 시 예외 처리 페이지 제작 |
| 콘텐츠 제작 | MBTI 검사 결과 별 상품 추천 |
| 성능 테스트 | JMeter 성능 테스트 진행 |

---

## 기술 스택
| 구분 | 기술 |
|------|------|
| **Backend** | Java 1.6 (Spring Framework, Spring MVC) |
| **WAS** | Apache Tomcat v9.0 |
| **Frontend** | JSP, HTML/CSS, JavaScript, Bootstrap, Figma |
| **Database** | Oracle SQL |
| **Tools** | Git, Eclipse, SQL Developer |
| **Collaboration** | Discord, GitHub, Notion |

---

##  주요 기능 목표
- 🌟 MBTI 기반 맞춤형 상품 추천  
- 🔒 사용자 권한 분리 및 기능 제어 (관리자 / 사용자)  
- 🎨 공통 UI/UX 제작 및 예외 처리 페이지 구현  
- 📊 Oracle SQL 최적화 (인덱싱, 프로시저, 뷰 활용)  
- ⚡ 성능 개선 및 테스트 (JMeter, JUnit)  

---

##  산출물 구성

### (1) 설계 & 구조

<details>
<summary>📊 MVC 구조 동작 순서 다이어그램</summary>

<img width="800" height="533" alt="MVC 구조 다이어그램" src="https://github.com/user-attachments/assets/699c6fb5-0e4b-49c9-96be-0602bf602954" />

</details>

<details>
<summary>🗂 정보 구조도</summary>

<img width="800" height="533" alt="정보 구조도1" src="https://github.com/user-attachments/assets/84b6056b-8098-4200-9df2-de17bb9db530" />  
<img width="800" height="533" alt="정보 구조도2" src="https://github.com/user-attachments/assets/45096d41-75af-45a0-aea3-7cc1aa836e98" />  
<img width="800" height="533" alt="정보 구조도3" src="https://github.com/user-attachments/assets/e9354ae7-5da2-4ab7-b2d7-d61293b3d8c3" />

</details>

<details>
<summary>📝 스토리보드</summary>

<img width="743" height="477" alt="스토리보드1" src="https://github.com/user-attachments/assets/1cf9a11e-e7dc-4401-8df3-1a27fcc21ce8" />  
<img width="721" height="478" alt="스토리보드2" src="https://github.com/user-attachments/assets/67333fe3-35d0-449e-8bc0-dbc1399c3c28" />  
<img width="747" height="478" alt="스토리보드3" src="https://github.com/user-attachments/assets/e09087d8-e2e3-4a46-97be-3541211583fb" />  
<img width="740" height="482" alt="스토리보드4" src="https://github.com/user-attachments/assets/4dd37c32-16b5-4cef-96e1-8118d8adc720" />  
<img width="740" height="479" alt="스토리보드5" src="https://github.com/user-attachments/assets/95086642-d2af-47f8-a3f9-717dec744629" />  
<img width="757" height="477" alt="스토리보드6" src="https://github.com/user-attachments/assets/67879fe2-ee2a-493d-b18c-bf16d33f4a61" />  
<img width="762" height="477" alt="스토리보드7" src="https://github.com/user-attachments/assets/61fe9175-b160-41d4-8597-36fb97604f96" />  
<img width="772" height="475" alt="스토리보드8" src="https://github.com/user-attachments/assets/bd6c6ea5-c5a7-4138-9a15-7a322ccf297e" />  
<img width="759" height="480" alt="스토리보드9" src="https://github.com/user-attachments/assets/3a4409f7-3072-4d9c-ac57-2075b0c6d579" />

</details>

<details>
<summary>📚 ERD 및 테이블 명세서</summary>

<img width="900" height="422" alt="ERD1" src="https://github.com/user-attachments/assets/e7abeddd-a7fc-49cf-9f7f-7ecd5e7462b2" />  
<img width="1226" height="663" alt="ERD2" src="https://github.com/user-attachments/assets/8dacf878-e538-4d69-9046-56539eb437ae" />  
<img width="1373" height="419" alt="ERD3" src="https://github.com/user-attachments/assets/fae44ba2-8267-4a1d-a287-a6c489198a11" />  
<img width="1376" height="514" alt="ERD4" src="https://github.com/user-attachments/assets/85f96237-77ad-4eaa-a9f9-695342261938" />  
<img width="1373" height="531" alt="ERD5" src="https://github.com/user-attachments/assets/1fff64a6-6c22-4f5f-8625-6a265f2dcb73" />  
<img width="1375" height="399" alt="ERD6" src="https://github.com/user-attachments/assets/2d93ebfc-a754-48cd-8f00-fe21182694c4" />  
<img width="1375" height="622" alt="ERD7" src="https://github.com/user-attachments/assets/dae2193b-297e-43dc-874c-6ed72295981e" />  
<img width="1528" height="181" alt="ERD8" src="https://github.com/user-attachments/assets/6d1d9c1c-3472-4ba1-b558-5a0a74a57462" />  
<img width="1528" height="578" alt="ERD9" src="https://github.com/user-attachments/assets/498e0156-9af8-4448-8797-e61e623c0856" />

</details>


---

### (2) 구현 & 개발
<details>
<summary>JMeter 성능 테스트 결과</summary>
<img width="723" height="422" alt="Image" src="https://github.com/user-attachments/assets/eabe63d8-8311-4ca2-beb2-ad2322a9077a" />
<img width="718" height="256" alt="Image" src="https://github.com/user-attachments/assets/4b850ad2-9964-4da5-b74c-e0f5fe2ac036" />
<img width="713" height="341" alt="Image" src="https://github.com/user-attachments/assets/c513a315-4696-4e39-828c-620c3b01d37e" />
<img width="668" height="222" alt="Image" src="https://github.com/user-attachments/assets/77bbbc04-c4b2-423f-9601-1cd80a1e7acc" />
</details>
<details>
<summary>JUnit 테스트 결과</summary>
<img width="527" height="704" alt="Image" src="https://github.com/user-attachments/assets/4cc1c465-32d2-4aad-8081-271ea6f5a76e" />
<img width="3286" height="1080" alt="Image" src="https://github.com/user-attachments/assets/392fd81a-26d9-43d5-add5-16293bf8c097" />
<img width="1222" height="871" alt="Image" src="https://github.com/user-attachments/assets/6529affa-fcb8-4eb1-af36-93e41e6cc448" />
</details> 
<details>
<summary>XSS 공격 방지 필터 구현</summary>
<img width="640" height="313" alt="Image" src="https://github.com/user-attachments/assets/9cce0ebc-a818-4821-9e99-128ff1b2dd24" />

  적용 후
<img width="766" height="253" alt="Image" src="https://github.com/user-attachments/assets/4f6e10c4-b410-4382-bce7-4223ae870905" />
<img width="484" height="114" alt="Image" src="https://github.com/user-attachments/assets/274ae7c9-f97f-4deb-a62d-522a62cf4e40" />
</details>
<details>
<summary>배치 프로그램 구조 및 실행 결과</summary>
<img width="681" height="686" alt="Image" src="https://github.com/user-attachments/assets/42f8d298-5ef1-47b1-a81f-6dae75493d04" />
<img width="441" height="406" alt="Image" src="https://github.com/user-attachments/assets/e7662706-43e0-46a0-8597-9b9449c99db5" />

배치 프로그램 로그
<img width="461" height="555" alt="Image" src="https://github.com/user-attachments/assets/7acaec05-96fc-43a0-8679-da229668f57e" />

배치 프로그램 실행 전
<img width="997" height="103" alt="Image" src="https://github.com/user-attachments/assets/bb65bcbe-30d9-4eb8-a1dd-c861dbea0295" />

배치 프로그램 실행 후
<img width="992" height="98" alt="Image" src="https://github.com/user-attachments/assets/59e2e895-5245-428d-a88a-d3867f24cbcb" />
</details>

---

### (3) 성능 & 최적화
- SQL 최적화
- 인덱스 추가, 뷰(View) 활용
```sql
CREATE INDEX idx_goods_category ON goods(category);
CREATE INDEX idx_recommend_mbti ON recommend(mbti_type);

CREATE OR REPLACE VIEW v_recommend_goods AS
SELECT g.goods_id, g.goods_name, g.category, r.mbti_type
FROM goods g
JOIN recommend r ON g.category = r.category;
```

---

## 트러블슈팅

**문제:**  
MyBatis Mapper SQL 바인딩 문제  

**원인 분석:**  
parameterType 불명확 및 JDBC 타입 미지정으로 인해 일부 파라미터가 바인딩되지 않음.

**해결 방법:**  
MyBatis Mapper XML에 `jdbcType` 명시.
```xml
<select id="selectSellerGoodsList2" parameterType="String" resultMap="goodsResult">
    <![CDATA[
    SELECT g.*, d.fileName, ROW_NUMBER() OVER (ORDER BY g.goods_create_date DESC) AS rn
    FROM c_goods g
    JOIN c_image_goods d ON g.goods_id = d.goods_id
    WHERE d.filetype = 'main_image'
      AND g.goods_status = #{goods_status, jdbcType=VARCHAR}
      AND g.goods_category IN ('원두')
      AND g.mem_id = #{mem_id, jdbcType=VARCHAR}
    ]]>
</select>
```

**성과:**

SQL 파라미터 정상 바인딩
DB 쿼리 실행 성공률 100% 향상
유지보수 과정에서 유사 문제 재발 방지

---

## 결과물 & 시연
## 📺 결과물 & 시연

[![프로젝트 시연 영상1](https://img.youtube.com/vi/SI6_xEXGLEY/0.jpg)](https://youtu.be/SI6_xEXGLEY)  
[![프로젝트 시연 영상2](https://img.youtube.com/vi/6JfOO6TT13U/0.jpg)](https://youtu.be/6JfOO6TT13U)  
[![프로젝트 시연 영상3](https://img.youtube.com/vi/8qZ6GBIJkhU/0.jpg)](https://youtu.be/8qZ6GBIJkhU)  
[![프로젝트 시연 쇼츠](https://img.youtube.com/vi/cR8Q7oYmx8k/0.jpg)](https://youtube.com/shorts/cR8Q7oYmx8k?feature=share)

[Notion 정리 링크] https://www.notion.so/WantToDo-2796a2e81c4e8198bcf2ec43bf962d4a?source=copy_link

---

## 향후 개선 계획
- 추천 알고리즘 고도화 (단순 MBTI 질문 → 질문지 및 유형 도출 알고리즘 추가 작성)
- React 기반 프론트엔드 리팩토링 및 반응형 UI 적용




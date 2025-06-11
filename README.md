# FlowOne ERP (Spring Boot JSP)

Spring Boot 기반의 사내 ERP 시스템입니다.  
현재는 인사관리 모듈을 중심으로 사원 등록 및 근태 관리 등의 기능을 개발할 예정입니다.

---

## ✅ 프로젝트 개요

- **프로젝트명:** FlowOne ERP
- **기술스택:**
  - Java 17
  - Spring Boot 3.2.5
  - JSP (Tomcat Embedded)
  - Oracle Database
  - Gradle
  - Lombok
  - Spring Security 

---

## ✅ 실행 방법

### 1. 프로젝트 clone

```bash
git clone https://github.com/your-username/flowone.git
cd flowone
2. IntelliJ에서 Gradle 프로젝트로 열기
build.gradle 인식되도록 열기

Gradle sync 후 실행

3. 서버 실행
bash
복사
편집
./gradlew bootRun
또는 IntelliJ에서 FlowOneApplication.java 실행

✅ 접속 테스트
txt
복사
편집
GET http://localhost:8080/hello
출력:

복사
편집
Hello, FlowOne ERP!
✅ 디렉토리 구조
bash
복사
편집
src/
 └─ main/
     ├─ java/com.flowone
     │   ├─ controller/
     │   ├─ service/
     │   ├─ config/
     │   └─ FlowOneApplication.java
     ├─ resources/
     │   └─ application.properties
     └─ webapp/
         └─ WEB-INF/views/
             └─ hello.jsp
✅ 향후 기능 계획
 사원 등록/조회/수정

 근태 관리 (출퇴근 기록)

 급여 계산

 DB 연동 (Oracle + MyBatis)


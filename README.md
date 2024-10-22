# 김영한님의 spring 스프링부트와 JPA 활용 1편 강의 정리
<br>
<hr>
<br>

## ✔️ jpashop directory
### 학습 범위 : 2-1-1 - 2-1-5
- 프로젝트 생성 및 환경 설정

- thymeleaf - jpa - h2 연동

- jpa 쿼리 로그 출력 > `p6spy`
<br>
<br>

### 학습 범위 : 2-2-1 - 2-3-2
- 엔티티 설계

- 엔티티 설계 시 주의점
  - 가급적 Setter 미사용
  - 모든 연관 관계는 지연 로딩(`LAZY`) 사용... 꼭!
  - `OneToOne`, `ManyToOne` 와 같이 `xToOne`인 경우 FetchType이 즉시로딩이므로 `LAZY`를 걸야줘야한다.
  - 컬렉션은 생성자에서 초기화 하지말고 필드에서 바로 초기화
<br>
<br>

### 학습 범위 : 2-4-1 - 2-4-3

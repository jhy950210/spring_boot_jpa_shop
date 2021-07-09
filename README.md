# spring_boot_jpa_shop
스프링부트 jpa 활용 shop

##환경
- Spring boot 2.4
- gradle
- Java 11
- Thypeleaf : modern server-side Java template
- Spring Data JPA
- H2 Database
- Lombok (plug in - lombok 설치, Annotation Processors - Enable Annotation Processing 체크)

##기능
- 회원기능
    - 회원 등록, 조회
- 상품기능
    - 상품 등록, 수정, 조회
- 주문기능
    - 상품 주문, 주문 내역 조회, 주문 취소
- 기타요구사항
    - 재고 관리, 상품 종류는 도서/음반/영화
    
 ##도메인 아키텍쳐
 ![https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e1811ba1-b5ca-488f-939f-3258e69878cc/Untitled.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/e1811ba1-b5ca-488f-939f-3258e69878cc/Untitled.png)

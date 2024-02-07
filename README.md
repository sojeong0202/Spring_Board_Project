# Spring_Board_Project

## 개발 환경
1. IDE: IntelliJ IDEA
2. Spring Boot 3.2.2
3. JDK 17
4. MySQL
5. Spring Data JPA
6. Thymeleaf

## 게시판 주요 기능
1. 글쓰기(Create): POST /posts
2. 글목록 조회(Read): GET /posts
3. 글조회(Read): GET /posts/{postId}
4. 글수정(Update): PUT or PATCH /posts/{postId}
5. 글삭제(Delete): DELETE /posts/{postId}
6. 페이징 처리(Pagination): GET /posts?page={pageNumber}&size={pageSize}
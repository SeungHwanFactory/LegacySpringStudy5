# LegacySpringStudy5
Ajax를 이용한 댓글 구현 및 댓글 페이징 처리

---
<h1> 📖 흐름</h1>
  
---
* 댓글 테이블 생성 (tbl_reply)
  *  ReplyVO 클래스 추가
  *  ReplyMapper 클래스와 XML로 처리
  *  테스트 케이스 작성
  *  CURD 작업
  *  CRUD 테스트 케이스 작성

* 서비스 로직 및 컨트롤러

  * ReplyService 인터페이스와 구체 클래스 ReplyServiceImpl 생성
  * ReplyController 설계
    * 등록 /replies/new POST
    * 조회 /replies/:rno GET
    * 삭제 /replies/:rno DELETE
    * 수정 /replies/:rno PUT or PATCH
    * 페이지 /replies/pages/:bno/:pgae GET
  * 테스트 케이스 작성
  * CRUD 확인

* JavaScript 모듈화

  * reply.js 등록 처리
  * 댓글 목록 처리
  * 댓글 삭제 및 갱신
  * 댓글 수정


* 댓글 관련 이벤트 처리

* 댓글 페이징 처리

  * 인덱스 설계
  * 인덱스를 이용한 페이징 쿼리
  * 댓글 숫자 파악 후 서비스 로직 및 controller변경

* 댓글 페이징 화면처리


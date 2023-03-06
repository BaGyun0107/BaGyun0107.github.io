---
layout: post
title: Semicolon-Nostanding
description: >
  22.05 - 22.06 (4주)  
  음식점, 카페 등 매장 이용 시간대별 예약과 알람, 평판리뷰 확인 가능한 예약 서비스
sitemap: false
hide_last_modified: true
---

**GitHub :** <https://github.com/codestates/NoStanding>  
**배포링크 :** <https://www.semicolon-nostanding.com>  
**상세정보 :** <https://codestates.notion.site/7-semicolon-Nostanding-297a7ffb182f4d1b852847f2628e6c26>

<div class="slider" align="center">
    <div><img src= "/assets/img/nostanding/nostanding1.jpeg" style="width: auto; height: 400px;"></div>
    <div><img src= "/assets/img/nostanding/nostanding2.png" style="width: auto; height: 400px;"></div>
    <div><img src= "/assets/img/nostanding/nostanding3.png" style="width: auto; height: 400px;"></div>
    <div><img src= "/assets/img/nostanding/nostanding4.png" style="width: auto; height: 400px;"></div>
    <div><img src= "/assets/img/nostanding/nostanding5.png" style="width: auto; height: 400px;"></div>
    <div><img src= "/assets/img/nostanding/nostanding6.png" style="width: auto; height: 400px;"></div>
    <div><img src= "/assets/img/nostanding/nostanding7.png" style="width: auto; height: 400px;"></div>
</div>

<script>
    $(document).ready(function(){
      $('.slider').slick({
        autoplay: true,
        autoplaySpeed: 2500,
        fade: true,
        dots: true
      });
    });
  </script>

**Stack :** `JavaScript` `NodeJS` `Sequelize` `JWT` `Express` `MySQL` `Axios`

- Position : Back-end
- 프로젝트의 전반적인 기획 및 구상
  - [와이어프레임](https://miro.com/app/board/uXjVOyoJqCo=/) 작성
  - 프로젝트 기획 의도 및 아이디어 제시
- CRUD 작성
  - 비밀번호 암호화 crypto 모듈로 PBKDF2 암호화 방식 진행
  - JWT로 쿠키를 사용한 로그인 방식
- DB 구축
  - MySQL를 Sequelize 활용하여 연동
  - MySQL Workbench로 DBDiagram 작성 및 [DB Schema](https://github.com/codestates/NoStanding/wiki/DB-Schema) 작성
- 댓글 수, 별점 필터링 후 재정렬 구현
- HTTPS 배포
  - AWS를 활용한 배포
- 알람 구현 및 지난 알람 DB 삭제
  - node-schedule을 활용하여 지난 알람 DB 삭제
  - sequelize-transaction으로 오류 발생 시 알람 생성 제한
- API 문서 작성
  - [Swagger](https://server.semicolon-nostanding.com/api-docs/) 활용
- 이메일 인증 구현
  - ejs와 nodemailer로 이메일 인증 및 비밀번호 찾기 구현
- 검색필터링 구현
  - query문 작성하여 띄어쓰기 구분제거
- OAuth 로그인 구현
  - 카카오, 구글 로그인 구현

## 서비스 기획 의도

---

날이 따뜻해지고 점점 외부 활동하는 사람이 늘어가는 추세로, 음식점, 카페 등 여러 방면의 가게를 시간대별로 예약을 잡아 줄을 서서 기다리는 시간을 최소화하는 예약 서비스입니다. 두번째 팀 프로젝트로 첫번째 프로젝트를 진행하며 부족했던 부분을 개선하여 기획 / 개발하였습니다.

## 회고

---

첫번째 프로젝트에서 부족했던 기초 단계를 탄탄히 다져서 시작을 했던 두번째 프로젝트였습니다. 4주간 팀원들과 매일매일 부족한 부분, 추가해야하는 부분을 회의를 통해 소통하였으며 기간을 정하여 그 기간 내에 기능을 완성할 수 있도록 노력했었습니다.

4주동안 팀원들과 작업하면서 서로 배려해주고, 응원해주면서 단 한번의 트러블 없이 프로젝트를 완성할 수 있었습니다. 비록 구현하고자 했던 기능들을 전부 추가하지 못한게 아쉽고, 완성도가 높다고 하기엔 부족한 면이 없지 않지만, 개발에 있어서 의사소통이 정말 중요하다는 것을 깨달을 수 있었던 프로젝트였습니다.

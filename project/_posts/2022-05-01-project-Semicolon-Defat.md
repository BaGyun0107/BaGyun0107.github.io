---
layout: post
title: Semicolon-Defat
description: >
  22.05 - 22.05 (2주)  
  1인 가구를 위한 다이어트 도시락 추천 서비스
sitemap: false
hide_last_modified: true
---

**GitHub :** <https://github.com/codestates/Defat>  
**배포링크 :** <https://www.semicolon-defat.com/>

<div class="slider" align="center">
    <div><img src= "/assets/img/defat/defat1.png" style="width: auto; height: 400px;"></div>
    <div><img src= "/assets/img/defat/defat2.png" style="width: auto; height: 400px;"></div>
    <div><img src= "/assets/img/defat/defat3.png" style="width: auto; height: 400px;"></div>
    <div><img src= "/assets/img/defat/defat4.png" style="width: auto; height: 400px;"></div>
    <div><img src= "/assets/img/defat/defat6.png" style="width: auto; height: 400px;"></div>
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
  - 프로젝트 기획 의도 및 아이디어 제시
- HTTPS 배포
  - AWS를 이용한 HTTPS 배포
- 검색필터링 구현
  - query문 작성하여 띄어쓰기 구분제거를 통한 검색 구현
- CRUD 작성
  - JWT로 쿠키를 사용한 로그인 방식 구현

## 서비스 기획 의도

---

Defat은 식단 관리 보조 서비스입니다. 1인 가구가 점점 늘어나는 추세로, 간단하게 먹을 수 있는 다이어트 식단을 추천해주고 사용자가 먹은 식단을 기록해주는 서비스를 제공하여 식단 관리에 도움을 주고자 기획한 프로젝트입니다.  
협업을 하기 위한 툴(Figma, Miro)을 익힐 수 있었습니다.

## 회고

---

개발 공부를 접하고서 첫 팀 프로젝트였습니다. 2주의 기간이 주어진 프로젝트로였지만, 처음 시작할 때 미리 구상해둔 것도 없었던 터라 기획 단계에서부터 시간이 오래 걸리는 바람에 기능과 홈페이지 구현의 미흡한 점이 많았습니다.

하나의 프로젝트를 만들기 위해서는 무슨 의도로 만드는지에 대한 방향성과 한 페이지에 어떤 기능들을 어떻게 구현할 것이며, REST API를 어떻게 구상할지 확실히 다져야 시작을 할 수 있다는 것을 깨달을 수 있는 프로젝트였습니다.

그래도 AWS를 통한 배포, 검색 필터링, 기본적인 CRUD 기능들을 추가하며 앞으로 기능을 추가하는 데 있어서 이 기능을 추가할 때의 기간, 시간을 얼마나 할애해야 하는지 등을 배울 수 있었습니다.

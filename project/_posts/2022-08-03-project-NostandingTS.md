---
layout: post
title: NostandingTS
description: >
  22.08 - 22.09  
  Semicolon-Nostanding TypeScript 리빌딩
sitemap: false
hide_last_modified: true
---

**GitHub :** <https://github.com/BaGyun0107/NostandingTS>

**Stack :** `TypeScript` `NodeJS` `Sequelize` `React` `Express` `MySQL`

- 백엔드폴더 JavaScript에서 TypeScript로 리빌딩
- 코드 간결화 진행
  - Nextfunction을 활용한 에러핸들링 구축
- 코드 가독성을 개선하기 위해 JWT 인증 미들웨어 구축
- 페이지네이션 개선
  - 기존의 코드에서는 한번에 모든 데이터를 불러오는 방식에서 한 페이지당 12개의 데이터를 받아오게끔 구현

## 서비스 기획 의도

---

타입스크립트를 인터넷 강의를 통해 배웠으니 팀 프로젝트에서 진행했던 파일들을 모두 타입스크립트로 리빌딩을 하면서 직접 타입스크립트가 가져오는 장점과 단점 등을 직접 경험해보고자 시작하게 되었습니다.

## 회고

---

처음 써보는 타입스크립트인데 막상 리빌딩 하다보니 많은 오류를 만나게되서 꽤나 고전했습니다.  
그래도 오류 하나하나 고쳐나가면서 느낀점은 기존 작성되어있던 코드가 정상작동은 하지만, 코드를 반복적으로 적거나, 코드의 구성이 지저분하다는걸 느낄 수 있었습니다.

또한, 자바스크립트에서는 개발자에게 굉장히 자비로운 언어로써, 개발자의 의도와 다르게 실행되는 경우가 간혹 발생한다는 것을 깨달았고, 이런 오류를 타입스크립트는 미리 확인해서 잡아주는 등 안정성이 확실히 올라간다는 것을 체험할 수 있었습니다.

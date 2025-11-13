<img src="https://capsule-render.vercel.app/api?type=wave&color=auto&height=150&section=header&text=Byoungyoon&fontSize=90&animation=fadeIn" />

### 안녕하세요. 사용자 경험과 구조의 균형을 끊임없이 고민하는 <span style="color:orange">프론트엔드 개발자 이병윤</span>입니다.

- 연락처 : 010 5024 1910
- 이메일 : bur5698@naver.com

## :hammer: Technology Stacks

- Frontend : 

  <span><img src="https://img.shields.io/badge/React-61dafb?style=flat&logo=react&logoColor=white"/></span>
  <span><img src="https://img.shields.io/badge/Next.js-000000?style=flat&logo=next.js&logoColor=white"/></span>
  <span><img src="https://img.shields.io/badge/React_Native-61dafb?style=flat&logo=react&logoColor=white"/></span>
  <span><img src="https://img.shields.io/badge/Flutter-02569B?style=flat&logo=flutter&logoColor=white"/></span>

- Backend :

  <span><img alt="Node.js" src="https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white"/></span>
  <span><img alt="Express" src="https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white"/></span>
  <span><img alt="NestJS" src="https://img.shields.io/badge/NestJS-e0234e?style=flat&logo=nestjs&logoColor=white"/></span>
  <span><img alt="Firebase" src="https://img.shields.io/badge/Firebase-FFCA28?style=flat&logo=firebase&logoColor=black"/></span>
  <span><img alt="Firestore" src="https://img.shields.io/badge/Firestore-FFA000?style=flat&logo=google-cloud&logoColor=white"/></span>
  <span><img alt="MongoDB" src="https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white"/></span>
  <span><img alt="Docker" src="https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white"/></span>

- Communication :

  <span><img alt="Figma" src="https://img.shields.io/badge/Figma-F24E1E?style=flat&logo=figma&logoColor=white"/></span>
  <span><img alt="Notion" src="https://img.shields.io/badge/Notion-000000?style=flat&logo=notion&logoColor=white"/></span>
  <span><img alt="Slack" src="https://img.shields.io/badge/Slack-4A154B?style=flat&logo=slack&logoColor=white"/></span>
  <span><img alt="Discord" src="https://img.shields.io/badge/Discord-5865F2?style=flat&logo=discord&logoColor=white"/></span>
  <span><img alt="Google Meet" src="https://img.shields.io/badge/Google_Meet-00897B?style=flat&logo=google-meet&logoColor=white"/></span>
  <span><img alt="Zoom" src="https://img.shields.io/badge/Zoom-0B5CFF?style=flat&logo=zoom&logoColor=white"/></span>

---

### 🪞 Retrospective
[2025-11-12]
- Handler로 구조를 만들때 index에 area의 큰 틀을 두고 작업을 하면 편한것 같다.

[2025-11-04]
- Action / Handler 중심 구조에서 Area 중심 구조로 설계 감각이 확장되었다.
- Area 단위로 구역을 나누고, 그 안에 `_action`, `_handler`를 두어 UI 구조와 폴더 구조를 일치시켰다.
- 반복되는 설계 패턴을 Template으로 두었는데, 한 눈에 어디서 쓰는지 잘 보이지 않아서 `@owner`, `@usedBy`, `@purpose` 주석을 남겨 문맥을 보존하기로 했다.

[2025-11-03]
- store의 setter 반복을 자동화할 수 있을 것 같다.
- 다만, 자동화는 타입 안전성과 명시성을 해칠 수 있으니, slice 단위로 한정하자

[2025-10-31]
- 폴더 구조가 깊어질수록 import도 깊어져 어디서 파생된 것인지 확 알기가 어려웠다
- 핵심 폴더마자 index.ts를 두어 경로를 단축시키자


---

![](./profile-3d-contrib/profile-south-season-animate.svg)

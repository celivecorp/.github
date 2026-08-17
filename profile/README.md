<div align="center">

<img src="https://raw.githubusercontent.com/celivecorp/.github/main/profile/logo.png" width="88" alt="celive">

# celive

**콘텐츠가 파는 시대, 제조부터 판매까지 직접 합니다.**

셀리브 코퍼레이션이 만드는 웹 서비스가 여기 모입니다.

</div>

---

## 무엇이 있나요

| 저장소 | 무엇 | 주소 |
|---|---|---|
| [`celivecorp.com`](https://github.com/celivecorp/celivecorp.com) | 코퍼레이션 공식 사이트. 한국어·일본어·중국어·러시아어 | https://celivecorp.com |

앞으로 늘어날 것들도 같은 자리에 둡니다.

---

## 이름 짓는 규칙

**서비스가 있는 주소를 그대로 저장소 이름으로 씁니다.**

```
celivecorp/
├── celivecorp.com      코퍼레이션 사이트
├── celive.kr           (예정)
└── celivelab.com       (예정)
```

`web`, `homepage`, `frontend` 같은 이름은 쓰지 않습니다. 사이트가 두 개를 넘어가는 순간 어느 것이 어느 사이트인지 알 수 없게 되기 때문입니다. 주소를 이름으로 쓰면 저장소 목록이 곧 서비스 목록이 됩니다.

사이트가 아닌 것(도구·라이브러리·문서)은 하는 일로 짓습니다 — `brand-assets`, `sheet-webhook` 처럼.

---

## 공통으로 지키는 것

**비밀값은 저장소에 넣지 않습니다.**
API 키·토큰·인증서는 배포 환경의 환경변수에만 둡니다. `.env` 는 항상 `.gitignore` 에 있고, 예시는 `.env.example` 로만 남깁니다. 인수인계 문서·메신저에도 실제 값을 적지 않습니다. 전달은 비밀번호 관리자로 합니다.

**빌드가 스스로 검사하게 만듭니다.**
사람이 매번 눈으로 확인해야 하는 일은 언젠가 반드시 빠집니다. 번역 누락, 폰트에서 빠진 글자, 깨진 링크, 빠진 메타태그 — 이런 것들은 빌드 단계에서 걸러지고, 걸리면 빌드를 멈춥니다.

**자바스크립트가 꺼져도 내용은 보입니다.**
목록·필터·탭 같은 것들은 서버에서 이미 다 그려 보내고, 자바스크립트는 거들기만 합니다. 검색엔진과 느린 회선을 위한 것이기도 합니다.

**한국어로 씁니다.**
주석·커밋 메시지·문서 모두 한국어입니다. 코드를 읽는 사람이 한국어를 쓰기 때문입니다.

---

## 브랜드

| | |
|---|---|
| 핫핑크 | `#FF2D87` — 로고·CTA·큰 숫자 |
| 핫핑크(작은 글자용) | `#D6006B` — 14px 급 라벨. 흰 배경 대비 5.2:1 |
| 먹색 | `#141014` |

로고 원본은 [`celivecorp.com/public/logo/`](https://github.com/celivecorp/celivecorp.com/tree/main/public/logo) 에 1:1 정사각 다섯 종으로 있습니다.

---

<div align="center">
<sub>문의 — <a href="https://celivecorp.com/#contact">celivecorp.com</a></sub>
</div>

```
{
  "task": "웹사이트 생성",
  "output_file": "docs/02_publishings.createsite.html",
  "requirements": {
    "title": "프로덕션 가이드라인 웹페이지 생성",
    "description": "20년차 연출감독이 클라이언트에게 보여주기 위한 프로덕션 소개 및 영상 제작 가이드라인 페이지를 생성한다. 모든 기능은 한 HTML 내부에서 작동하는 형태로 제작하며, 버튼 클릭 시 섹션이 열리고 닫히는 아코디언 방식으로 구성한다. 관리자 페이지 기능(CRUD)도 같은 HTML 안에서 탭 또는 토글 방식으로 이동할 수 있게 제작한다.",
    "single_file_mode": true,
    "features": [
      "장르별 기본 예산 — CRUD 가능",
      "포트폴리오 — 유튜브 영상 임베드, CRUD 가능",
      "AI 제작 가이드라인 — CRUD 가능 (AI 물리엔진 한계, 선정적 장면 불가 등 포함)",
      "자체적으로 사용 가능한 영상 AI 툴 목록 [RunwayML(gen-4), Midjourney, Flow(veo3.1)] — CRUD 가능",
      "고객센터 안내 — CRUD 가능",
      "다크모드 / 라이트모드 전환",
      "각 메뉴는 버튼을 눌렀을 때 설명이 펼쳐지는 아코디언 방식",
      "로컬스토리지(LocalStorage) 기반 데이터 저장",
      "관리자 기능은 페이지 내부의 별도 탭에서 운영",
      "반응형 디자인"
    ],
    "persona": {
      "role": "프로덕션 대표이자 20년차 연출감독",
      "goals": [
        "클라이언트에게 현실적인 예산/기획/촬영/후반작업 가이드를 설명",
        "AI 사용의 한계와 불가능한 것들을 명확히 안내",
        "애매한 표현을 구체적인 요구사항으로 정리한 문서를 제공"
      ],
      "pain_points": [
        "클라이언트가 영상 제작의 기본을 모름",
        "예산 대비 과도한 요구 반복",
        "AI가 못하는 장면을 AI로 요구"
      ]
    },
    "contact_info": {
      "대표자": "빵후",
      "전화번호": "01012341234",
      "이메일": "dudgn7715@gmail.com"
    },
    "menus": [
      "장르별 기본적 예산",
      "포트폴리오",
      "AI 제작 가이드라인",
      "자체 AI Tool 목록",
      "고객센터",
      "관리자 페이지"
    ],
    "admin_crud_fields": [
      "genreBudget",
      "portfolio",
      "aiGuide",
      "aiTools",
      "customerCenter"
    ],
    "output_format": "HTML 단일 파일",
    "instructions": [
      "파일 전체는 하나의 HTML 내부에 CSS/JS 포함",
      "CRUD 기능은 JavaScript로 구현",
      "UI는 Bootstrap 또는 Tailwind 없이 순수 CSS 또는 CSS 포함형으로 구성",
      "다크모드 전환은 body.classList.toggle 방식 사용"
    ]
  }
}
```
{
  "instruction": "이 요청은 완결된 형태다. 추가 topic이나 주제 요청을 하지 말고 즉시 HTML을 생성해라. 주제는 이미 '카메라 소개 페이지'로 확정되어 있다.",
  "output_format": "html",
  "filename": "study_vibecoding/codes/camera.html",
  "requirements": {
    "description": "카메라 소개용 랜딩 페이지 HTML을 생성한다.",
    "no_additional_questions": true,
    "sections": [
      {
        "title": "최신 카메라 소개",
        "type": "text",
        "content": "현재 출시된 최신 미러리스 카메라의 특징과 장점 설명"
      },
      {
        "title": "카메라 이미지",
        "type": "image",
        "source": "https://images.unsplash.com/photo-1519183071298-a2962be96c85?q=80&w=1200"
      },
      {
        "title": "카메라 종류",
        "type": "list",
        "items": ["DSLR", "미러리스", "컴팩트 카메라", "액션 카메라"]
      },
      {
        "title": "촬영 기초 팁",
        "type": "text",
        "content": "노출, 셔터스피드, 조리개, ISO 기본 개념 간단 설명"
      }
    ],
    "features": {
      "dark_mode_toggle": true,
      "bootstrap": true
    }
  },
  "rules": {
    "no_topic_request": true,
    "no_additional_input": true,
    "output_only_html": true
  }
}

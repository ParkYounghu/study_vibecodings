## prompt

```
{
  "task": "create_website",
  "tech_stack": ["HTML", "Bootstrap5"],
  "output": "study_vibecodings/codes/shotdocs.html",
  "style_reference": "ShotDeck 스타일의 시네마틱하고 미니멀한 UI",
  "description": "카메라 앵글을 아카이브 형태로 설명하는 웹사이트. ShotDeck 스타일을 참고한 다크톤 UI. Hero 섹션과 앵글별 카드 그리드 구성.",
  "sections": [
    {
      "name": "hero_section",
      "content": {
        "title": "Camera Angle Archive",
        "subtitle": "Learn cinematic framing inspired by ShotDeck",
        "background": "dark"
      }
    },
    {
      "name": "angle_cards",
      "type": "grid",
      "items": [
        {
          "angle": "High Angle",
          "description": "카메라가 위에서 아래를 내려다보는 구도. 피사체를 약하게 보이게 만든다.",
          "image": "https://images.unsplash.com/photo-1500530855697-b586d89ba3ee?auto=format&fit=crop&w=800&q=80"
        },
        {
          "angle": "Low Angle",
          "description": "카메라가 아래에서 위를 바라보는 구도. 피사체를 강하게 보이게 한다.",
          "image": "https://images.unsplash.com/photo-1497032628192-86f99bcd76bc?auto=format&fit=crop&w=800&q=80"
        },
        {
          "angle": "Dutch Angle",
          "description": "카메라를 좌우로 기울여 불안함, 긴장감을 표현한다.",
          "image": "https://images.unsplash.com/photo-1501785888041-af3ef285b470?auto=format&fit=crop&w=800&q=80"
        }
      ]
    }
  ],
  "design_guidelines": {
    "colors": "dark theme with strong contrast",
    "layout": "container + grid",
    "font": "Bootstrap default"
  }
}
```


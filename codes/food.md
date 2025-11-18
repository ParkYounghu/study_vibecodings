{
  "instruction": "이 요청은 완결된 형태다. 추가 topic이나 주제 요청을 하지 말고 즉시 HTML을 생성해라. 주제는 이미 'Food Mark - 혼밥 레시피 소개 페이지'로 확정되어 있다.",
  "output_format": "html",
  "filename": "codes/food.html",
  "requirements": {
    "description": "혼밥족을 위한 간편 레시피 랜딩 페이지. 카드 버튼 클릭 시 이미지와 상세 조리 단계가 나타나는 인터랙티브 형태로 생성.",
    "no_additional_questions": true,
    "sections": [
      {
        "title": "Header 및 레시피 검색",
        "type": "search",
        "content": "페이지 상단에 검색 입력 칸과 검색 버튼 포함. 사용자가 텍스트를 입력할 수 있는 칸과 오른쪽에 '검색' 버튼 위치."
      },
      {
        "title": "Food Mark – 혼밥 레시피 소개",
        "type": "text",
        "content": "1인 가구를 위한 쉽고 빠르고 맛있는 레시피 소개. 카드 클릭 시 이미지와 레시피 단계가 나타나는 인터랙티브 형태."
      },
      {
        "title": "인기 레시피 카드",
        "type": "interactive_cards",
        "items": [
          {
            "name": "돼지고기 김치찌개",
            "recipe": [
              "재료: 돼지고기 200g, 김치 200g, 두부 1/2모, 파 약간, 물 500ml, 고춧가루 1큰술, 간장 1큰술",
              "1) 돼지고기는 먹기 좋은 크기로 썰고, 김치는 먹기 좋게 자른다.",
              "2) 냄비에 돼지고기를 볶다가 김치를 넣고 3분 정도 더 볶는다.",
              "3) 물과 고춧가루, 간장을 넣고 끓인다.",
              "4) 두부와 파를 넣고 5~7분 더 끓이면 완성."
            ],
            "image": "https://images.unsplash.com/photo-1519183071298-a2962be96c85?q=80&w=1200"
          },
          {
            "name": "간장 계란밥",
            "recipe": [
              "재료: 밥 1공기, 계란 1개, 간장 1큰술, 참기름 1작은술, 쪽파 약간",
              "1) 계란을 프라이 또는 스크램블로 조리한다.",
              "2) 밥 위에 계란을 올리고 간장, 참기름을 뿌린다.",
              "3) 쪽파를 송송 썰어 올리고 잘 섞어 먹는다."
            ],
            "image": "https://images.unsplash.com/photo-0kThMylLsbY?q=80&w=1200"
          },
          {
            "name": "알리오 올리오",
            "recipe": [
              "재료: 스파게티 100g, 올리브 오일 2큰술, 마늘 3쪽, 페퍼론치노 약간, 파슬리 약간",
              "1) 스파게티를 소금물에 삶는다.",
              "2) 팬에 올리브오일과 다진 마늘, 페퍼론치노를 볶는다.",
              "3) 삶은 스파게티를 넣고 섞은 후 파슬리를 뿌려 완성."
            ],
            "image": "https://images.unsplash.com/photo-1525755662778-989d0524087e?q=80&w=1200"
          },
          {
            "name": "야채비빔밥",
            "recipe": [
              "재료: 밥 1공기, 나물 여러가지, 고추장 1큰술, 참기름 1작은술",
              "1) 나물은 각각 데치거나 볶아 준비한다.",
              "2) 밥 위에 나물과 고추장을 올린다.",
              "3) 참기름을 뿌리고 비벼서 먹는다."
            ],
            "image": "https://images.unsplash.com/photo-1402131186566-1e4c56ddda91?q=80&w=1200"
          },
          {
            "name": "연어구이 & 샐러드",
            "recipe": [
              "재료: 연어 150g, 소금·후추, 샐러드 채소",
              "1) 연어에 소금과 후추로 간을 한다.",
              "2) 팬 또는 오븐에 구워준다.",
              "3) 샐러드 채소와 함께 플레이팅한다."
            ],
            "image": "https://images.unsplash.com/photo-1490645935967-10de6ba17061?q=80&w=1200"
          },
          {
            "name": "버터갈릭 감자구이",
            "recipe": [
              "재료: 감자 2개, 버터 1큰술, 마늘 2쪽, 허브 약간",
              "1) 감자를 큼직하게 썰어 준비한다.",
              "2) 팬에 버터와 마늘을 넣고 볶는다.",
              "3) 감자를 넣고 허브와 함께 구워 완성."
            ],
            "image": "https://images.unsplash.com/photo-1467003909585-2f8a72700288?q=80&w=1200"
          },
          {
            "name": "토마토달걀볶음밥",
            "recipe": [
              "재료: 밥 1공기, 계란 1개, 토마토 1개, 마늘 1쪽, 소금·후추 약간",
              "1) 팬에 마늘을 볶고 토마토를 넣는다.",
              "2) 밥과 계란을 넣고 빠르게 볶는다.",
              "3) 소금·후추로 간을 맞춘 후 완성."
            ],
            "image": "https://images.unsplash.com/photo-1478145046317-39f10e56b5e9?q=80&w=1200"
          }
        ]
      },
      {
        "title": "요리 기본 팁",
        "type": "text",
        "content": "기본 양념 조합, 재료 손질 팁, 빠르게 맛을 내는 조리법 등을 간단히 설명한다."
      }
    ],
    "features": {
      "dark_mode_toggle": true,
      "bootstrap": true,
      "interactive_image_on_click": true
    }
  },
  "rules": {
    "no_topic_request": true,
    "no_additional_input": true,
    "output_only_html": true
  }
}

# Grape-datas

## 데이터 형식
```json
{
  "name": "사이트 이름",
  "url": "유저 매핑 형식 URL",
  "user_not_found" : "유저를 찾을 수 없을때의 html 문구",
  "category": "사이트 카테고리"

} ...
```

## 예시 데이터
```json
 {
    "name": "깃허브",
    "url": "https://github.com/{}",
    "user_not_found": "Find code, projects, and people on GitHub:",
    "category": "개발"
  },
  {
    "name": "나무위키",
    "url": "https://namu.wiki/w/사용자:{}",
    "user_not_found": "해당 문서를 찾을 수 없습니다.",
    "category": "정보"
  },
  {
    "name": "네이버",
    "url": "blog.naver.com/{}",
    "user_not_found": "죄송합니다. 유효하지 않은 요청입니다.",
    "category": "포털"
  },
  {
    "name": "네이트판",
    "url": "https://pann.nate.com/search?searchType=N&q={}",
    "user_not_found": "에 대한 검색결과가 없습니다.",
    "category": "커뮤니티"
  },
  {
    "name": "다음 카페",
    "url": "https://m.cafe.daum.net/{}",
    "user_not_found": "페이지 사용 권한이 없습니다.",
    "category": "커뮤니티"
  },
```

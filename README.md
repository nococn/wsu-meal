# 🍱 우송대 학식

우송대학교 학생식당·기숙사 식단을 날짜별로 보는 웹 페이지입니다. 로그인 없이 바로 열립니다.

- 데이터: [wsu-meal-api](https://github.com/sangukjeon/wsu-meal-api) (학교 홈페이지 식단을 하루 네 번 JSON으로 저장)
- 빌드 없이 HTML·CSS·자바스크립트 파일만으로 동작하고, GitHub Pages로 배포합니다.

## 기능

- 이번 주 날짜를 요일·날짜로 골라 보기 (오늘이 기본)
- 식당 탭 (학교 홈페이지 순서), 마지막으로 본 식당 기억
- 주메뉴는 크게, 나머지 반찬은 작은 알약으로
- 오늘 기숙사 식당은 지금 시간에 맞는 끼니(조식·중식·석식)에 "지금" 표시
- 다크 모드

## 로컬에서 보기

```bash
python -m http.server 4321
```

브라우저에서 `http://localhost:4321`을 엽니다.

## 배포

**Settings → Pages**에서 `Deploy from a branch`, 브랜치 `main`, 폴더 `/ (root)`를 고릅니다.

---

<sub>우송대학교의 공식 서비스가 아닙니다. 식단 출처는 [우송대학교 홈페이지 학생식당 안내](https://www.wsu.ac.kr/page/index.jsp?code=campus0806)이며, 실제 제공 메뉴와 다를 수 있습니다.</sub>

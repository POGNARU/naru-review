# 모닝페이지 회고 리포트

포근나루(POGNARU STUDIO) 운영자 햇살의 모닝페이지 월별 회고 아카이브입니다.  
새벽에 쓴 글들을 모아, 달마다 가만히 돌아봅니다.

🔗 **[회고 리포트 보기](https://pognaru.github.io/morning_pages_analysis/)**

---

## 파일 구조

```
index.html                  # 회고 리포트 목록 페이지
2026-04-05-review.html      # 4·5월 모닝페이지 회고
2026-05-review.html         # 5월 회고
2026-06-01-11-review.html   # 6월 1~11일 회고
2026-06-20-week-review.html # 6월 셋째 주 회고
```

---

## 회고 리포트 추가하는 법

### 1. 새 회고 HTML 파일 작성
`YYYY-MM-review.html` 형식으로 파일을 만듭니다.  
두 달치를 묶을 경우 `YYYY-MM-MM-review.html`로 합니다.  
(예: `2026-05-review.html` / `2026-04-05-review.html`)

### 2. index.html에 카드 추가
`index.html` 안의 해당 월 `.month-block`에 아래 카드를 복사해 붙입니다.

```html
<a class="report-card" href="YYYY-MM-review.html">
  <div class="date-mark">
    <div class="date-day">DD</div>
    <div class="date-month">MON</div>
  </div>
  <div class="report-info">
    <div class="report-title">N월 모닝페이지 회고</div>
    <div class="report-desc">한 달간의 새벽 기록을 돌아본 리포트</div>
  </div>
  <div class="arrow">→</div>
</a>
```

새로운 달이면 `.month-block` 전체를 복사하고 `.month-label`의 연·월을 바꿉니다.

### 3. 커밋 & 푸시
```bash
git add .
git commit -m "N월 모닝페이지 회고 추가"
git push
```

---

## 브랜드 정보

| 항목 | 값 |
|------|----|
| 크림 | `#FDF4EE` |
| 살구 | `#F8E4D4` |
| 테라코타 | `#C8845A` |
| 다크브라운 | `#3C2415` |
| 로고 폰트 | Gowun Batang |
| 본문 폰트 | Nanum Myeongjo |

# 산책 커피 · Sanchaek Coffee

동네 골목의 작은 로스터리 카페를 위한 간단한 정적 랜딩페이지입니다.

![HTML](https://img.shields.io/badge/HTML5-e34f26?logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS3-1572b6?logo=css3&logoColor=white)

## 소개

빌드 도구나 프레임워크 없이 순수 HTML/CSS로만 만든 1페이지 사이트입니다.
따뜻한 브라운 톤에 반응형 레이아웃(모바일~데스크톱)을 적용했습니다.

## 구성

| 파일 | 설명 |
| --- | --- |
| `index.html` | 페이지 마크업 (히어로 / 대표 메뉴 / 소개 / 오시는 길) |
| `style.css` | 색상 변수, 반응형 그리드, 스티키 헤더 스타일 |
| `.gitignore` | OS·에디터 임시 파일 제외 |

## 섹션

- **Hero** — 카페 슬로건과 CTA 버튼
- **대표 메뉴** — 오늘의 드립 / 산책 라떼 / 흑임자 아인슈페너
- **작은 로스터리 이야기** — 브랜드 소개
- **오시는 길** — 주소·영업시간·전화

## 실행

별도 설치나 빌드가 필요 없습니다.

```bash
# 저장소 클론 후
git clone https://github.com/hana8511-prog/cafe-landing.git
cd cafe-landing

# index.html 을 브라우저로 열기 (또는 로컬 서버)
python -m http.server 8000
# → http://localhost:8000
```

## 커스터마이징

- 색상: `style.css` 상단 `:root` 변수 수정
- 메뉴/문구: `index.html` 의 각 섹션 텍스트 수정

## 라이선스

개인 학습·예제용으로 자유롭게 사용하세요.

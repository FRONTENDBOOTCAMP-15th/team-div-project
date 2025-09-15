# Uber Project

FRONTENDBOOTCAMP-15th UI Practice

<br />

## Team Member

멋사 15기 회고 2조 팀 DIV 방범대 팀원들을 소개합니다.

<br />

## Team Rules

### Git & 협업 규칙

#### 커밋 메시지

- `feature:`, `fix:`, `docs:`, `style:`, ...
ex ) feature : header 추가

### 폴더·파일 네이밍

#### 파일 구조

```bash
/public
  /font
/src
  /assets
    /images
  /common # reset.css / a11y.css 등
  /css # 할당된 컴포넌트 작업 css / ex) header.css
  /html # 할당된 컴포넌트 작업 html / ex) header.html
  /style.css # 병합될 메인 css
/index.html # 병합될 메인 html
```

#### class 네이밍

- `kebab-case` 사용

### 코드 스타일(자동화)

- 포매터: Prettier

### 접근성 체크리스트

- 키보드만으로 모든 기능 사용 가능 (Tab 이동)
- 이미지 `alt` 사용 (필요없을 경우 사용 X)
- 시멘틱 마크업 우선 (필요시 ARIA 사용)
- 폼 레이블 연결

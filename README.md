# SASS Guide

> 이 프로젝트는 **Sass를 실제 프로젝트에서 테스트 할 수 있도록 세팅한 교육용 예제**입니다.

---

## 🗂️ 프로젝트 구조

```bash
sass-guide/
├── A-non-react-html/   # 순수 HTML 환경에서 Sass 사용 예제
└── B-react-vite/       # React + Vite 기반 Sass 사용 예제
```

### [A] non-react ver(html)

#### 개요

* Vanilla HTML + SCSS 환경
* VS Code 확장(Live Sass Compiler) 또는 Sass CLI를 통해 스타일 컴파일
* 기본적인 변수, 믹스인, 네스팅, 파일 분할 학습에 적합

#### 학습 포인트

* Sass 설치 없이 실습하는 방법
* @use / @import 차이 체험
* Partial 파일 관리 (\_variables.scss 등)

### [B] react-vite ver

#### 개요

* React + Vite + SCSS
* 글로벌 SCSS 구조 학습

#### 학습 포인트

* @use, @forward를 통한 모듈화 스타일 설계
* main.scss를 통한 전역 스타일 관리
* Vite 환경에서 sass 및 sass-embedded 설정
  
---

## 🧠 Sass 학습 키워드

기능 설명
* $변수명 색상, 폰트, 여백 등을 변수화하여 재사용성 향상
* @mixin 반복되는 스타일 블록화 + 매개변수로 동적 스타일 적용
* @use / @forward 모듈화된 스타일 시스템 구현
* @if, @for 조건 분기 및 유틸리티 클래스 자동 생성 등 로직 기반 스타일
* Partial 파일 \_파일명.scss으로 정의하여 개별 CSS로 컴파일되지 않도록 설정
  
---

## 🚀 실행 방법

### A 폴더 (npm 없이 Sass CLI 사용)

bash
* sass src/scss/main.scss dist/main.css --watch
* 또는 VS Code → Live Sass Compiler 확장 사용

### B 폴더 (React + Vite)

bash
* npm install
* npm run dev
* 버전에 따라 sass나 sass-embedded 중 하나 설치:  npm install -D sass (sass-embedded)
  
---

## 📌 참고

### Sass 공식 문서: https://sass-lang.com/

이 프로젝트는 교육 및 포트폴리오 실습용으로 제작되었습니다

---

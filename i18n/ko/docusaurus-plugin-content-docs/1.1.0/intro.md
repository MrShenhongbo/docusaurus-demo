---
sidebar_position: 1
---

# 튜토리얼 소개

5분 안에 도쿠사우루스를 발견합시다.

## 시작하기

**새 사이트 만들기** 로 시작하세요.

Or **try Docusaurus immediately** with **[docusaurus.new](https://docusaurus.new)**.

### 필요한 것

- [Node.js](https://nodejs.org/en/download/) version 16.14 or above:
  - Node.js를 설치할 때 종속성과 관련된 모든 확인란을 선택하는 것이 좋습니다.

## 새 사이트 생성

**classic 템플릿**을 사용하여 새 Docusaurus 사이트를 생성합니다.

다음 명령을 실행하면 클래식 템플릿이 프로젝트에 자동으로 추가됩니다.

```bash
npm init docusaurus@latest my-website classic
```

명령 프롬프트, Powershell, 터미널 또는 코드 편집기의 기타 통합 터미널에 이 명령을 입력할 수 있습니다.

이 명령은 또한 Docusaurus를 실행하는 데 필요한 모든 종속성을 설치합니다.

## 사이트 시작

개발 서버를 실행합니다.

```bash
cd my-website
npm run start
```

The `cd` command changes the directory you're working with. In order to work with your newly created Docusaurus site, you'll need to navigate the terminal there.

The `npm run start` command builds your website locally and serves it through a development server, ready for you to view at http://localhost:3000/.

Open `docs/intro.md` (this page) and edit some lines: the site **reloads automatically** and displays your changes.

# 개인용 앱 안내

공개 사이트: https://xellos216.github.io/app-info/

## 문서 구조

```text
index.html                     앱 목록
assets/                        공통 스타일과 아이콘
rclone/
  index.html                   rclone 앱 소개
  privacy.html                 rclone 개인정보처리방침
creator-publishing-desk/
  index.html                   Creator-Publishing-Desk 앱 소개
  privacy.html                 Creator-Publishing-Desk 개인정보처리방침
  terms.html                   Creator-Publishing-Desk 이용약관
```

각 앱은 Google Cloud의 별도 앱 설정에 해당하는 소개와 정책을 유지합니다.
Google Cloud에는 앱 목록 주소가 아니라 해당 앱의 소개·정책 주소를 입력합니다.
공통 승인 도메인은 `xellos216.github.io`입니다. 이 사이트의 게시는 Google의
브랜드·권한 검증이나 YouTube API 준수 심사 승인을 의미하지 않습니다.

정적 HTML을 `main` 브랜치 루트에서 GitHub Pages로 게시합니다. 빌드 도구,
외부 JavaScript, 로그인, 분석 스크립트 또는 백엔드를 사용하지 않습니다.
내부 상대 링크·프래그먼트·canonical URL과 비밀정보 포함 여부를 확인한 뒤
배포하며, 실제 공개 HTTPS 응답을 최종 확인합니다.

## 이전 주소

기존 `xellos216/rclone-oauth-info` 저장소와 공개 페이지는 이미 등록된
Google Cloud 링크를 유지하기 위해 그대로 남아 있습니다. 최신 문서의
작성·갱신 대상은 이 `app-info` 저장소입니다. 기존 사이트를 제거하거나
다른 내용으로 교체하기 전에는 해당 앱의 Cloud URL 변경 완료를 확인합니다.

## 공개 범위

이 저장소에는 공개 앱 안내 문서와 표시 파일만 포함합니다. 인증 정보,
비공개 미디어·영상 링크, 계정 화면 원본, 업로드 실행 기록, 로컬 환경의
개인 경로를 추가하지 않습니다.

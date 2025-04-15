# Caring Note Keycloak Theme

이 저장소는 Caring Note 서비스에서 사용될 Keycloak 커스텀 테마를 개발하고 관리하기 위한 공간입니다.

## 테마 구조

`theme/caring-note` 디렉토리 내에 Keycloak 테마 관련 파일들을 구성합니다.

- `login`: 로그인 관련 페이지 테마
- `account`: 계정 관리 페이지 테마
- `email`: 이메일 템플릿 테마
- ... 기타 필요한 테마 타입

## 빌드 및 배포

`Dockerfile`을 사용하여 테마 파일을 포함하는 Docker 이미지를 빌드합니다.
GitHub Actions 워크플로우 (`.github/workflows/build.yml`) 를 통해 푸시 또는 풀 리퀘스트 시 자동으로 이미지를 빌드합니다. 
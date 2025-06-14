# Buildah 소개 (Intro to Buildah)

Buildah는 리눅스에서 컨테이너 이미지를 만들고 조작할 수 있게 해주는 오픈소스 CLI 도구입니다.  
Docker 없이도 OCI(Open Container Initiative) 호환 이미지를 생성할 수 있는 것이 특징입니다.

## 주요 특징

- 컨테이너를 생성하지 않고 이미지 생성 가능
- 스크립트 기반 빌드, Dockerfile 빌드 모두 지원
- Podman과 완전히 호환
- 루트리스(rootless) 환경에서도 실행 가능

## 설치 방법 (예: Ubuntu 기준)

```bash
sudo apt install buildah

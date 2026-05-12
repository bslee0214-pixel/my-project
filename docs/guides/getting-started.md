# MkDocs 시작하기

> MkDocs와 Material 테마를 사용해 기술 문서 사이트를 만드는 방법을 간단히 정리한 가이드입니다.

---

## 소개

MkDocs는 Markdown 기반의 정적 문서 사이트 생성기입니다.

특히 Material 테마를 사용하면 다음과 같은 기능을 쉽게 사용할 수 있습니다.

- 다크 모드
- 검색 기능
- 코드 하이라이팅
- 탭 네비게이션
- 반응형 UI

---

## 목차

1. MkDocs 설치
2. 프로젝트 생성
3. Material 테마 적용
4. 로컬 서버 실행
5. 빌드 및 배포

---

## 1. MkDocs 설치

```bash
pip install mkdocs-material
```

---

## 2. 프로젝트 생성

```bash
mkdocs new my-docs
cd my-docs
```

---

## 3. Material 테마 적용

`mkdocs.yml` 파일 수정:

```yaml
theme:
  name: material
```

---

## 4. 로컬 서버 실행

```bash
mkdocs serve
```

브라우저에서 아래 주소 접속:

```text
http://127.0.0.1:8000
```

---

## 5. 사이트 빌드

```bash
mkdocs build
```

빌드 결과는 `site/` 폴더에 생성됩니다.

---

## 마무리

MkDocs는 설정이 간단하고 Markdown 기반이라서
개인 기술 문서 관리에 매우 편리합니다.

작은 메모부터 시작해서 점점 문서를 확장해보세요.
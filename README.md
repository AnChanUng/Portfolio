# Portfolio — 안찬웅

비즈니스 관점에서의 문제를 기술로 풀어나가는 서버 개발자, 안찬웅의 포트폴리오 사이트입니다.

🔗 **https://anchanung.github.io/Portfolio/**

## 구성

```
index.html                  # 포트폴리오 단일 페이지
assets/css/style.css        # 스타일 (다크/라이트 테마 토큰)
assets/js/main.js           # 테마 토글, 스크롤 인터랙션, 카운트업, 라이트박스
assets/img/profile.png      # 프로필 사진
assets/img/project/         # 자율주행 플랫폼 아키텍처 도식 (원본 + 썸네일)
assets/resume_anchanung.pdf # 이력서 PDF (다운로드용)
```

## 특징

- 다크/라이트 테마 토글 (선택값 `localStorage` 저장, 최초 방문 시 OS 설정을 따름)
- 스크롤 진행 바 · 섹션 자동 하이라이트 · 등장 애니메이션 · 수치 카운트업
- 프로젝트 도식 갤러리 + 라이트박스 (ESC · 배경 클릭으로 닫기)
- 모바일 대응 반응형 레이아웃, `prefers-reduced-motion` 대응
- 빌드 도구 없는 정적 페이지 (프레임워크 의존성 없음)

## 로컬 실행

```bash
python -m http.server 8000
# http://localhost:8000
```

## 배포

GitHub Pages — Settings → Pages → Source: `Deploy from a branch` → `main` / `/ (root)`

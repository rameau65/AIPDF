# AI Character IP Development Framework (AIPDF)

AIPDF는 AI를 활용해 캐릭터 IP를 **기획·디자인·세계관·브랜드·상품화·라이선싱·투자·출판**까지 일관된 시스템으로 개발하기 위한 프레임워크입니다.

[English README](README.md) · [한국어 문서](docs/ko/index.md) · [English Docs](docs/en/index.md)

## Phase 1 — Framework Core

- GitHub 저장소 표준 구조
- MkDocs Material 기반 문서 사이트
- 국문·영문 문서 체계
- 핵심 `SKILL.md`
- 캐릭터, 세계관, 브랜드, 제품, 라이선싱, 퍼블리싱 핵심 문서
- GitHub Actions 문서 검수
- GitHub Pages 자동 배포

## 프레임워크 구성

1. **Character Core** — 캐릭터 DNA, 실루엣, 얼굴 일관성, 표정과 포즈
2. **World & Emotion** — Emotion Bloom™, 세계관, 관계, 스토리 루프
3. **Brand System** — 비주얼 언어, 컬러, 타이포그래피, 다이어그램
4. **Product System** — 아트토이, 패키지, 굿즈, 리테일, 전시
5. **Business System** — 라이선싱, 사업화, 투자 및 수익 구조
6. **Publishing System** — PPTX, PDF, DOCX 및 문서 배포

## 로컬 실행

```bash
python -m venv .venv
source .venv/bin/activate  # Windows: .venv\Scripts\activate
pip install -r requirements-docs.txt
mkdocs serve
```

브라우저에서 `http://127.0.0.1:8000`을 엽니다.

## 기준 IP

SINDAENG(신댕이)는 AIPDF의 최초 레퍼런스 구현입니다. 다른 캐릭터 IP에도 프로젝트 프로필만 교체해 동일한 단계와 품질 기준을 적용할 수 있습니다.

## 권리 안내

프레임워크 문서와 설정은 저장소 라이선스를 따릅니다. SINDAENG 캐릭터 이미지, 상표 및 전용 자산은 별도 명시가 없는 한 해당 권리자의 권리 범위에 포함됩니다.

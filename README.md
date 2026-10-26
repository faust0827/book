# 교정생활의 모든 것 — 가이드북 프로젝트

이 폴더는 교정생활 가이드북 원고와 수집 자료를 담습니다.

## 구조
- `outline.md`: 전체 목차
- `chapters/`: 본문 Markdown 원고 (Part 0~12)
- `sources/`: 법령·KPI·RSS·통계 수집 노트
- `appendices/`: 추후 부록 세부 파일
- `assets/`: 이미지·표 자료
- `교정통계연보/`: 통계연보 PDF 원본

## 작성 원칙
- 쉬운 말 + 근거 법령 + 체크리스트
- 공식 자료와 법령을 우선 근거로 사용
- 최신성 확인 필요: 2026.10.2 공소청 체계, 2026.12 수용자 자녀 지원 시행 등

## 다른 PC에서 이어하기

이 폴더는 Git 저장소로 초기화되어 있으며, `book.bundle` 파일로 옮길 수 있습니다.

새 PC에서 시작:
```bash
git clone book.bundle book
cd book
```

이후 변경사항을 다시 묶을 때:
```bash
git add -A
git commit -m "Update book"
git bundle create book.bundle --all
```

# AI Design Template Workspace

업체별 디자인 작업을 반복해서 진행할 수 있도록 만든 템플릿형 작업 폴더입니다.

## 구조

```txt
templates/
  henna-label/
    DESIGN.md
    README.md
    data-example.json

clients/
  dada/
    business-context.md
    design-brief.md
    data.json
    assets/
    output/

assets/
  shared/

output/
```

## 사용 방법

1. `templates/`에서 작업 종류에 맞는 공통 템플릿을 고릅니다.
2. `clients/<업체명>/`에 업체별 정보를 작성합니다.
3. 참고 이미지와 로고는 업체별 `assets/`에 넣습니다.
4. 완성 시안은 업체별 `output/`에 저장합니다.

현재 DADA 작업은 `clients/dada/`에 정리되어 있습니다.

## GitHub에 올리는 기준

- GitHub에는 문서, 템플릿, JSON 데이터, SVG처럼 가벼운 파일을 중심으로 올립니다.
- PNG/JPG 목업, 참고 이미지, 중간 시안, AI/PSD 같은 원본 대용량 파일은 기본적으로 GitHub에 올리지 않습니다.
- 업체별 큰 파일은 로컬 폴더나 클라우드 드라이브에 보관하고, 필요하면 문서에 위치나 링크만 적습니다.
- 클라이언트 공유용으로 꼭 필요한 작은 미리보기 이미지만 `clients/<업체명>/preview/`에 넣어 예외적으로 추적할 수 있습니다.

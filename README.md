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

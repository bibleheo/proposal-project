# proposal-project

블루티엔에스(BlueTNS) 제안서 통합 리포지토리. 기존에 개별 리포지토리로 흩어져 있던 제안서 프로젝트들을 하위 폴더로 통합했습니다.

## 🔗 통합 포털 (GitHub Pages)

메인 랜딩 페이지: `index.html` — 배포 후 `https://bibleheo.github.io/proposal-project/`

## 📁 구성

| 폴더 | 제안서 | 원본 리포지토리 |
|------|--------|------------------|
| [`zwcad-proposal/`](./zwcad-proposal/) | ZWCAD 제안서 | `bibleheo/zwcad-proposal` |
| [`zwcad365-proposal/`](./zwcad365-proposal/) | ZWCAD 365 | `bibleheo/zwcad365-proposal` |
| [`zyxcad-ax-proposal/`](./zyxcad-ax-proposal/) | ZYXCAD AX 제안서 | `bibleheo/zyxcad-ax-proposal` |
| [`ZWCAD-Video-Proposal/`](./ZWCAD-Video-Proposal/) | ZWCAD 영상 제안서 | `bibleheo/ZWCAD-Video-Proposal` |
| [`bts-proposal/`](./bts-proposal/) | 블루티엔에스 제안서 | `bibleheo/bts-proposal` |

각 폴더는 원본 리포지토리의 `index.html`을 진입점으로 그대로 유지합니다.

## 🚀 배포

`main` 브랜치에 푸시하면 `.github/workflows/pages.yml` 워크플로가 저장소 루트 전체를 GitHub Pages로 배포합니다.
- 랜딩 페이지: `/`
- 각 제안서: `/<폴더명>/`

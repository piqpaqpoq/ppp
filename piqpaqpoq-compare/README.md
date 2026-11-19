# 픽팩폭 한눈비교

기존 픽팩폭과 별도로 배포하는 정적 비교 사이트입니다.

- `index.html`은 비교 목록입니다.
- `compare/cu-woni-lunchbox/index.html`은 첫 비교 글입니다.
- `assets/site.css`는 기존 픽팩폭의 색상값과 카드 스타일을 바탕으로 정리한 공통 스타일입니다.
- 상품 가격과 구성은 기존 공개 사이트의 상품 613과 BGF 보도자료를 바탕으로 옮겼습니다. 사진은 BGF 공식 원문이 제공하는 URL을 사용합니다.

## 배포

새 GitHub 저장소 이름 예시 `piqpaqpoq-compare`

이 폴더 안의 파일과 폴더를 새 저장소의 루트에 올리세요. GitHub의 Settings → Pages에서 Deploy from a branch를 선택하고, 기본 브랜치의 `/ (root)`를 저장하세요. 배포가 완료되면 GitHub가 표시하는 사이트 주소에서 홈과 첫 비교 글을 열 수 있습니다.

## 로컬 확인

이 폴더에서 `python3 -m http.server 8000`을 실행한 뒤 브라우저에서 `http://localhost:8000`을 여세요.

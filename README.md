# 황윤철 팀장 영업 관리 대시보드 — 웹 공개용

이 폴더의 `index.html` **한 파일**만 있으면 GitHub Pages로 링크를 만들 수 있습니다.
(HTML·CSS·데이터가 모두 한 파일에 들어 있습니다.)

## GitHub에 올려서 링크 만들기 (약 5분)

1. [github.com](https://github.com) 로그인 → 오른쪽 위 **+** → **New repository**
2. Repository name: `sales-dashboard` (원하는 이름)
   - 공개 링크로 쓰려면 **Public** 선택
   - **Create repository**
3. 생성된 저장소에서 **uploading an existing file** 클릭
4. `index.html`, `README.md` 두 파일을 끌어다 놓고 **Commit changes**
5. 저장소 상단 **Settings** → 왼쪽 **Pages**
6. **Source**: `Deploy from a branch` / **Branch**: `main` + `/ (root)` → **Save**
7. 1~2분 뒤 아래 주소가 열립니다:
   `https://<내 GitHub 아이디>.github.io/sales-dashboard/`

주소를 카카오톡·문자로 보내면 누구나 열람할 수 있습니다(모바일 화면 대응).

## 꼭 알아두세요

- 이 페이지는 **읽기 전용 미리보기**입니다. 업체 추가·진행 기록·자료 업로드 같은 입력/저장은
  AgentBase 대시보드(원본)에서 하세요.
- 데이터는 **이 파일을 만들 시점의 스냅샷**입니다. 이후 입력한 내용은 자동 반영되지 않습니다.
  최신으로 바꾸려면 새로 만든 `index.html`로 교체(업로드)하면 됩니다.
- **실제 고객 정보(업체명·연락처·계약금액)가 들어간 파일을 Public 저장소에 올리면 누구나 볼 수 있습니다.**
  실데이터가 들어간 뒤에는 Private 저장소 + 별도 호스팅을 권장합니다.
- 사내 공유용으로는 AgentBase 대시보드의 공유 기능을 쓰는 편이 안전합니다(항상 최신 데이터).

# 봉산 걷기 기록

폰에서 GPS로 걷는 길을 기록하고 보여주는 단일 HTML 웹앱입니다. (Claude 채팅에서 만든 아티팩트를 가져온 초기 버전)

- 원본 아티팩트: https://claude.ai/artifact/H4nBt8fAZySoC1q5U2VtK5
- 파일: `index.html` (외부 의존성 없음, 브라우저에서 바로 열기)

## 현재 기능
- 걷기 시작/멈춤, 거리·시간·기록한 점 표시, 지나간 길 캔버스 그리기
- 내 위치 보기, 구글 지도/카카오맵 열기
- 길 저장·보기·삭제 (브라우저 localStorage, 기기별 저장)

## 다음 작업 후보
- [x] 실제 지도(OpenStreetMap 타일) 위에 경로 표시 (구현됨, 실기기 확인 필요)
- [ ] 봉산 코스(출발점, 구간, 전망대 등) 안내
- [ ] 저장한 길을 다른 기기에서도 보기 (내보내기/가져오기 GPX 또는 서버 저장)
- [ ] 걷기 중 화면 꺼짐 방지, 정확도 필터 개선
- [ ] GitHub Pages로 배포해 폰에서 바로 접속

## 폰에 설치해서 쓰기 (GitHub Pages)
1. GitHub 저장소 Settings → Pages → Branch를 `claude/exciting-davinci-c0s3k5`, 폴더 `/ (root)`로 선택 후 Save
   (무료 계정은 저장소가 공개(public)여야 Pages를 쓸 수 있어요)
2. 1~2분 뒤 `https://hwan2go.github.io/bongsan-walk/` 주소가 생겨요
3. 폰 Chrome/Safari에서 그 주소를 열고 위치 허용 → "홈 화면에 추가"

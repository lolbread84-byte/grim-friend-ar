# 그림친구 AR

학생이 그린 그림을 사진으로 찍으면 배경을 지우고 통통한 3D 캐릭터로 바꿔,
스마트폰 카메라 화면(AR)에 띄워 같이 사진을 찍는 웹앱입니다.

👉 **바로 쓰기: https://lolbread84-byte.github.io/grim-friend-ar/**

- 파일 하나(`index.html`)로 동작, 설치 불필요
- 사진은 기기 안에서만 처리 (서버 전송 없음)
- 카메라는 `https://` 주소에서만 켜짐 → Netlify Drop, GitHub Pages 등에 올려서 사용

## 로컬 실행
```bash
npx http-server -p 8765
```

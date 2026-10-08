# money-app

금전관리 자동화 시스템(Google Apps Script, light4u.kr 워크스페이스 전용)을 iframe으로 감싸서, 브라우저 주소창에는 계속 이 깔끔한 깃허브 주소만 보이도록 하는 페이지.

- access가 DOMAIN(워크스페이스 제한)이라, light4u.kr 계정으로 로그인되어 있어야 내용이 보입니다. 로그인이 안 되어 있으면 화면이 비어 보일 수 있고, 이 경우 페이지 하단에 나오는 "직접 접속하기" 링크를 눌러 로그인 후 이용하면 됩니다.
- 실제 앱 배포 주소가 바뀌면 `index.html` 안의 `AKfycb...`로 시작하는 주소 2곳(iframe `src`, fallback 링크)을 새 주소로 바꿔서 다시 커밋하면 됩니다. (DOMAIN 방식이라 `/a/macros/light4u.kr/s/{배포ID}/exec` 형식을 유지해야 함)

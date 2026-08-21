CIST 갤럭시탭 음성인식 v4 - GitHub Pages 업로드용

v4 핵심 수정:
- v3의 JavaScript 문법 오류 수정 (await 함수 선언)
- 1분 시작 버튼에서 마이크 권한 요청을 완전히 제거
- 마이크 테스트에서 권한을 먼저 받고, 1분 시작은 SpeechRecognition.start()만 직접 실행
- 음성인식 종료 시 1분 동안 자동 재시작
- 상태/오류 메시지 표시

업로드:
GitHub 저장소 root의 기존 index.html을 이 index.html로 교체하세요.
manifest.webmanifest도 교체하세요.
README.txt는 선택 사항입니다.

테스트:
1. HTTPS GitHub Pages + Chrome
2. 🎤 마이크 테스트 → 🟢 마이크 정상
3. ▶ 1분 시작을 한 번 누름
4. "사과"라고 말함

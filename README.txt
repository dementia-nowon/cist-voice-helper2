CIST 갤럭시탭 음성인식 v6

중요:
- 기존 CIST 전체 페이지/문항/디자인을 그대로 유지한 상태에서 음성인식 부분만 수정했습니다.
- 마이크 테스트 후 마이크 스트림을 8초 뒤 종료하던 코드를 제거했습니다.
- 1분 시작 버튼에서는 마이크 권한을 다시 요청하지 않고 SpeechRecognition.start()를 직접 호출합니다.
- 음성인식 오류 코드를 화면에 표시합니다.
- GitHub Pages root에 index.html을 교체 업로드하세요.
- manifest.webmanifest도 교체하세요.

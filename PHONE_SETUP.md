# 휴대폰만으로 APK 만들기
1. GitHub에서 새 빈 저장소를 만들거나 기존 저장소의 Codespaces를 엽니다.
2. Codespaces 터미널에 이 ZIP을 업로드한 후 `unzip GameLounge_APK_GitHubActions.zip`으로 압축을 풉니다.
3. 프로젝트 파일을 저장소 최상위에 두고 `git add . && git commit -m "Add Android APK build" && git push` 실행.
4. GitHub 저장소 Actions > Build Android APK > Run workflow.
5. 성공하면 해당 실행의 Artifacts에서 GameLounge-debug-apk 다운로드.
참고: 기존 게임 사이트 저장소의 파일을 덮어쓰지 않도록 새 저장소를 권장합니다.

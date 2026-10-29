# 게임라운지 안드로이드 앱 (WebView)

사이트: https://friend-omok-v13-7-2-ios-native-clic.vercel.app/

## APK 만들기
1. PC에서 Android Studio 설치 (JDK 17 권장).
2. `GameLoungeAndroid` 폴더를 **Open**으로 열기.
3. Gradle Sync 완료 기다리기 (인터넷 필요).
4. **Build > Build Bundle(s) / APK(s) > Build APK(s)** 선택.
5. `app/build/outputs/apk/debug/app-debug.apk` 파일을 안드로이드 기기에 설치.

## 업데이트
사이트의 HTML을 Vercel에 재배포하면 앱은 다음 새로고침/재실행 시 변경 내용을 받습니다. 웹 캐시가 남으면 조금 늦을 수 있습니다.

## 참고
- 이 ZIP은 **Android Studio 소스 프로젝트**이며 APK가 아닙니다.
- 실제 빌드 및 기기 테스트는 수행하지 않았습니다.
- 웹사이트에 존재하는 Firebase/게임 버그는 이 앱이 자동으로 해결하지 않습니다.
- Android WebView 환경에서 Firebase 인증 팝업, 외부 링크, 파일 선택 등은 추가 조정이 필요할 수 있습니다.

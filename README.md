# dock

내 안드로이드 앱들의 최신 APK를 올려 두는 공개 배포 저장소입니다.

- 앱마다 Release 하나(태그 = 앱 이름)를 두고, 각 앱의 GitHub Actions가 빌드 뒤 `app.apk`(familyguard는 `monitor-app.apk`·`admin-app.apk`)와 `version.json`을 덮어씁니다.
- 앱은 토큰 없이 `https://github.com/parkhaas/dock/releases/download/<앱 이름>/version.json`을 읽어 새 버전을 확인합니다.
- 이 저장소에는 코드가 없습니다. 설치 파일은 Releases에서 받으세요.

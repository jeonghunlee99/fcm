# Flutter Firebase Push Notification Example

## 프로젝트 소개 📱

이 프로젝트는 **Flutter**와 **Firebase**를 사용하여 푸시 알림 기능을 구현하는 예제
## 주요 기능 ✨

1. **Firebase 설정 및 초기화**: Firebase 초기화를 통해 애플리케이션에서 Firebase 기능을 사용할 수 있도록 설정
2. **푸시 알림 처리**:
   - **백그라운드 메시지 처리**: 앱이 백그라운드에 있을 때도 푸시 알림 메시지를 수신하고 처리
   - **포어그라운드 메시지 처리**: 앱이 실행 중일 때 푸시 알림을 수신하고 로컬 알림을 통해 사용자에게 알림을 표시
3. **디바이스 토큰 획득**: Firebase에서 제공하는 디바이스 토큰을 획득하여 알림을 전송
4. **로컬 알림 설정**: `flutter_local_notifications` 패키지를 이용해 로컬 알림을 설정

## 사용된 패키지 📦

- [firebase_core](https://pub.dev/packages/firebase_core): Firebase 초기화를 위한 필수 패키지.
- [firebase_messaging](https://pub.dev/packages/firebase_messaging): Firebase Cloud Messaging(FCM) 기능을 구현하기 위한 패키지.
- [flutter_local_notifications](https://pub.dev/packages/flutter_local_notifications): 로컬 알림을 표시하기 위한 패키지.

## 프로젝트 설정 방법 ⚙️

1. Firebase 콘솔에서 Firebase 프로젝트를 생성하고, Android 및 iOS 앱을 추가합니다.
2. `google-services.json`(Android) 및 `GoogleService-Info.plist`(iOS) 파일을 Flutter 프로젝트에 추가합니다.
3. `pubspec.yaml` 파일에 필요한 패키지를 추가하고 `flutter pub get` 명령어로 패키지를 설치합니다.
4. Firebase 설정 및 로컬 알림 초기화 코드를 `main.dart` 파일에 추가합니다.


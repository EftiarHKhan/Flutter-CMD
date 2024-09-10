# Flutter-CMD

## App inspect - When local db is not opening
adb kill-server adb start_server

## Dart fix to check issue
### fix minor issue & check issues
dart fix --dry-run
### fix issues forcely
dart fix --apply

### flutter web directory build
flutter build web --release -t lib/main_web.dart

## MAC cmd
### Remove file by file extension
find . -type f -name "*.apk" -exec rm {} \;

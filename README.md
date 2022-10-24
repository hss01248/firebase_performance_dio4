![dio_fire_png](https://user-images.githubusercontent.com/121164/80114944-726aca80-8584-11ea-975c-1165765d33e6.png)

[![pub version](https://img.shields.io/pub/v/firebase_performance_dio.svg?label=pub&color=orange)](https://pub.dev/packages/firebase_performance_dio)

## Description

Dio's Interceptor implementation that sends http request metric data to Firebase.

## Usage

```dart
final dio = Dio();
final performanceInterceptor = DioFirebasePerformanceInterceptor();
dio.interceptors.add(performanceInterceptor);
```

__SUGGESTION:__ If you use dio client as a singleton you can use this interceptor as singleton as well.


claude 
```
lib/
├── main.dart
├── app.dart
├── config/
│   ├── routes/app_router.dart
│   └── env/
├── core/
│   ├── constants/
│   ├── di/
│   ├── error/
│   ├── network/
│   ├── theme/
│   ├── usecases/
│   └── utils/
├── features/
│   ├── auth/
│   │   ├── data/
│   │   │   ├── datasources/
│   │   │   ├── models/
│   │   │   └── repositories/
│   │   ├── domain/
│   │   │   ├── entities/
│   │   │   ├── repositories/
│   │   │   └── usecases/
│   │   └── presentation/
│   │       ├── bloc/
│   │       ├── pages/
│   │       └── widgets/
│   └── home/   (نفس هيكل auth)
└── shared/
    ├── widgets/
    └── extensions/


```

gpt
```
lib/
├── app/
│   └── app.dart
├── core/
│   └── theme/
│       └── app_theme.dart
├── features/
│   ├── home/
│   │   └── presentation/
│   │       └── pages/
│   │           └── home_page.dart
│   ├── orders/
│   │   └── presentation/
│   │       └── pages/
│   │           └── orders_page.dart
│   └── profile/
│       └── presentation/
│           └── pages/
│               └── profile_page.dart
├── navigation/
│   └── main_navigation.dart
└── main.dart
```
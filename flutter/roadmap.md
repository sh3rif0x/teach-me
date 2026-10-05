# Flutter Roadmap

1. Dart Basics
   - variables, types, null safety
   - functions, closures
   - OOP: classes, inheritance, mixins, abstract
   - collections, generics
   - async: Future, async/await, Stream

2. Flutter Basics
   - widgets: Stateless / Stateful
   - layouts: Row, Column, Stack, ListView, GridView
   - Container, Text, Image, Button, TextField
   - Theme, Navigation (Navigator)
   - Forms + validation

3. State Management (Local)
   - setState
   - InheritedWidget
   - Provider

4. Navigation & Routing
   - go_router
   - deep links
   - route guards

5. Networking
   - http / dio
   - JSON parsing (json_serializable / freezed)
   - interceptors, error handling

6. Local Storage
   - shared_preferences
   - flutter_secure_storage
   - sqflite / drift / hive / isar

7. Advanced State Management
   - flutter_bloc (Cubit / Bloc)
   - Riverpod

8. Clean Architecture
   - data / domain / presentation
   - entities, models, repositories, usecases
   - dartz / fpdart (Either)
   - get_it + injectable (DI)

9. Backend / Services
   - Firebase: Auth, Firestore, Storage, FCM
   - REST APIs / WebSockets
   - Supabase (alternative)

10. UI/UX Advanced
    - animations (implicit / explicit / Hero)
    - CustomPainter
    - responsive (LayoutBuilder, MediaQuery)
    - localization (intl, easy_localization)
    - dark / light theme

11. Testing
    - unit tests
    - widget tests
    - integration tests
    - mocktail / bloc_test

12. Platform & Native
    - platform channels
    - permissions
    - maps, camera, notifications
    - Flavors (dev / staging / prod)

13. Performance & Quality
    - DevTools profiling
    - const widgets, lazy lists
    - lints, code generation (build_runner)

14. CI/CD & Release
    - GitHub Actions / Codemagic
    - Play Store / App Store publishing
    - code signing, versioning

15. Bonus
    - Flutter Web / Desktop
    - Isolates
    - Monorepo (melos)
    - Native Android/iOS basics
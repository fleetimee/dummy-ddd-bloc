


![Untitled Diagram drawio](https://github.com/octavvia/dummy-ddd-bloc/assets/86775678/497af21a-2a6d-49e0-b172-4969089218fb)


step : 
buat structure
- constant -> menampung http dll

- data_state.dart

- entities -> response or request 

- article_repository.dart -> abstract class

- article_model.dart -> generate from json you can using quicktype.io

- article_repository_implementation -> 

- news_api_service -> method using POST GET UPDATE DELETE

```
flutter pub run build_runner build
```

- core/usecase.dart

- feature/usecase/get_article.dart
    - based name 

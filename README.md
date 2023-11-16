### 한상 🍽️
사용자 맞춤 레시피 추천 서비스
- 사용자와 유사한 취향을 고려한 협업 필터링 기반 
- 식자재 인식을 통한 레시피 추천 서비스

### 디렉토리 설계
```
📦lib
 ┣ 📂login
 ┃ ┣ 📜kakao_login.dart
 ┃ ┣ 📜login.dart
 ┃ ┣ 📜main_view_model..dart
 ┃ ┗ 📜start.dart
 ┣ 📂object_detection
 ┃ ┣ 📂servieces
 ┃ ┃ ┣ 📜CameraSettings.dart
 ┃ ┃ ┣ 📜Classifier.dart
 ┃ ┃ ┗ 📜Recognition.dart
 ┃ ┣ 📂utils
 ┃ ┃ ┗ 📜IsolateUtils.dart
 ┃ ┣ 📂views
 ┃ ┃ ┣ 📜BoxWidget.dart
 ┃ ┃ ┗ 📜HomeScreen.dart
 ┃ ┣ 📜CameraView.dart
 ┃ ┗ 📜ImageUtils.dart
 ┣ 📂provider
 ┃ ┣ 📜user_bookmarkedRecipes.dart
 ┃ ┗ 📜user_preferences_provider.dart
 ┣ 📂Recipe
 ┃ ┣ 📜HttpRequests.dart
 ┃ ┣ 📜RecipeDetailPage.dart
 ┃ ┗ 📜RecipePage.dart
 ┣ 📂review
 ┃ ┗ 📜review.dart
 ┣ 📂signup
 ┃ ┣ 📜additional_info.dart
 ┃ ┗ 📜signup.dart
 ┣ 📂tab
 ┃ ┣ 📜Ingredient_scanner.dart
 ┃ ┣ 📜menu.dart
 ┃ ┣ 📜mypage.dart
 ┃ ┗ 📜search.dart
 ┣ 📂user_setting
 ┃ ┣ 📜step1.dart
 ┃ ┗ 📜step2.dart
 ┣ 📜home.dart
 ┣ 📜main.dart
 ┗ 📜style.dart
```

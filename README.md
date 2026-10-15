# AndroidFilms

Application Android de découverte de films, séries et acteurs, développée en Kotlin
avec Jetpack Compose, dans le cadre de ma formation d'ingénieure (ISIS, groupe INSA, 2024).

## Fonctionnalités
- Films, séries et acteurs tendance de la semaine (API TMDB)
- Recherche par mot-clé
- Fiches détaillées des films et des séries, avec le casting
- Favoris enregistrés localement (Room)
- Affichage adapté au portrait et au paysage

## Architecture et technologies
- **Kotlin**, **Jetpack Compose**, Material 3
- Architecture **MVVM** : ViewModel et Repository
- **Hilt** pour l'injection de dépendances
- **Retrofit** et **Moshi** pour les appels à l'API REST
- **Room** pour la persistance locale
- **Navigation Compose**, **Coil** pour les images
- Une fausse implémentation de l'API (`FakeTmdbAPI`) pour développer sans réseau

## Lancer le projet
1. Créer une clé d'API sur [themoviedb.org](https://www.themoviedb.org/).
2. La renseigner à la place de `CLE_API_TMDB` dans
   `app/src/main/java/com/example/firstapplication/Repository.kt`.
3. Ouvrir le projet dans Android Studio et lancer l'application (Android 7.0 minimum).

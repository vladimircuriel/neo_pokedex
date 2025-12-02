<h1 align="center">
   Neo Pokédex - Mobile Pokédex App
</h1>

<p align="center"> 
  <img src="https://github.com/user-attachments/assets/21f23e51-a10d-46e6-b7b9-700d2cb32f1f" alt="neo-pokedex" width="100"/>
</p>

<div align="center">
  <img src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white" />
  <img src="https://img.shields.io/badge/GraphQL-DA0093?style=for-the-badge&logo=graphql&logoColor=white" />
  <img src="https://img.shields.io/badge/graphql_flutter-1a1a1a?style=for-the-badge&logo=graphql&logoColor=DA0093" />
  <img src="https://img.shields.io/badge/Hive-FCCA3E?style=for-the-badge&logo=hive&logoColor=000000" />
  <img src="https://img.shields.io/badge/shared_preferences-333333?style=for-the-badge&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/flutter_animate-02569B?style=for-the-badge&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/share_plus-000000?style=for-the-badge&logo=share&logoColor=white" />
  <img src="https://img.shields.io/badge/cached_network_image-1a1a1a?style=for-the-badge&logo=flutter&logoColor=white" />
</div>

---

**Neo Pokédex** is a cross-platform mobile application built with **Flutter** and **Dart**. It provides a complete interface for exploring detailed Pokémon information by consuming the PokeAPI through **GraphQL**. The app lets users browse the full Pokémon list, view stats and evolutions, search by name or number, and save favorites locally.


- [Features](#features)
- [Application](#application)
- [Tools Used](#tools-used)
- [Areas for Improvement](#areas-for-improvement)


## Features
  
### Pokémon Browser & Details
- List screen showing each Pokémon with name, image, and types.  
- Search bar supporting lookup by name or Pokédex number.  
- Detailed screen displaying stats, abilities, evolutions, and moves.  
- Favorite system allowing users to save custom Pokémon lists locally.

### GraphQL Integration
- Optimized GraphQL queries for list pagination and detailed Pokémon data.  
- Uses the **graphql_flutter** package to fetch real-time data from the PokeAPI GraphQL endpoint.

### Navigation & UX
- Smooth transitions between list and detail screens with animations.  
- Advanced filtering and sorting: type, generation, abilities, power, and base stats.  
- Clean layout with UI enhancements and animated elements.

## Application

https://github.com/user-attachments/assets/0963226c-06cf-4aae-99ff-37ae61c3dfe3

## Tools Used

- ![Flutter](https://img.shields.io/badge/Flutter-02569B?logo=flutter&logoColor=white&style=flat-square) **Flutter**: Cross-platform UI framework powering the interface and animations.  
- ![Dart](https://img.shields.io/badge/Dart-0175C2?logo=dart&logoColor=white&style=flat-square) **Dart**: Language used for app logic, state handling, and GraphQL interactions.  
- ![GraphQL](https://img.shields.io/badge/GraphQL-DA0093?logo=graphql&logoColor=white&style=flat-square) **GraphQL (graphql_flutter)**: Fetches Pokémon data efficiently with queries for lists and details.  
- ![Hive](https://img.shields.io/badge/Hive-FCCA3E?logo=hive&logoColor=000000&style=flat-square) **Hive**: Lightweight local database used to store favorites and offline data.  
- ![shared_preferences](https://img.shields.io/badge/shared_preferences-333333?logo=flutter&logoColor=white&style=flat-square) **shared_preferences**: Stores quick local flags and user preferences.  
- ![flutter_animate](https://img.shields.io/badge/flutter_animate-02569B?logo=flutter&logoColor=white&style=flat-square) **flutter_animate**: Provides smooth and expressive animations across the app.  
- ![share_plus](https://img.shields.io/badge/share_plus-000000?logo=share&logoColor=white&style=flat-square) **share_plus**: Enables sharing Pokémon cards with other apps.  
- ![cached_network_image](https://img.shields.io/badge/cached_network_image-1a1a1a?logo=flutter&logoColor=white&style=flat-square) **cached_network_image**: Handles efficient image loading and caching for Pokémon sprites.

## Areas for Improvement

- Offline mode applies only to favorites; expanding offline browsing would improve reliability.  
- Evolutions and moves could include interactive diagrams or animations.  
- No built-in analytics to track user activity or search patterns.  
- No cloud sync; favorites remain local to the device.

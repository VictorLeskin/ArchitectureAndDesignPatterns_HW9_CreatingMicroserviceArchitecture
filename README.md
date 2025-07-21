# ArchitectureAndDesignPatterns_HW9_CreatingMicroserviceArchitecture
Home work 9 of OTUS counce 

Cпецификация OpenAPI (Swagger) для круговых турниров по игре, где каждый играет с каждым с поддержкой регистрации
игроков, организаторов турниров и рейтингового агенства.
Результатом игры может быть только победа одного игрока. 
 Основные эндпоинты:
   - /new_player (POST) - завести нового игрока
   - /new_tournir_organizeer  (POST)  - завести нового организатора турнира
   - /new_tournament (POST)  - завести новый турнир со списком игроков  участвующих в турнире
   - /game_result (GET) - получить результат  игры
   - /tournament_result (GET) - получить результат  турнира
   - /new_rating (POST) - обновить текущий рейтинг

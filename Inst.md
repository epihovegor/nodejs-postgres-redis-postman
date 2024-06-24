

## Подключение к терминалу Redis
docker exec -it redis-container redis-cli

## Запрос того, что закешировал Redis (учесть, что index.js информация хранится 10 сек)
GET user-list

## Просмотр логов Redis
docker logs ID контейнера 
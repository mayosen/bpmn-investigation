Ссылки

- http://localhost:8088/tasklist
- http://localhost:8088/operate
- http://localhost:8088/broker
- http://localhost:8088/identity

docker compose down -v --remove-orphans

docker compose up -d

docker compose logs -f

TODO:
- Проверить, что DMN переменные инициализируются. Нужно расставить блоки

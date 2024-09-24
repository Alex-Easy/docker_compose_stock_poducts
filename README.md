### Задание
Cделать конфигурацию docker-compose любого Вашего проекта из курса по Django, который использует БД (например, CRUD: Склады и запасы).

Результатом является docker-compose.yml файл с описанием конфигурации для развертывания приложения (и не забудьте про Dockerfile).

### Решение
В проекте предусмотрен файл docker-compose.yaml, в котором указана конфигурация для развертывания приложения,
командой ``` docker-compose up -d --build ``` делаем сборку образов из файла dockerfile и запускаем контейнеры в 
фоновом режиме.
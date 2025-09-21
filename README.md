Стек:
 - <a href="https://nginx.org/">![Nginx](https://img.shields.io/badge/nginx-%23009639.svg?style=for-the-badge&logo=nginx&logoColor=white)</a>
 - <a href="https://www.docker.com/">![Docker](https://img.shields.io/badge/docker-%230db7ed.svg?style=for-the-badge&logo=docker&logoColor=white)</a>

Реализовано frontend-приложение, доступное в интернете по HTTPS.

 1. Приложение включает в себя одну HTML-страницу.
 2. Приложение доступно в интернете по доменному имени.
 3. Приложение имеет подключенный SSL-сертификат.
 4. Приложение использует Nginx.
 5. Приложение контейнеризировано и запускается при помощи Docker Compose.

https://docker-frontend-app.ru/

<hr>

Реализован CI-пайплайн для доставки на удаленный сервер frontend-приложения.

 1. Приложение использует React.
 2. Приложение доступно в интернете по протоколу HTTPS (подключен SSL-сертификат).
 3. Пайплайн написан на GitLab.
 4. Секреты (SSH-ключ и пароль для доступа к серверу) спрятаны в секреты проекта и отсутствуют в коде репозитория.

https://gitlab.com/develengie/docker-frontend-app

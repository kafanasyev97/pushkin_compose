1. Сделать команды:
   git submodule add git@github.com:kafanasyev97/pushkin.git frontend
   git submodule add git@github.com:kafanasyev97/pushkin_backend.git backend

2. Создать файлы .env в backend и frontend
   back:
   DB_HOST
   DB_PORT
   DB_NAME
   DB_USERNAME
   DB_PASSWORD

   front:
   VITE_API_URL - URL бэкенда

3. Команда для запуска контейнера docker-compose up --build
   обновить все подмодули git submodule update --init --recursive (????)

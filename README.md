# Vesсhatel
Платформа для трансляции потокового видео и просмотра видео-роликов.

## Технологический стэк
### Front-end
  - JavaScript, HTML, CSS
  - React
  - React-Router
  - Redux, Redux-thunk, Redux-Saga
  - Ant Design
  - Styled Components
  - React player
  - Particles-ts
  - Socket.io
  
### Back-end
  - Node.js
  - Express
  - PostgresQL
  - Sequelize ORM
  - Node media server
  - Ffmpeg
  - Web-sockets
  
## Команда проекта
  - Иван Пузырёв
  - Екатерина Гнеденко
  - Илья Тупицын
  - Артём Ивлев 


### Для запуска проекта
1. Склонировать репозиторий
2. Установить ffmpeg, создать файл .env и указать в нем по примеру файла env.example данные для БД и путь к ffmpeg
3. Выполнить комманду npm i, находясь в директории ~/server, затем в директории ~/client
4. Для миграции БД: находясь в директории ~/server, выполнить команду npx sequelize-cli db:migrate и для заполнения БД сидами npx sequelize-cli db:seed:all
5. Выполнить комманду npm start, находясь в директории ~/server, затем в директории ~/client

### "Hexlet Chat"
Очень упрощенный аналог Slack-чата, фронтенд которого построен на технологии React.
Особенности: 
- авторизация
- регистрация новых пользователей
- переключение по каналам
- управление каналами (добавление, переименование, удаление)
- всплывающие уведомления (react-toastify)
- фильтрация запрещенных слов (leo-profanity).

Сообщения отправляются на сервер через POST запрос, получение данных от сервера происходит через websockets.

React приложение построено с помощью Vite.

#### Ссылка на проект
https://frontend-project-12-yvu1.onrender.com/

#### Используемые технологии
- React, React Router, Redux Toolkit, React Bootstrap
- Formik, Yup, i18next
- Socket.io client
- Bootstrap

### Системные требования
 - Node.js 20+ & npm 10+

### Установка и запуск

Скопируйте репозиторий:
```bash
git clone https://github.com/Chuvikovsky/hexlet-chat.git
```

Перейдите в папку frontend-project-12
```bash
cd hexlet-chat
```

Установите зависимости
```bash
make install
```

Собирите приложение
```bash
make build
```

Запустите сервер
```bash
make start
```

Перейдите по ссылке [http://127.0.0.1:5001/login](http://127.0.0.1:5001/login)


![Hexlet Chat](public/chat-1.png)


![Hexlet Chat modal window](public/chat-2.png)
# Домашнее задание к лекции Node.js

  - Скачайте и установите node http://nodejs.org/download/
  - Проверьте установку из консоли
  
```
> node -v
> npm -v
```

## Сервер состояния вашего календаря

  - Необходимо написать реализацию сервера на node.js, который 
     - сможет сохранять **асинхронно** (в файловую систему) и отправлять **асинхронно** клиенту состояние календаря
     - сервер так же должен отдавать ваши статические .js .css .html файлы
     - разрешается использовать любые npm пакеты
     - синхронные функции модуля fs **запрещены**
  - Необходимо добавить файл `package.json` с описанием вашего проекта и его зависимостями

## Как проверить, что все работает

  - Скачать ваш git репозиторий с нуля
  - Выполнить в корне `npm install`
  - Запустить ваш сервер `node server.js`
  - Пройти по url `http://localhost:8080/` (порт ваш)
  - Ваше приложение должно запуститься и скачать с вашего сервера состояние и начать работать
  - Если у вас есть тесты, то сделайте, чтобы они работали по команде `npm test` see [example](https://github.com/azproduction/lmd/blob/master/package.json#L13-L15)


# utility-bills

Прежде всего нужно установить все необходимые пакеты:  
`npm install`

Далее создать копию файла `.env.template` и переименовать её в `.env`.  
В новом файле настроить параметры конфигурации.

Контракт деплоится с помощью truffle следующей командой:  
`truffle migrate --reset --compile-all --network private`

Сервер для веб-интерфейса запускается командой:  
`npm run dev`  
После чего он доступен по ссылке `localhost:8000`

Логин и пароль администратора предопределены (admin, admin).  
Адрес администратора (по совместительству владельца контракта) указывается в файле `.env`.

Для авторизации предварительно нужно войти в свой аккаунт в MetaMask (или другом провайдере), адрес которого был указан при регистрации.

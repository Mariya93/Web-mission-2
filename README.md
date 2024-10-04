# Mission 2

## Part 0
[Link] ()

## Part1
- Вопрос 1: Зачем нужен ssh? Ответ на пару предложений.
> Ответ: SSH (Secure Shell) используется для защищенного удаленного доступа и управления серверами через шифрованное соединение. Благодаря этому обеспечивается безопаснуя передача данных и управление сервером удаленно.

- Вопрос 2: Предположим, у вас есть прямой доступ к серверу(терминалу) под управлением ubuntu. У вас есть коллега Вася, который хочет получить доступ к этому серверу. Он генерирует пару ssh ключей с помощью команды ssh-keygen и дает вам свой публичный ключ. В какой файл на сервере нужно записать ключ, чтобы Вася смог подключиться к терминалу сервера?
> Ответ: Ключ нужно записать в файл ~/.ssh/authorized_keys на сервере. Там содержится список ключей, которым разрешено подключаться к серверу.

- Вопрос 3: Тут вопрос про АПИ. Разберитесь, что такое long polling и webhooks, опишите сами в нескольких предложениях, как они работают.
> Ответ: Long polling - метод клиент-серверного взаимодействия, при котором клиент отправляет запрос на сервер и сервер выдает ответ, в момент доступности актуальной информации. Webhooks - это метод передачи данных от сервера к клиенту в режиме реального времени (сервер отправляет данные клиенту сразу по мере их появления).

- Вопрос 4: Найдите информацию, что такое issues на гитхабе и для чего нужны. Также вставьте ссылки на пару примеров issues в популярных open source проектах.
> Ответ: Issues на GitHub - это инструмент для отслеживания ошибок, идей, задач и др в проекте. Примеры issues в популярных "не знаю, на сколько они популярны" open source проектах:

React: https://github.com/facebook/react/issues

VS Code: https://github.com/microsoft/vscode/issues

- Вопрос 5
> Ответ: Чтобы git отслеживал пустые папки, можно в них добавить файл, который будет сохранять папку в репозитории, даже если она пуста

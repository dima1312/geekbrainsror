Что нужно сделать к 10му уроку.

Ваше предыдущее Rack приложение размещенное на heroku и предоставленное мне через pull-request сделать на rails и так же выложить на heroku и сделать очередной pull-request.

Сделать это можно так:

1. В своем репозитории в своей ветке удаляете все файлы (ваш rack в гите сохранилось уже).
2. Создаете рельсовое приложение, делаете его, комитите так чтобы все приложение было у вас в корне вашей ветке
3. Пушите на хероку (с перезаписью)
```shell
git push heroku your_branch:master
```
4. Пушите в свою ветку в гитхабе
```shell
git push -f origin your_branch
```
5. Делаете пулл реквест (он может ругаться что нельзя смерджить)
6. Profit

Все вопросы принимаются в следующем порядке:

1. Указываете пункт задания на котором у вас проблема
2. Отмечаете чем закончился предыдущий пункт перед проблемой.
3. Получаете ответ что делать дальше.

Пример проведенной коммуникации с вымышленным аккаунтом в котором я все это провернул находится тут https://github.com/apavlyut/geekbrainsror/pull/1

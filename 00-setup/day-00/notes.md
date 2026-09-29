# Day 0 - Setup

## Что сделал

- Настроил Git
- Проверил user.name и user.email
- Создал новый SSH-ключ
- Добавил SSH-ключ в GitHub
- Проверил SSH-подключение к GitHub
- Создал репозиторий qa-ai-learning
- Клонировал репозиторий на компьютер
- Открыл проект в VS Code
- Настроил Git Bash как основной терминал
- Сделал первый commit и push
- Подключил GitHub к ChatGPT

## Git команды

git status
git add .
git commit -m "Day 0: setup learning environment"
git push

## Что запомнить

git status - посмотреть состояние репозитория

git add . - подготовить изменения к коммиту

git commit -m "..." - сохранить изменения в локальной истории Git

git push - отправить локальные коммиты на GitHub

git pull - забрать изменения с GitHub на компьютер

## Postman Native Git

.postman/ - служебная конфигурация связи локального проекта с Postman workspace

postman/ - коллекции, environments, globals, specs и другие Postman-файлы

Основные команды:

postman --version
postman collection new "API Learning"
postman collection list

ls -la postman
find postman -maxdepth 3 -type f

git status
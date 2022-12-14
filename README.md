# Домашнее задание ко 2 семинару по курсу "Введение в контроль версий"

## Краткая инструкция по работе с GIT

1. Создать новую директорию для проекта и перейти в неё.
2. Выполнить в терминале _git init_
3. Создать и отредактировать файл.
4. Записать все изменения в индекс _git add ._
5. Зафиксировать все изменения в GIT _git commit -m "commit description"_
6. Убедится в отсутствии файлов не попавших в коммит _git status_

## Основные команды GIT

- **git init** - Инициализация локального репозитория.
- **git status** -Получить информацию о git и его текущем состоянии.
- **git add** -Добавить файл или файлы к следующему коммиту.
  - **git add <filename>** - Добавить файл
  - **git add .** - Добавить все файлы в текущей директории
- **git commit -m "commit description"** - Создание коммита.
  - **git commit -a -m "commit description"** - тоже что и последовательное выполнение команд _git add ._ и _git commit -m "commit description"_. **_ ! Не работает для вновь созданных файлов. Для новых файлов нужно выполнить git add_**
- **git log** - Вывод на экран истории всех коммитов с их хеш-кодами.
  - **git log --online** - Сокращенный вывод на экран истории всех коммитов.
  - **git log -p** - Вывод на экран истории всех коммитов с отображением изменений в коммите
- **git checkout** - Переход от одного коммита к другому
- **git checkout master** -Вернуться к актуальному состоянию и продолжить работу
- \*\*git checkout -b <branch_name> - Создать ветку branch_name и перейти в неё
- **git diff**- Показать разницу между текущим файлом и файлом в коммите

## Базовый синтаксис markdown

[Базовый синтаксис markdown](https://www.markdownguide.org/basic-syntax/).

## Ссылка на статью по теме

[Статья на хабре](https://habr.com/ru/post/541258/).

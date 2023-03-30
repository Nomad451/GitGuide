# Гайд по системе контроля версий Git

## Установка Git и Visual Studio Code
**Установка Git для Windows, MAC, Linux:** http://git-scm.com/downloads

**Установка VSCode для Windows, MAC, Linux:** https://code.visualstudio.com/Download

При первом использовании Git необходимо представиться. Для этого
нужно ввести в терминале 2 команды:
```fix
git config --global user.name "Ваше имя английскими буквами"
git config --global user.email почта@example.com
```

## Основные команды Git:
```fix
git init - инициализация локального репозитория

git status - получить информацию от git о его текущем состоянии

git add - добавить файл или файлы к следующему коммиту

git commit -m "message" - создание коммита

git log - вывод на экран истории всех коммитов с их хеш-кодами

git checkout - переход от одного коммита к другому

git checkout master - вернуться к актуальному состоянию и продолжить работу

git diff - увидеть разницу между текущим файлом и закоммиченым файлом

git commit --amend -m "message" - изменение последнего коммита

mkdir незвание папки - создание новой директории

history - все введенные когда-либо в терминал команды
```
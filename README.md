# test-2

1. git status
2. git add [files] - добавляет файлы в stage
3. git commit -m "comment"
4. git log / git log --oneline - информация о коммите, авторе и дате /краткая запись о нашем коммите
5. git push [rep_link] [branch_name]
6. git remote -v - показывает текущую url ссылку на репозиторий и ее название (origin)
7. git branch - наши все ветки
8. git reset [file_name] / git reset --hard - удаляем из git add (Stage) файл который случайно добавили (К примеру node_modules) / удаляем ВСЕ внесенные изменения во всех файлах
9. git diff / git diff [file_name] - показывает те строки которые мы изменили, но не добавляли в stage (git add .)

##

## 1. // Слияние веток с помощью pull reguest в github.

10. git branch develop - создание новой develop ветки
11. git checkout develop - переключение на ветку develop

## далее отправляем ветку на гитхаб, там создаем НОВЫЙ пулл ревест сравнивая с веткой main/master. Далее добавляем описание к пулл реквесту и создаем! Потом любые разработчики могут посмотреть фичу которую вы сделали в данном пулл реквесте. Можно добавить людей который могут смотреть код (Справа в reviewers) и вводим гитхаб человека который может просматривать этот reviewers!

## А в files changes мы можем увидеть все изменения и по возможности написать все комментарии

## Далее после того, как все комменты внесли и баги пофиксили, в convertation снимаем все комменты нажимая на resolve convertation

### Далее уже можем мерджить ветку mearge на зеленую кнопку - соединяя ее с main/master

## После мерджа рекомендовано удалять ветку, т.к. она по-сути больше не нужна. Нажимаем delete branch

12. Далее нам все изменения из гитхаба надо подтянуть командой - git pull origin main/master - подтягиваем все изменения из ветки master к себе в ветку

## ====================================================

## 2. // Слияние веток с помощью git merge в терминале.

13. После удаления develop ветки из github, она в терминале у нас все равно останется. Поэтому ее нужно вручную удалить. Команда git branch -d develop

## -- Создаем новую ветку feature/main-page. 10-11 пункт и вносим изменения и делаем пуш на гитхаб от данной ветки!!

14. Далее переключаемся на main/master c помощью checkout и соединение веток с помощью merge.
    !! git merge feature/main-page !

15. Далее отправляем измениния от ветки main/master на гитхаб.
    git push origin feature/main-page

16. После соединений веток, мы можем удалить нашу ветку feature/main-page

# test-2

1. git status
2. git add [files] - добавляет файлы в stage
3. git commit -m "comment"
4. git log / git log --oneline - информация о коммите, авторе и дате /краткая запись о нашем коммите
5. git push [rep_link] [branch_name]
6. git remote -v - показывает текущую url ссылку на репозиторий и ее название (origin)
7. git branch - наша текущая ветка
8. git reset [file_name] / git reset --hard - удаляем из git add (Stage) файл который случайно добавили (К примеру node_modules) / удаляем ВСЕ внесенные изменения во всех файлах
9. git diff / git diff [file_name] - показывает те строки которые мы изменили, но не добавляли в stage (git add .)

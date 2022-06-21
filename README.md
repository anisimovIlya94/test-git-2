1. git status
2. git add [files] - добавляет файлы в stage
3. git commit -m "comment" = запись
4. git log / git log --oneline
5. git push [rep_link(ссылка на репозиторий)] [branch_name(ветка)]
6. git reset - отменить добавление файлов в stage
7. git diff - отображает измененные строки(можно применять к опеределенному файлу)
8. git reset --hard - вернет файлы в изначальное (с последнего сохранения) положение

Создание веток:
- с помощью pull requests
1. git branch - показывает все ветки, создать новую : git branch [*your branch*]
2. git checkout [*your branch*] - переключиться на другую ветку
3. git pull [rep_link] [branch_name] - добавление в среду разработки кода из ветки github
4. git branch -d [branch_name] - удалить ветку локально(в среде разработки)
- с помощью terminal
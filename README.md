1. git status
2. git add [files] = добавляет файлы в stage
3. git commit -m "комментарий" = запись
4. git log / git log --oneline = подробная / краткая информация о коммите
5. git push [rep_link] [branch_name] = отпрвка на удаленный репозиторий
6. git reset [files] = убирает данный файл / файлы из stage
7. git diff = позволяет смотреть на измененные строки
8. git reset --hard = возвращает все изменения
9. git branch = наши ветки
10. git branch [name] = добавление ветки, git branch -d [name] = удаление ветки (локально)
11. git checkout [name] = переключение на ветку name (Все изменения кода в одной ветке не затрагивают код другой ветки)
12. git pull [rep_link] [branch_name] = добавляет изменения из выбранной ветки на GitHub в локальную версию
13. git merge [name] = переносит код из ветки name в текущую ветку (локально) затем сделать git push и git branch -d [name] также и на GitHub (В Pull requests)

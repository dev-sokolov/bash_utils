# Основные команды Git

## `git commit`

```sh
git add file.txt        # Добавить один файл
git add .               # Добавить все файлы в текущей директории
git add -p              # Добавить файлы частично (пошаговое добавление)
```

## `git commit`
```sh
git commit -m "Сообщение коммита"  # Обычный коммит
git commit --amend                 # Изменить последний коммит
```

## `git status`
```sh
git status  # Показать статус репозитория
```

## `git log`
```sh
git log --oneline --graph --all  # Краткая история с ветками
git log -p                       # Показывает изменения в каждом коммите
```

## `git diff`
```sh
git diff                  # Разница между рабочими файлами и индексом
git diff --staged         # Разница между индексом и последним коммитом
git diff HEAD~1 file.txt  # Разница между текущей и предыдущей версией файла
```

## `git checkout`
```sh
git checkout main               # Переключиться на ветку main
git checkout -b new-feature     # Создать и переключиться на новую ветку
git checkout -- file.txt        # Восстановить файл из последнего коммита
```

## `git branch`
```sh
git branch                 # Показать список веток
git branch new-feature     # Создать новую ветку
git branch -d old-feature  # Удалить ветку (если нет незакоммиченных изменений)
git branch -D old-feature  # Принудительное удаление ветки
```

## `git merge`
```sh
git checkout main
git merge feature-branch  # Слить feature-branch в main
```

## `git rebase`
```sh
git checkout feature
git rebase main            # Переместить feature поверх main
git rebase --continue      # Продолжить после конфликта
git rebase --abort         # Отменить rebase
```

## `git reset`
```sh
git reset HEAD file.txt          # Удалить файл из индекса (но оставить изменения)
git reset --soft HEAD~1          # Отменить последний коммит, оставив изменения
git reset --hard HEAD~1          # Полностью отменить последний коммит и изменения
git reset --hard 53425t2rewt45   # Откатить изменения до коммита 53425t2rewt45
```

## `git revert`
```sh
git revert HEAD      # Откат последнего коммита
git revert abc123    # Откат конкретного коммита
```

## `git remote`
```sh
git remote -v              # Показать список удалённых репозиториев
git remote add origin URL  # Добавить удалённый репозиторий
git remote remove origin   # Удалить удалённый репозиторий
```

## `git fetch`
```sh
git fetch origin       # Скачать все изменения с origin
git fetch origin main  # Скачать изменения только для ветки main
```

## `git pull`
```sh
git pull origin main      # Скачать и слить изменения из main
git pull --rebase origin  # Скачать и выполнить rebase
```

## `git push`
```sh
git push origin main       # Отправить изменения в main
git push -u origin feature # Отправить новую ветку и запомнить origin
git push --force           # Принудительная отправка (осторожно!)
```

## `git tag`
```sh
git tag v1.0            # Создать тег v1.0
git tag -a v1.0 -m "Версия 1.0" # Создать аннотированный тег
git push origin --tags  # Отправить теги в удалённый репозиторий
```

## `git cherry-pick`
```sh
git cherry-pick abc123  # Применить коммит abc123 в текущую ветку
```

## `git stash`
```sh
git stash # ...
```

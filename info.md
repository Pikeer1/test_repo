# Основные команды семинара 3

git init - инициализация локального репозитория

git status - получить информацию от git о его текущем состоянии

git add -добавить файл или файлы к следующему коммиту

> git reset - убрать из индекса все добавленные в него изменения (в рабочей директории все изменения сохранятся)

> git checkout text.txt - отменить изменения в файле, вернуть состояние файла, имеющееся в индексе

> git reset --hard - отменить изменения; вернуть то, что в коммите, на который указывает HEAD (незакомиченные изменения удалены из индекса и из рабочей директории, неотслеживаемые файлы останутся на месте)

> git clean -df - удалить неотслеживаемые файлы и директории

> git cherry-pick --abort - прервать конфликтный перенос коммитов

> git cherry-pick --continue - продолжить конфликтный перенос коммитов (сработает только после решения конфликта)
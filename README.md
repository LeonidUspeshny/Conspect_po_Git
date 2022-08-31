# Notice

git clone https://github.com/libgit2/libgit2 клонироует репозиторий (на локальный диск)

 git clone https://github.com/libgit2/libgit2 mylibgit
Эта команда делает всё то же самое, что и предыдущая, только результирующий каталог будет назван mylibgit.

git status - Основной инструмент, используемый для определения, какие файлы в каком состоянии находятся 


## Создать новый репозиторий или проект

```
echo "# test" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/LeonidUspeshny/test.git
git push -u origin main
```

Отслеживание новых файлов git add README

Если вы изменили файл после выполнения git add, вам придётся снова выполнить git add, чтобы проиндексировать последнюю версию файла:


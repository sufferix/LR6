# Лабораторная работа №6
_Цель лабораторной работы_: изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.

## Ход работы
1. Клонирование репозитория, настройка клиента git, создание текстового файла, первого коммита с ним и выгрузка коммита на локальный репозиторий
<p align="center">
  <img src="https://github.com/sufferix/LR6/blob/report/screens/705.png">
</p>

Просмотр изменений во всех коммитах
<p align="center">
  <img src="https://github.com/sufferix/LR6/blob/report/screens/706.png">
</p>

2. Создание новой ветки и просмотр изменений в ней
<p align="center">
  <img src="https://github.com/sufferix/LR6/blob/report/screens/707.png">
</p>

4. Слияние двух веток, прошло без конфликта
<p align="center">
  <img src="https://github.com/sufferix/LR6/blob/report/screens/708.png">
</p>

Создание коммита с новым файлом, отмечая, что произошло слияние
<p align="center">
  <img src="https://github.com/sufferix/LR6/blob/report/screens/709.png">
</p>

5. Удаление созданной ветки
<p align="center">
  <img src="https://github.com/sufferix/LR6/blob/report/screens/710.png">
</p>

Просмотр промежуточных коммитов
<p align="center">
  <img src="https://github.com/sufferix/LR6/blob/report/screens/712.png">
</p>

6. Добавление других изменений в репозиторий, на данном скриншоте была добавлена картинка
<p align="center">
  <img src="https://github.com/sufferix/LR6/blob/report/screens/714.png">
</p>

Просмотр коммитов
<p align="center">
  <img src="https://github.com/sufferix/LR6/blob/report/screens/714g.png">
</p>

А на этом скриншоте показано, как был добавлен в коммит уже существующий файл, который потерпел изменения, и как был удалён новый файл, после этого была сделана выгрузка коммита. Далее был создан коммит с картинкой, который в последствие подвергся откату
<p align="center">
  <img src="https://github.com/sufferix/LR6/blob/report/screens/715.jpg">
</p>

Окно, которое появилось при откате
<p align="center">
  <img src="https://github.com/sufferix/LR6/blob/report/screens/716.jpg">
</p>

Выгрузка коммитов и их просмотр
<p align="center">
  <img src="https://github.com/sufferix/LR6/blob/report/screens/717.png">
</p>
<p align="center">
  <img src="https://github.com/sufferix/LR6/blob/report/screens/718.png">
</p>

7. Создание ветки для отчёта и редактирование файла README.md
<p align="center">
  <img src="https://github.com/sufferix/LR6/blob/report/screens/720.png">
</p>

Добавление папки со скриншотами в новую ветку
<p align="center">
  <img src="https://github.com/sufferix/LR6/blob/report/screens/721.png">
</p>

8. Форматированная история операций
<p align="center">
  <img src="https://github.com/sufferix/LR6/blob/report/screens/722.png">
</p>

## Лог команд
```
git clone
git config user.name
git config user.email
git add
git commit -m
git push
git show *хэш коммита*
git branch
git checkout
git log
git merge
git branch -d
git rm
git revert HEAD
git push --set-upstream origin 
git log --pretty=format:"%h - %an, %ar : %s"
```

## Вывод
В данной лабораторной работе были изучены базовые возможности системы управления версиями, был получен опыт работы с Git Api и опыт работы с локальным и удаленным репозиторием.
Привет, GitHub и мир

## Инструкция git

* git branch -m старое_название_ветки Новое_название_ветки

* git init – инициализация локального репозитория
* git status – получить информацию от git о его текущем состоянии
* git add – добавить файл или файлы к следующему коммиту
* git commit -m “message” – создание коммита.
* git log – вывод на экран истории всех коммитов с их хеш-кодами
* git branch – посмотреть список веток в репозитории
* git bgiranch <название ветки> – создать новую ветку
* git checkout <название ветки> – переход к другой ветке
* git branch -d <название ветки> – удалить ветку

## Инструкция markdown

* "# Заголовок" – выделение заголовков. Количество символов “#” задаёт уровень заголовка (поддерживается 6 уровней).

* = или - – подчёркиванием этими символами (не менее 3 подряд) выделяют заголовки первого (“=”) и второго (“-”) уровней.
* ** Полужирное начертание** или __ Полужирное начертание__
* *Курсивное начертание* или _Курсивное начертание_
* ***Полужирное курсивное начертание***
* ~~Зачёркнутый текст~~
* Строка – ненумерованные списки, символ “*” в начале строки
* 1, 2, 3 … – нумерованные списки

## Работа с удаленными репозиториями
* git clone - копирование внешенего репозитория на ПК

* git pull - скачивание всего из удаленного репозитория на ПК
* git push - отправка текущего репозитория на удаленный
* как сделать pull request:
    - Делаем fork репозитория
    - Делаем clone СВОЕЙ версии репозитория
    - Создаем новую ветку и в НЕЕ вносим свои изменения
    - Фиксируем изменения (делаем коммиты)
    - Отправляем свою версию в свой GitHub
    - На сайте GitHub нажимаем кнопку pull request 
# Задание 1
По аналогии с практикой из лекции создайте свой docker image с http сервером nginx. Замените страницу приветсвия Nginx на своё (измените текст приветствия на той же странице).

Подсказки:
На проверку присылается GitHub-репозиторий с Dockerfile и статичными файлами для него


## Команды для работы с контейнером

* Создание образа:

``` docker build . -t my_first_dockerfile```


* Создание и запуск контейнера: 

``` docker run -d -p 7777:80 --name my_first_container my_first_dockerfile```


* Остановка контейнера по имени:

```docker stop my_first_container```


* Запуск контейнера по имени:

```docker start my_first_container```


* Удаление контейнера по имени:

```docker rm my_first_container```
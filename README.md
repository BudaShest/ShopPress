# Shopa Press
## Fast and lightweight CMS for online commerce 

Мы - комманда разработчиков из шараги докажем Вам, что говнокод может выйти совершенно на новый уровень!

### Установка
``` docker-compose up ```

Также вам необходимо будет развернуть папку [vendor](https://habr.com/ru/post/439200/)
Для этого мы рекомендуем выполнить команду:  

``` docker container exec -it <php_container_name> /bin/sh ```

И уже внутри контенейнера выполнить:

``` composer install ```

P.s чтобы узнать имя контейнера(<php_container_name>) выполните:

``` docker container ls -a ```


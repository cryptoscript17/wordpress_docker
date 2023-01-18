# wordpress_docker



1) В новой папке выполнить:
    
    git clone https://github.com/cryptoscript17/wordpress_docker.git

2) Скачать дистрибутив Вордпресс [https://ru.wordpress.org/] и распаковать внутрь папки с конфигурационным файлом docker-compose.yml


3) Выполнить сборку командой:

    docker-compose up -d
    
4) Сайт будет доступен локально по адресу [http://localhost:8000], а БД работает на TCP 3306.

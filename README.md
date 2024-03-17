Тестовый проект на Laravel
Этот проект представляет собой тестовый проект, разработанный с ис-пользованием фреймворка Laravel. Он показывает как работать в данном фреймворке с маршрутами и контроллерами.
Установка
•	Склонируйте репозиторий на свой локальный компьютер:git clone https://github.com/yourusername/app402.git
•	Перейдите в каталог проекта: cd _путь до проекта_/app402
•	Установите зависимости через Composer: composer install
•	Скопируйте файл .env.example и переименуйте его в .env. Настройте со-единение с базой данных в файле .env.
•	Сгенерируйте ключ приложения:php artisan key:generate
•	Выполните миграции для создания таблиц в базе данных:php artisan mi-grate
•	Запустите веб-сервер:php artisan serve
•	Теперь проект доступен по адресу http://localhost:8000.
Использование:
Чтобы посмотреть страничку About – перейдите по ссылке http://localhost:8000/about_us
Чтобы посмотреть данные базы данный с конкретным ID - http://localhost:8000/posts/2 (где 2 - id конкретной строки в базе данных)

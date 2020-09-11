Тестовое задание для PHP-программиста
=====================================

на Symfony и Slim пишу в первый раз 😅 

**Установка:**
1. Клонируем репозиторий
2. Заходим репозитори и устанавливаем пакеты коммандой `composer install`
3. Создаем файл `.env.local` и прописываем туда конфиг пример:
`APP_ENV=prod
DATABASE=mysql://webmaster:webmaster@localhost:3306/slim_project
`

4.Инициализируем структуру таблицы `Movie` c помошью комманды `php bin/console orm:schema-tool:create`
 
Тянем данные с помошью команды `php bin/console fetch:trailers `


**Профит 🎉🎉**

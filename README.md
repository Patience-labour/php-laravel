# Ответы на вопросы:

1. Список основных composer-пакетов Laravel после установки:

## Основные пакеты фреймворка:
* laravel/framework - ядро Laravel
* laravel/sail - Docker-окружение для разработки
* laravel/sanctum - API аутентификация
* laravel/tinker - REPL для взаимодействия с приложением

## Зависимости:

* guzzlehttp/guzzle - HTTP-клиент
* fakerphp/faker - генерация фейковых данных
* monolog/monolog - логирование
* nesbot/carbon - работа с датами и временем
* ramsey/uuid - генерация UUID
* vlucas/phpdotenv - работа с переменными окружения
* voku/portable-ascii - работа со строками

## Внутренние компоненты:
* doctrine/inflector - преобразование слов
* dragonmantank/cron-expression - парсинг cron-выражений
* egulias/email-validator - валидация email
* league/commonmark - Markdown парсер
* league/flysystem - файловая система
* league/mime-type-detection - определение MIME-типов

2. Директория config и её содержимое

## В директории config/ хранятся файлы конфигурации:
* app.php - основные настройки приложения
* auth.php - настройки аутентификации
* broadcasting.php - веб-сокеты и широковещание
* cache.php - настройки кэширования
* cors.php - CORS политики
* database.php - настройки базы данных
* filesystems.php - файловые системы и диски
* hashing.php - хеширование паролей
* logging.php - логирование
* mail.php - настройки почты
* queue.php - очереди задач
* services.php - настройки сторонних сервисов
* session.php - управление сессиями
* view.php - шаблонизатор Blade

3. Директории с бизнес-логикой приложения

## Основные классы с бизнес-логикой хранятся в:
* app/Models/ - Eloquent модели (работа с данными)
* app/Http/Controllers/ - контроллеры (обработка запросов)
* app/Services/ - сервисные классы (создаются разработчиком)
* app/Jobs/ - фоновые задачи
* app/Listeners/ - обработчики событий
* app/Providers/ - сервис-провайдеры
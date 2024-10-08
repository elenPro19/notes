# Проект Laravel "Заметки"

Добро пожаловать в проект "Заметки".

Это приложение создано на фреймворке Laravel c использованием Bootstrap для привлекательного интерфейса и позволяет пользователям вести заметки в удобном формате.

## Возможности проекта
- Создание, редактирование и удаление заметок
- Просмотр заметок в виде карточек


## Установка и запуск проекта

### Шаг 1: Клонирование репозитория

Сначала клонируйте репозиторий на пк:

```bash
git clone https://github.com/elenPro19/notes.git
```

### Шаг 2: Переход в директорию проекта

```bash
cd notes
```
### Шаг 3: Установка зависимостей

Убедитесь, что у вас установлен Composer. После этого выполните команду:

```bash
composer install
```

### Шаг 4: Настройка переменных окружения

Скопируйте файл `.env.example` в `.env`:

Откройте файл `.env` и настройте параметры подключения к вашей базе данных:

```dotenv
DBCONNECTION=mysql
DBHOST=127.0.0.1
DBPORT=3306
DBDATABASE=db_name 
DBUSERNAME=root
DBPASSWORD=password
```

### Шаг 5: Генерация ключа приложения

Сгенерируйте ключ для вашего приложения:

```bash
php artisan key:generate
```

### Шаг 6: Миграция базы данных

Перед запуском миграций базы данных убедитесь, что вы правильно настроили подключение к MySQL в файле `.env`.

Убедитесь, что сервер MySQL работает. Это можно сделать через XAMPP, MAMP или любым другим способом, который вы используете для управления MySQL.

Запустите миграции для создания необходимых таблиц:

```bash
php artisan migrate
```

### Шаг 7: Запуск сервера

Теперь вы можете запустить встроенный сервер Laravel:
```bash
php artisan serve
```

После этого откройте ваш браузер и перейдите по адресу: [http://localhost:8000](http://localhost:8000)

## Обратная связь
Если у вас есть идеи по улучшению проекта или вы нашли ошибку, пожалуйста, свяжитесь с нами по email dvmost19@gmail.com

Спасибо за использование проекта "Заметки"!

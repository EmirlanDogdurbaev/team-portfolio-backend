### Бэкенд портфолио

Этот репозиторий содержит бэкенд часть веб-сайта портфолио, разработанного с использованием фреймворка Laravel и управляемого базой данных PostgreSQL.

- **Репозиторий бэкенда:** [Ссылка на репозиторий бэкенда](https://github.com/EmirlanDogdurbaev/team-portfolio-backend)

### Начало работы

Чтобы настроить и запустить бэкенд локально, выполните следующие шаги:

1. **Клонировать репозиторий:**
   ```bash
   git clone https://github.com/EmirlanDogdurbaev/team-portfolio-backend
   ```

2. **Установить зависимости:**
   ```bash
   cd portfolio-backend
   composer install
   ```

3. **Настройка базы данных:**
    - Создайте файл `.env` на основе `.env.example` и укажите параметры подключения к базе данных PostgreSQL.
    - Выполните миграции для создания необходимых таблиц в базе данных:
      ```bash
      php artisan migrate
      ```

4. **Запустить сервер разработки:**
   ```bash
   php artisan serve
   ```

Бэкенд будет доступен по адресу `http://localhost:8000`.

### Участники

- Emirlan Dogdurbaev(email: emirlandogdurbaev@gmail.com)


Если у вас возникнут вопросы или проблемы с бэкендом проекта, не стесняйтесь обращаться к участникам нашей команды, указанным выше.

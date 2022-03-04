# ТЗ фитнес
### 1. Цель проекта
Цель проекта - разработать сайт конструктор тренировок. Пользователь может составлять персональную тренировку, выбирая несколько элементов из 25 видео. Выбранные видео воспроизводятся в одном плейлисте без паузы подряд. 25 видео должны быть разделены на блоки по категориям упражнений (к примеру упражнения стоя, упражнения сидя и т.д.). Помимо этого на сайте будут отдельные тренировки, которые пользователь сможет зациклить на определенное количество времени (к примеру: одно и то же упражнение будет повторяться раз за разом на протяжении 20 минут). Пользователь получаает доступ к функционалу сайта после оплаты.
 
### 2. Описание системы
Система состоит из следующих функциональных блоков:  
1. Регистрация, аутентификация и авторизация
2. Функционал оплаты доступа к сайту (единоразовая оплата)
3. Конструктор тренировок

### 2.1 Регистрация
- имя и фамилия - обязательное поле  
- почта - обязательное поле  
- пароль - обязательное поле

### 2.1.1. Типы пользователей
Система предусматривает 3 типа пользователей: администратор, гость и клиент.  
- Администратор - полный доступ + редактирование сайта (добавлять видео, изменять контактную информацию и пр.).  
- Гость - видит основную информацию о сайте и поверхностно функционал.  
После регистрации в системе получает статус клиента.
- Клиент - после оплаты может просматривать и использовать весь функционал сайта.

### 2.2. Оплаты доступа к сайту
После регистрации пользователь имеет возможность единоразово оплатить доступ к сайту.  

### 2.3 Конструктор тренировок 
- Составить личную тренировку из выбранных видео.  
(Могу предложить имею. Добавить возможность сохранения тренировки в личном кабинете, чтобы пользователю не было необходимости создавать одну и ту же подборку несколько раз)
- Воспроизводить выбранное упражнение (1 видео) указанное количество времени

### 3. Предлагаемый стек технологий
- Бекенд:
  - Язык Python
  - Фреймворк Django
  - БД PostgreSQL
  - SQLAlchemy ORM
- Фронтенд:
  - html, css, js
Хранение файлов и изображений на сервере.
### 4. Требования к дизайну
- Светлый, легкий.
  

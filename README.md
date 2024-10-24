# Домашнее задание 24_1

# Задание 1
Создайте новый Django-проект, подключите DRF в настройках проекта.

# Задание 2
**Создайте следующие модели:**

Пользователь:
* все поля от обычного пользователя, но авторизацию заменить на email;
* телефон;
* город;
* аватарка.

Модель пользователя разместите в приложении users

Курс:
* название,
* превью (картинка),
* описание.

Урок:
* название,
* описание,
* превью (картинка),
* ссылка на видео.


_Урок и курс - это связанные между собой сущности._ 
_Уроки складываются в курс, в одном курсе может быть много уроков. Реализуйте связь между ними._

Модель курса и урока разместите в отдельном приложении. 
Название для приложения выбирайте такое, чтобы оно описывало то, с какими сущностями приложение работает. 
Например, lms или materials - отличные варианты.

# Задание 3

Опишите CRUD для моделей курса и урока. 
Для реализации CRUD для курса используйте Viewsets, а для урока - Generic-классы.

Для работы контроллеров опишите простейшие сериализаторы.

_При реализации CRUD для уроков реализуйте все необходимые операции_ 
_(получение списка, получение одной сущности, создание, изменение и удаление)._

Для работы контроллеров опишите простейшие сериализаторы.

Работу каждого эндпоинта необходимо проверять с помощью Postman.

_Также на данном этапе работы мы не заботимся о безопасности и_ 
_не закрываем от редактирования объекты и модели даже самой простой авторизацией._


# Дополнительное задание
Реализуйте эндпоинт для редактирования профиля любого пользователя 
на основе более привлекательного подхода для личного использования: Viewset или Generic.
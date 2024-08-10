### ___Описание задач___

Добавьте необходимые модели привычек.
Реализуйте эндпоинты для работы с фронтендом.
Создайте приложение для работы с Telegram и рассылками напоминаний.
Модели.
В книге хороший пример привычки описывается как конкретное действие, которое можно уложить в одно предложение:

## __Я буду [ДЕЙСТВИЕ] в [ВРЕМЯ] в [МЕСТО]__

За каждую полезную привычку необходимо себя вознаграждать или сразу после делать приятную привычку.
Но при этом привычка не должна расходовать на выполнение больше двух минут.

Чем отличается полезная привычка от приятной и связанной?
Полезная привычка — это само действие, которое пользователь будет совершать и получать за его выполнение
определенное вознаграждение (приятная привычка или любое другое вознаграждение).

Приятная привычка — это способ вознаградить себя за выполнение полезной привычки.

### ___Настройки___

* Исключить одновременный выбор связанной привычки и указания вознаграждения.

* В модели не должно быть заполнено одновременно и поле вознаграждения, и поле связанной привычки. Можно заполнить
  только одно из двух полей.

* Время выполнения должно быть не больше 120 секунд.

* В связанные привычки могут попадать только привычки с признаком приятной привычки.

* У приятной привычки не может быть вознаграждения или связанной привычки.

* Нельзя выполнять привычку реже, чем 1 раз в 7 дней. Нельзя не выполнять привычку более 7 дней.

* На каждой странице вывода может быть по 5 привычек.

* Каждый авторизованный пользователь имеет доступ только к своим привычкам.

* Пользователь может видеть список публичных привычек без возможности их как-то редактировать или удалять.

* Для полноценной работы сервиса необходимо реализовать работу с отложенными задачами в мессенджере Телеграмм,
  для напоминания о том, в какое время какие привычки необходимо выполнять.

* Для проекта необходимо настроить CORS, чтобы фронтенд мог подключаться к проекту на развернутом сервере.

* Для реализации экранов силами фронтенд-разработчиков необходимо настроить вывод документации.
  При необходимости описать документацию вручную.

* Cоздайте отдельные контейнеры для сервисов в проекте: Django, PostrgeSQL, Redis, Celery.
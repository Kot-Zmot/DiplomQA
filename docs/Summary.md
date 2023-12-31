# Отчет по итогам автоматизации

## Проведенные мероприятия:

- в ходе ознакомления с веб-сервисом было осуществлено ручное тестирование функционала в целях составления плана автоматизации.
- по итогам ручного тестирования было запланировано автоматизирование тестовых сценариев.
- составлен [план автоматизации](https://github.com/Kot-Zmot/DiplomQA/blob/main/Plan.md).
- написаны необходимые классы для взаимодествия с элементами веб-сервиса и для управления тестовыми данными.
- произведена автоматизация сценариев.
- подключена и настроена система отчетов Allure.
- составлен [отчет](Report.md) по результатам проведения тестов.
- созданы [issue](https://github.com/Kot-Zmot/DiplomQA/issues) с описанием обнаруженных дефектов.


## Реализовавшиеся риски

- Ввиду отсутствия пояснительной документации о работе сервиса отсутствует однозначное понимание ожидаемых результатов в тестах
- Отсутствие у веб-элементов приложения тестовых атрибутов создало сложности с локаторами элементов


## Общий итог по времени

|                                              | Запланировано, ч | Потрачено, ч |                          Обоснование расхождения                          |
|:---------------------------------------------|:----------------:|:------------:|:-------------------------------------------------------------------------:|
| Настройка SUT                                |      12          |      9       |                                                                           |
| Разработка тест-плана                        |      10          |      10      |                                                                           |
| Создание автотестов и их запуск              |      80          |      120     | Большое кол-во времени занял поиск уникальных селекторов                  |
| Создание баг-репортов                        |      10          |      12      | Доп время было потрачено на UI ошибки                                     |                                     |
| Отчёт по результатам автоматизации           |      10          |      6       |                                                                           |
| Настройка CI                                 |      8           |      -       | Не удалось корректно настроить CI. Т.к требование не было обязательным    |                                                                   |
|                                              |                  |              | для сдачи проекта, задача удалена.                                        |
|Всего                                         |     130          |      157     |                                                                           |


## Непроделанная работа
- Не была выполнена дополнительно интеграция с системой CI. - Для учета в дальнейшей работе
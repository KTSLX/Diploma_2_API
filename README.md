##  Дипломный проект. Задание 2: API тесты

### Автотесты для проверки программы заказа бургеров в Stellar Burgers

###  Использованный стек технологий

* Pytest
* Requests
* Allure

###  Реализованные сценарии

Созданы API тесты для эндпоинтов: `.../auth/register`, `.../auth/login`, `.../auth/user`, `.../orders`
, `.../ingredients`.

###  Структура проекта

- `Diploma_2` - проект, содержащий тесты и вспомогательные файлы.
- `tests` - пакет, содержащий тесты, разделенные по классам: `test_create_user.py`, `test_login_user.py`
  , `test_update_user.py`, `test_create_order.py`, `test_get_orders.py`.

###  Запуск автотестов

**Установка зависимостей**

> `$ pip install -r requirements.txt`

**Запуск автотестов из корня проекта `Diploma_2` и создание HTML-отчета в Allure**

> `pytest tests\ --alluredir=allure_results`
> `allure serve allure_results`

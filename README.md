##  Diploma project. Task 2: API tests

### Autotests to check burgering order process of Stellar Burgers

###  Technology stack

* Pytest
* Requests
* Allure

###  Scenarios

API tests for handles: `.../auth/register`, `.../auth/login`, `.../auth/user`, `.../orders`, `.../ingredients`.

###  Project structure

- `Diploma_2` - project, containing tests and helpers.
- `tests` - directory with tests separated by classes: `test_create_user.py`, `test_login_user.py`, `test_update_user.py`, `test_create_order.py`, `test_get_orders.py`.

###  How to launch tests?

**installing requerements**

> `$ pip install -r requirements.txt`

**Launching autotests from the project-root directory `Diploma_2` and the HTML-report creation in Allure**

> `pytest tests\ --alluredir=allure_results`
> `allure serve allure_results`

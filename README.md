# Data of project budgets

--------

* Описание проекта
* Используемые технологии
* Запуск


Описание проекта
----------------

Данный проект является сведением трат бюджетов различных производственных проектов на зарплаты и премии сотрудникам за календарный год.
В проекте есть возможность:
* создать файл с 2 листами:
    * лист с пустой таблицей с актуальным списком сотрудников для заполнения зарплат и премий за календарный год;
    * лист с пустой таблицей с актуальным списком производственных проектов для заполнения бюджетов на начало года и распределения выделений премий.

Используемые технологии
-----------------------

| Python 3.11.1   |  
| Openpyxl 3.1.5  |

Запуск
------

Для начала необходимо сгенерировать файл выгрузки "Отчёт за текущий год" и положить его в директорию "./docs/"
Остаётся запустить файл main.py, находящийся в директории "/src/budget_projects_creater/"

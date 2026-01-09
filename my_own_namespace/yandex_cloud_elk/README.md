## Решение

Модуль:
https://github.com/cranberry511/my_own_collection/blob/1.0.0/my_own_namespace/yandex_cloud_elk/plugins/modules/my_own_module.py

1. Проверка module на исполняемость локально:
![Запуск module test](img/test.jpg)

2. Запуск module через single task playbook:
![Запуск playbook](img/run.jpg)

3. Проверка на идемпотентность:
![Запуск module test](img/test2.jpg)

4. Инициализация collection:
![Инициализация collection](img/create_collection.jpg)

5. Запуск playbook с использованием role:
![Запуск playbook](img/run_in_collection.jpg)

Ссылка на collection:
https://github.com/cranberry511/my_own_collection/tree/1.0.0

6. Установка collection из локального архива:
![Установка collection](img/unarchive.jpg)

Ссылка на архив:
https://github.com/cranberry511/my_own_collection/blob/1.0.1/my_own_namespace/yandex_cloud_elk/archive_collection/my_own_namespace-yandex_cloud_elk-1.0.0.tar.gz

7. Запуск single task playbook для проверки работы:
![Запустите single task playbook](img/unarchive_run_single.jpg)
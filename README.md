С чего начинается Linux?
Цель:
1)получить навыки работы с Git, Vagrant, Packer;
2)публиковать готовые образы в Vagrant Cloud.

Команды для запуска:
vagrant up  - запуск виртуальной машины с ОС CentOS 7
vagrant ssh - подключение к запущенной ВМ
uname -r    - проверка версии ядра в ОС на ВМ.

Особенности проектирования и реализации решения:
- Вместо CentOs 8 был использован CentOs 7 так как он более стабилен и у него больше репозиториев доступных в моём регионе.
- Ядро было обновлено из репозитория
- Проект загружен на Vagrant Cloud
- При создании был использован iso-образ размещеный локально, а не из интернета, так как есть проблемы с соединением. Данное решение было оптимальным.


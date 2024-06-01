# mysyslog
Проект mysyslog представляет собой библиотеку для логирования данных в разных форматах.

# Структура проекта
libmysyslog: основная библиотека для логирования.
libmysyslog-text: модуль для вывода логов в текстовом формате.
libmysyslog-json: модуль для вывода логов в формате JSON.
mysyslog-client: клиентское приложение для тестирования библиотеки.
mysyslog-daemon: демон, работающий в фоновом режиме и записывающий логи.

# Особенности
Поддерживаемые уровни журналирования: DEBUG, INFO, WARN, ERROR, CRITICAL.
Поддерживаемые форматы вывода: текстовый и JSON.

# Сборка проекта с использованием Makefile
make all: собирает все компоненты.
make clean: удаляет все временные и объектные файлы, возвращая проект к исходному состоянию.
make deb: создает deb-пакет для программы.

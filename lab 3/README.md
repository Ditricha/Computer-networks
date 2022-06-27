# Задание
Разработать клиент-серверное приложение на основе сетевых сокетов и протокола TCP, представляющее http-сервер версии http 1.1 с ограниченным функционалом.

http сервер должен обрабатывать как минимум GET-запросы (в формате специальных TCP пакетов) и предоставлять статическую информацию (html-страницы, файлы) клиенту.

Разработать http-клиент для проверки данного сервера с помощью GET-запросов.

Дополнительно: предусмотреть многопоточную обработку соединений. Потоки для соединений выделяются из пула потоков динамически.

Реализовывать полный набор методов HTTP не нужно.

Использовать язык C/С++.
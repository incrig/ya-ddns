# ya-ddns
DDNS Yandex

# Что нужно?
- ОС — Linux
- Установлен curl
- IP — белый, хоть и динамический (узнать у провайдера)
- Маршрутизатор настроен на проброс нужного порта до компьютера. В ADSL-модемах это названо «Виртуальный сервер». В маршрутизаторах может быть названо «Проброс» или «Перенаправление». По модели маршрутизатора/модема яндекс/гугл найдёт информацию, как это настроить.
- У вас есть доменное имя делегированное на DNS яндекса.

# Как пользоваться?
- Сохраните файл ya-ddns в любой удобной директории, желательно чтобы путь был латиницей.
- Добавьте запуск скрипта в Cron, через каждые 14400 секунд, или укажите свой интервал в скрипте и в Cron.

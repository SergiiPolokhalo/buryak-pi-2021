# buryak-pi-2021
FPGA based Buryak

Первая ошибка на плате звука , у микросхемы U7 (мост UART) нет соединения между 7 и 8 ножками
Вторая ошибка у компаратора U10 отсутствует подтяжка к питанию на выходе, нужно между 7 и 8 ножками U10 запаять резистор 1к 0603/0402

В герберах RC1.1 исправлено
добавлены герберы под китайский SD холдер

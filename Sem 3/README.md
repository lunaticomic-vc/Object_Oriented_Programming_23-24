Записки:

Форматирания изход не цели да интерпретира информацията като един байт
Синхронизация: Вместо програмата да моли за достъп до файла всеки път, операциите се извършват в буфер. "Изсипването" на файла се извършва чрез .flush()

close() извиква flush() автоматично

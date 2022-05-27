программа для умножения точки кривой на скаляр.
задаётся только скаляр.

остальные параметры кривой следующие:
p = FFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFF43
a = FFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFFF40
b = 77CE6C1515F3A8EDD2C13AABE4D8FBBE4CF55069978B9253B22E7D6BD69C03F1
gx = 0
gy = 6BF7FC3CFB16D69F5CE4C9A351D6835D78913966C408F6521E29CF1804516A93

Вычисление точки происходит по методу double-and-add

Так как по стандарту числа вычисляются в 16-тирчиной системе формата LITTLE Endian, а программе нужны числа в формате BIG Endian, поэтому необходимо их конвертировать с помощью конвертера
конвертер: http://www.save-editor.com/tools/wse_hex.html#littleendian

примерное время выполнения - 15-30 секунд
во время выполнения программа не реагирует ни на какие действия
страницца будет доступна по адресу  http://127.0.0.1:3000/

2.3	Для линейного конгруэнтного генератора чисел (https://ru.wikipedia.org/wiki/Линейный_конгруэнтный_метод) реализовать алгоритм вычисления последующего числа по четырем предыдущим.
Считать параметр m не более 65535. Например, есть 4 числа : 157;  5054; 25789; 13214
Следующим за этими числами будет число 16605.

2.4	Необходимо сформировать звуковой стереосигнал для которого направление на источник меняется по окружности относительно наблюдателя. В качестве метода формирования использовать метод Interaural time difference
(https://courses.washington.edu/psy333/lecture_pdfs/Week9_Day2.pdf).
Расстояние между ушами 20.4 см. Скорость звука 340.29 м/c. 
Расстояние до источника и скорость движения сделать управляемыми параметрами.

2.6	Реализовать простой синтезатор частот.
Использовать алгоритм Карплуса-Стронга
(https://en.wikipedia.org/wiki/Karplus%E2%80%93Strong_string_synthesis).
Входом является набор частот в звуковом диапазоне, частота дискретизации, длительность в секундах.
Выходом является сигнал, который допустимо записать в файл либо вывести на звуковую карту.
При записи в файл привести отсчеты к формату int16.
Любые модификации, дополнительные алгоритмы, параметры (коэффициент затухания и т.д.) и интерфейс остаются на усмотрение соискателя и приветствуются.

2.7	Реализовать в matlab метод МНК (https://ru.wikipedia.org/wiki/Метод_наименьших_квадратов) для конечного набора значений, используя полином 5 степени, без использования стандартных функций lsqcurvefit() или polyfit(). 
На графике должны отображаться заданные точки и аппроксимирующая их функция. Приложить скриншоты графиков.

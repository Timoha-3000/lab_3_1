Лабораторная работа 3.
Создание однонаправленной нейронной сети
с помощью нейронно-сетевого инструментария MATLAB.
Цель занятия – продемонстрировать основные этапы реализации нейронно-сетевого
подхода для решения тестовой задачи с использованием нейронно-сетевого
инструментария пакета MATLAB.
Можно выделить 5 основных этапов:
1. Подготовка данных для тренировки сети.
2. Создание сети.
3. Обучение сети.
4. Тестирование сети
5. Моделирование сети. (Использование сети для решения поставленной задачи

6. В качестве примера рассмотрим следующую задачу:
Задан массив, состоящий из нескольких значений функции y = c*exp(-((x-a).^2/s))
интервале (0,1). Создать нейронную сеть прямого распространения (англ. feedforward
neural network) (многослойный перцептрон), что при вводе значений функции на входы
сети на выходах получались бы значения параметров
C, A, S .

Задание.
1. Исследовать влияние шума в исходных данных на результаты обучения
нейронной сети. Для этого к исходному массиву данных прибавить случайные
числа из диапазонов (0 – 0.01; 0 – 0.05; 0 – 0.1; 0 -0.2). Провести процедуру
обучения и протестировать сеть.
2. Сформировать исходный массив и массив эталонов из случайных чисел и
провести обучение сети. Прокомментировать результаты.

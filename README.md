# Visualization-with-B-splines

В репозитории представлено 2 файла с кодами из дипломного проекта "Визуализация многомерных данных с использованием B-сплайнов на C#", 
выполненного в среде Window Framework с помощью Window Forms на языке программирования C#.   

Form1 заключает в себе код для первой формы проекта - "Загрузка данных" с двумя полями - для загрузки таблицы из файлов в форму и 
выбора из загруженной таблицы строк для дальнейшей визуализации, а также расчета коэффициентов для построения графика 
и масштабирования значений.

Form2 содержит код для второй формы с построенным графиком: по оси х откладываются признаки, по оси y - отмасштабированные значения 
в диапазоне [0;1]. Одному визуализируемому объекту (одной n-мерной точке) соответствует один B-сплайн, построенный по контрольным точкам
значений признаков.
# Search-for-similar-pictures

## Данный проект предназначен для реализации задачи поиска похожих изображения для запрошенного изображения по собранному датасету цветов из 3-х разных источников.   
Он включает в себя:
- архив с датасетом;
- jupyter notebook с реализацией основных подходов к решению данной задачи;
- Сохранённую модель, обученную в процессе решения данной задачи, для воспорсизведения полученных результатов.

Для решения данной задачи было рассмотренно несколько подходов:
- обучения своей модели свёрточной сети, извлечения из неё признаков и поиск похожих изображений на основе "расстояния" или другой модели классического ML;
- использование предобученной модели свёрточной сети и последующая класстеризация на основе полученных признаков из модели;
- Использование библиотеки CV и алгоритма (метода) SIFT.

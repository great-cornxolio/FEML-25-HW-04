# Домашнее задание «Проблема качества данных»
Нетология. Курс: Feature Engineering (FEML-25). Программа: "Data Scientist: с нуля до middle"
___

Цель: применить на практике методы по оценке качества данных.

### Описание задания:
В домашней работе необходимо провести очистку данных на примере датасета [train.csv](https://github.com/great-cornxolio/FEML-25-HW-04/blob/main/train.csv) с информацией о пассажирах корабля Титаник. На полученных данных обучите модель классификации, с целевым признаком Survived (1 – пассажир выжил, 0 – погиб). Обучите модель на необработанных данных и посчитайте метрику качества. Проведите очистку данных. Обучите модель на данных после обработки, посчитайте метрику качества. Сравнить полученные результаты. Значение метрики должно улучшиться.

### Этапы работы:
1. Получите и загрузите данные.
2. Удалите все пропущенные значения и категориальные переменные. Обучите модель. Выберете и посчитайте метрику качества.
3. Снова загрузите полные данные.
4. Удалите признаки, которые логически не нужны для построения модели. Обоснуйте.
5. Проверьте данные на наличие пропущенных значений.
- Посчитайте, какой процент данных будет потерян, если просто удалить пропуски.
- Заполните пропуски: средним значением; константой; классом, указывающим на то, что значение было пропущено; случайным числом. Для разных признаков используйте подходящий метод. Можно не использовать все перечисленные методы.
6. Категориальные переменные переведите в цифровые значения. Можно использовать pd.get_dummies, preprocessing.LabelEncoder. Старайтесь не использовать для этой задачи циклы.
7. Проверьте данные на наличие выбросов.
- Удалите выбросы, если считаете это целесообразным. Обоснуйте.
8. Постройте 1-2 графика на выбор. Визуализация должна быть основана на исследуемых данных и быть полезной (из графика можно сделать вывод об особенностях датасета/класса/признака)
9. Попробуйте математически преобразовать признак Age.
10. Обучите ту же модель, что в п. 2 на преобразованных данных. Посчитайте ту же, что в п. 2 метрику.
11. Сформулируйте выводы по проделанной работе.
- Кратко опишите какие преобразования были сделаны и почему.
- Сравните метрики моделей из п. 2 и п. 10.
- Напишите свое мнение о целесообразности работы с данными при построении моделей машинного обучения. Нужно ли аналогичным образов исследовать и дополнять действительно большие данные?

[Решение](https://github.com/great-cornxolio/FEML-25-HW-04/blob/main/FEML_25_HW_04.ipynb)

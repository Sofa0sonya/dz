Проект 1. Исследование резюме с портала HeadHunter

Содержание:

1. Введение
Компания HeadHunter стремится создать модель, которая автоматически определит приблизительный уровень заработной платы, соответствующий пользователю, на основе предоставленной им информации. Прежде чем приступить к построению модели, данные необходимо обработать, изучить и очистить. Это является целью данного проекта.

2. Описание задачи
Проект состоит из четырех частей: базовый анализ структуры данных, преобразование данных, разведывательный анализ и очистка данных. Каждая часть включает блоки практических заданий, которые выполнялись в Jupyter Notebook.

Требования к оформлению решения в ноутбуке:

- Использование только Jupyter Notebook.
- Соблюдение шаблона ноутбука.
- Выполнение каждого задания в отдельной ячейке.
- Использование только изученного материала: переменные, основные структуры данных, циклы, функции, библиотеки numpy, pandas, matplotlib, seaborn, plotly.
- Читаемый и понятный код с соблюдением PEP 8.
- Оформление графиков в соответствии с правилами визуализации данных.
- Выводы к графикам в формате Markdown.

3. Описание данных
В проекте используется база резюме, загруженная с портала поиска вакансий hh.ru. Датасет содержит 44744 анонимизированных записей по 12 признакам, включая информацию о поле, возрасте, ожидаемой заработной плате, желаемой должности, городе проживания, готовности к переезду, занятости, графике работы, опыте работы, месте работы, образовании, дате и времени обновления резюме, а также наличии автомобиля.

4. Результат
Файл с решением: Project_1.ipynb. Для воспроизводимости кода можно использовать requirements.txt.

5. Выводы
В данном проекте было проведено исследование и очистка данных на примере датасета с резюме соискателей с портала hh.ru. Было выполнено преобразование данных, формирование новых информативных признаков и удаление избыточных данных. Также проведено исследование зависимостей с использованием визуализации с помощью библиотек matplotlib, seaborn и plotly. Осуществлена очистка данных путем удаления дубликатов, обработки пропущенных значений и устранения выбросов.

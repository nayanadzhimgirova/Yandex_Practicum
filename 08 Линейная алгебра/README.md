**Описание проекта**: Нужно защитить данные клиентов страховой компании «Хоть потоп». Разработать такой метод преобразования данных, чтобы по ним было сложно восстановить персональную информацию. Обосновать корректность его работы.
Нужно защитить данные, чтобы при преобразовании качество моделей машинного обучения не ухудшилось. Подбирать наилучшую модель не требуется.

**Навыки и инструменты**: Python, NumPy, Scikit-learn

**Выводы**:
- Я изучила данные и разделила их на признаки и целевой признак. В данных 5000 строк, 4 признака и один целевой признак.
- Сгенерировала рандомную матрицу и умножила на неё признаки. Обучила модели линейной регрессии на данных до и после преобразования и сравнила их качество метрикой R2. Метрика не изменилась, значит, умножение данных на рандомную обратимую матрицу не меняет качество обучения.
- Метод преобразования данных - умножение на рандомную обратимую матрицу.

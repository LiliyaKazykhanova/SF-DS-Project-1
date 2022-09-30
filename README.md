# SF-DS-Project-1
## Проект 1. Анализ вакансий на hh.ru
Ссылка для загрузки датасета: https://drive.google.com/uc?export=download&confirm=no_antivirus&id=1RklOSUpvnQ-d4hfsIV17YVjHycbXTwbF

### Оглавление
[1. Исследование структуры данных](https://github.com/LiliyaKazykhanova/SF-DS-Project-1/blob/main/README.md#Исследование-структуры-данных)

[2. Преобразование данных](https://github.com/LiliyaKazykhanova/SF-DS-Project-1/blob/main/README.md#Преобразование-данных)

[3. Исследование зависимостей в данных](https://github.com/LiliyaKazykhanova/SF-DS-Project-1/blob/main/README.md#Исследование-зависимостей-в-данных)

[4. Очистка данных](https://github.com/LiliyaKazykhanova/SF-DS-Project-1/blob/main/README.md#Очистка-данных)

[5. Выводы](https://github.com/LiliyaKazykhanova/SF-DS-Project-1/blob/main/README.md#Выводы)

#### Исследование структуры данных
- Вывод первых(/ последних) строк для визуальной оценки структуры dataframe;
- Оценка размерности данных;
- Получение информации о столбцах: индексы, названия, количество, число непустых значений, кол-во оперативной памяти в МБ;
- Получение описательной статистики (анализ данных типа object).

:arrow_up:[к оглавлению](https://github.com/LiliyaKazykhanova/SF-DS-Project-1/blob/main/README.md#Оглавление)

#### Преобразование данных
- "Образование и ВУЗ" -> "Образование" с 4 категориями уровней образования;
- "Пол, возраст" -> "Пол" (категории М и Ж) и "Возраст";
- "Опыт работы" -> "Опыт работы (месяц)";
- "Город, переезд, командировки" -> "Город", "Готовность к переезду", "Готовность к командировкам";
- "Занятость" и "График" -> признаки-мигалки для каждого формата занятости и графика (10 категорий) (One Hot Encoding);
- "ЗП" -> "ЗП (руб)".

#### Исследование зависимостей в данных
- Исследование распределения признака "Возраст";
- Исследование распределения признака "Опыт работы (месяц)";
- Исследование распределения признака "ЗП (руб)";
- Исследование зависимости медианной желаемой ЗП от уровня "Образования";
- Исследование распределения желаемой ЗП в зависимости от города проживания соискателя;
- Исследование зависимости медианной желаемой заработной платы от признаков "Готовность к переезду" и "Готовность к командировкам";
- Исследование зависимости медианной желаемой заработной платы от Возраста и Образования;
- Исследование зависимости "Опыта работы (в годах)" от "Возраста";
- Исследование зависимости уровня желаемой заработной платы от города проживания соискателя и его готовности к переезду;
- Исследование зависимости медианной желаемой заработной платы от "Образования" и "Пола".

#### Очистка данных
- Определение числа полных дубликатов и их удаление;
- Вывод информации о числе пропусков в столбцах;
- Заполнение/ удаление пропущенных значений в столбцах;
- Очистка данных вручную: удаление записей с несоответствующим условию уровнем "ЗП (руб)";
- Очистка данных вручную: удаление записей с несоответствующим условию значением "Опыт работы (месяц)";
- Исследование распределения признака "Возраст" в логарифмическом масштабе с помощью метода 3х сигм.

#### Выводы

:arrow_up:[к оглавлению](https://github.com/LiliyaKazykhanova/SF-DS-Project-1/blob/main/README.md#Оглавление)

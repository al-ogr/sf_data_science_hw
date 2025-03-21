# Проект 2. Исследование данных HR-агентства

## Оглавление  
[1. Описание проекта](README.md#Описание-проекта)  
[2. Какой кейс решаем?](README.md#Какой-кейс-решаем)  
[3. Краткая информация о данных](README.md#Краткая-информация-о-данных)  
[4. Результаты](README.md#Результаты)

### Описание проекта
Проведение исследования для HR-агентства, изучающего тренды на рынке труда в IT, на основе данных о зарплатах в сфере Data Science за 2020–2022 годы.

:arrow_up:[к оглавлению](README.md#Оглавление)


### Какой кейс решаем?    
Исследуйте данные и сделайте выводы по полученным результатам. Подкрепите свои рассуждения и выводы визуализациями и с помощью статистического тестирования проверьте, являются ли выводы статистически значимыми.

**Задания:**  
1. Выяснить, какие факторы влияют на зарплату специалиста Data Scientist.

2. Ответить на ключевые вопросы HR-агентства:
    - Наблюдается ли ежегодный рост зарплат у специалистов Data Scientist?
    - Как соотносятся зарплаты Data Scientist и Data Engineer в 2022 году?
    - Как соотносятся зарплаты специалистов Data Scientist в компаниях различных размеров?
    - Есть ли связь между наличием должностей Data Scientist и Data Engineer и размером компании?

3. Продемонстрируйте использование разных тестов для проверки статистической значимости сделанных выводов:
    - тесты для количественного признака:
        - для одной выборки;
        - для двух выборок;
        - для нескольких выборок;
    - тест для категориальных признаков..

**Метрика качества**  
1. Загрузка и обработка данных:
    - Студент корректно загрузил данные.
    - Студент проверил датасет на наличие пропусков и дубликатов, а также на корректность типов данных столбцов.
    - Студент определил в данных неинформативные признаки, которые не будут участвовать в исследовании.
    - Студент классифицировал все признаки на числовые и категориальные.
    - Студент нашёл основные статистические характеристики для каждого из признаков.
2. Разведывательный анализ данных:  
    - Визуальный анализ данных:  
        - Студент выполнил визуальный анализ данных.
        - Сделан базовый анализ для каждого признака, участвующего в исследовании:
            - для числовых признаков построены гистограммы, иллюстрирующие распределения;
            - для категориальных признаков определено количество записей для каждой категории и построены соответствующие визуализации.
        - Студент создал корректные визуализации, которые демонстрируют влияние каждого из признаков, участвующих в исследовании, на зарплату по всем наименованиям Data Scientist или на зарплату по всем должностям.
        - Студент на основе визуального анализа дал первичные ответы на поставленный в задании вопрос: «Какие факторы влияют на заработную плату?».   
    - Статистический анализ данных:  
        - В исследовании студент подтвердил или опроверг свои первичные гипотезы, полученные на этапе визуального анализа, с помощью статистических тестов:
        - Студент корректно сформулировал нулевые и альтернативные гипотезы на основе поставленных бизнес-вопросов.
        - Студент правильно выбрал статистический тест для каждой из гипотез, предварительно проверив условие его применения (там, где это необходимо):
            - проверка на нормальность;
            - проверка равенства дисперсий в группах.
        - Студент успешно протестировал данные, продемонстрировав владение различными статистическими тестами:
            - тесты для количественного признака:
                - для одной выборки;
                - для двух выборок;
                - для нескольких выборок;
            - тест для категориальных признаков.  
3. Соответствие выводов бизнес-вопросам:  
    - Студент привёл развёрнутые и обоснованные ответы по каждому вопросу:
        - Наблюдается ли ежегодный рост зарплат у специалистов Data Scientist?
        - Как соотносятся зарплаты Data Scientist и Data Engineer в 2022 году?
        - Как соотносятся зарплаты специалистов Data Scientist в компаниях различных размеров?
        - Есть ли связь между наличием должностей Data Scientist и Data Engineer и размером компании?
    - Представленные выводы корректны и соответствуют результатам, полученным в ходе статистического анализа.
4. Дополнительное исследование:
    - Студент самостоятельно корректно сформулировал минимум две дополнительных бизнес-гипотезы о влиянии факторов на заработную плату специалистов и для каждой гипотезы:
        - представил визуальный анализ данных;
        - произвёл статистическое тестирование;
        - сделал верные, соответствующие бизнес-вопросам выводы по полученным результатам.
5. Оформление исследования:
    - Студент качественно оформил решение задачи:
    - Описана постановка задачи.
    - На протяжении всего исследования прослеживается логика, ноутбук имеет понятную структуру, разделён на части заголовками.
    - Есть промежуточные выводы.
    - Все визуализации имеют подписи к осям и заголовки и соответствуют стандартам оформления.
    - Сделан финальный вывод по исследованию.
    - Код студента понятный, оформлен по стандартам PEP-8 и сопровождён комментариями.

**Что практикуем**  
Проведение визуального анализа данных.  
Проведение статистического анализа данных.  
Программирование на python.  
Формирование отчета.

:arrow_up:[к оглавлению](README.md#Оглавление)

### Краткая информация о данных
Данные о зарплатах в сфере Data Science за 2020–2022 годы 
[ds_salaries.csv](https://lms.skillfactory.ru/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block@ds_salaries.zip)
  
:arrow_up:[к оглавлению](README.md#Оглавление)

### Результаты:  
В ходе выполнения задания сформирован отчет в формате .ipynb с применением библиотеки визуализации данных Plotly, проведен визуальный анализ данных, полученные выводы подтверждены или опровергнуты в результате проведения статистического анализа.

:arrow_up:[к оглавлению](README.md#Оглавление)
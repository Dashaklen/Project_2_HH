# Проект: Рекомендательная модель для вакансий Data Scientist

### Оглавление

[Описание проекта](#описание-проекта)  
[Этапы проекта](#этапы-проекта)  
[Структура проекта](#структура-проекта)  
[Используемыебиблиотеки](#используемые-библиотеки)
[Этапы анализа](#этапы-анализа)  
[Заключительные выводы](#заключительные-выводы)  
[Установка и использование](#установка-и-использование)  

### ***Описание проекта***
Этот проект направлен на подготоку данных для создания модели машинного обучения, которая будет рекомендовать вакансии клиентам кадрового агентства, претендующим на позицию Data Scientist. В рамках работы над проектом мы проведем детальный анализ данных, чтобы понять их структуру и соответствие целям нашей модели.

:arrow_up:[к оглавлению](#оглавление)

### Этапы проекта

Проект включает в себя несколько этапов, каждый из которых будет проанализирован и оформлен в Jupyter Notebook:

1. **Знакомство с данными**: Изучение структуры базы данных и ознакомление с доступными таблицами.
2. **Предварительный анализ данных**: Оценка качества, объема и распределения данных.
3. **Детальный анализ вакансий**: Исследование различных вакансий с акцентом на их характеристики и требования.
4. **Анализ работодателей**: Изучение компаний, предлагающих вакансии, и их репутации.
5. **Предметный анализ**: Выявление навыков и технологий, востребованных на рынке труда для Data Scientist.

:arrow_up:[к оглавлению](#оглавление)

### ***Структура проекта***

- [Project_2.ipunb](https://github.com/Dashaklen/Project_2_HH/blob/master/Project_2%20.ipynb): Jupyter ноутбук с анализом данных.
- [reqirements.txt](https://github.com/Dashaklen/Project_2_HH/blob/master/requirements.txt): Зависимости
- [README.md](https://github.com/Dashaklen/Project_2_HH/blob/master/README.md): Описание проекта.'

:arrow_up:[к оглавлению](#оглавление)

### Используемые библиотеки

Для работы с проектом потребуется установить следующие библиотеки:

- `pandas` - для работы с данными.
- `numpy` - для числовых расчетов.
- `matplotlib` и `seaborn` - для визуализации данных.
- `sqlalchemy` - для работы с базой данных.
- Другие необходимые библиотеки, указанные в файле requirements.txt

:arrow_up:[к оглавлению](#оглавление)

### Этапы анализа
Проект включает в себя несколько ключевых этапов, каждый из которых направлен на тщательное понимание данных и подготовку к созданию модели машинного обучения:

1. **Знакомство с данными**:
   - Изучение структуры базы данных и доступных таблиц в схеме `public`.
   - Определение ключевых полей и их типов данных, а также количества доступных записей.
   - Первичная визуализация данных для понимания общих характеристик.

2. **Предварительный анализ данных**:
   - Проверка на наличие пропущенных значений и аномалий в данных.
   - Оценка распределения данных по ключевым признакам (например, зарплата, опыт работы, навыки).
   - Применение методов описательной статистики для понимания основных характеристик данных.

3. **Детальный анализ вакансий**:
   - Анализ каждого из аспектов вакансий, таких как требования, навыки, опыт, и уровень образования.
   - Выявление зависимости между различными характеристиками вакансий и их популярностью.
   - Классификация вакансий по категориям и сравнение данных между различными типами вакансий.

4. **Анализ работодателей**:
   - Изучение компаний-работодателей, предлагающих вакансии, и их репутации на рынке труда.
   - Оценка корреляции между характеристиками работодателей (например, размер компании, отрасль) и предлагаемыми вакансиями.
   - Анализ отзывов сотрудников и рейтингов компаний.

5. **Предметный анализ**:
   - Выявление актуальных навыков и технологий, востребованных для позиций Data Scientist на основе собранных данных.
   - Определение ключевых факторов, влияющих на привлекательность вакансий для потенциальных кандидатов.
   - Формулирование рекомендаций по улучшению вакансий и повышению их привлекательности.

:arrow_up:[к оглавлению](#оглавление)

### Заключительные Выводы:
Анализ рынка вакансий в области Data Science показывает, что в этой сфере сохраняется высокая конкуренция и очень маленкое число позиций для начинающих специалистов. Изученные данные подчеркивают важность опыта и наличия специфических навыков, таких как программирование на Python и работа с базами данных SQL, для повышения вероятности трудоустройства.

**Основные выводы**:

1. Высокая конкуренция на рынке труда требует от соискателей наличия большого опыта и определенных навыков. Невозможность получения работы без предварительного опыта ставит под сомнение возможности для входа в профессию, что может быть проблемой для молодых специалистов.

2. Ключевыми навыками для успешной карьеры в Data Science остаются программирование на Python, знание SQL и основные концепции машинного обучения. Поскольку технологии продолжают развиваться, навыки работы с современными фреймворками, такими как PyTorch и TensorFlow, становятся всё более актуальными.

3. Наличие вакансий с полным днём, удаленной работой и гибким графиком свидетельствует о том, что компании адаптируют свои предложения к потребностям соискателей, что, в свою очередь, может повысить их привлекательность как работодателей.

4. Доминирование крупных городов, таких как Москва и Санкт-Петербург, в количественном выражении вакансий указывает на необходимость развития трудовых ресурсов в других регионах, чтобы помочь обеспечить равномерное распределение возможностей между городами.

В целом, для успешной карьеры в Data Science кандидатам необходимо сосредоточиться на приобретении специализированных навыков, активно участвовать в обучающих программах и наращивать опыт работы, чтобы увеличить свои шансы. Работодателям стоит рассмотреть возможность создания более доступных вакансий для новичков и программ стажировок, что поможет обогатить рынок труда новыми талантливыми специалистами и укрепить свою позицию как желаемого работодателя.

:arrow_up:[к оглавлению](#оглавление)

### Установка и использование

1. Клонируйте репозиторий:
   git clone [https://github.com/Twi1ightFox/Project_2_HH.git](https://github.com/Twi1ightFox/Project_2_HH)
2. Настройка подключения к базе данных
Для подключения к базе данных вам необходимо создать файл `.env` в корневой директории проекта. Пример содержимого:

```python
DBNAME='project_sql'
USER='skillfactory'
PASSWORD='ваш_пароль'
HOST='ваш_host'
PORT=5432
```

3. Установка pyton-dotenv
Для загрузки переменных из файла `.env` установите библиотеку `python-dotenv`:

```bash
pip install python-dotenv
```

Не забудьте добавить файл `.env` в ваш `.gitignore`, чтобы он не попал в репозиторий.

4. Установить необходимые библиотеки:
   pip install -r requirements.txt
   
5. Запустить Jupyter notebook для просмотра и запуска анализа.

:arrow_up:[к оглавлению](#оглавление)


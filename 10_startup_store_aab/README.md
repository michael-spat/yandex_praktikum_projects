# Проект "Анализ пользовательского поведения в мобильном приложении"
- **Задача**: на основе данных использования мобильного приложения для продажи продуктов питания проанализировать воронку продаж, а также оценить результаты A/A/B-тестирования.  

- **Описание проекта**: В данном проекте мной были изучены принципы событийной аналитики. Я построил воронку продаж, исследовал путь пользователей до покупки. Проанализировал результаты A/B-теста введения новых шрифтов. Сравнил 2 контрольных группы между собой, убедился в правильном разделении трафика, а затем сравнил с тестовой группой. Выявлено, что новый шрифт значительно не повлияет на поведение пользователей.

- **Набор данных**: датасет с данными об объявлениях сервиса и следующими столбцами:
    - `EventName` - наименование события,
    - `DeviceIDHash` - id пользователя,
    - `EventTimestamp` - временная метка пользователя,
    - `ExpId` - номер эксперимента для теста, где 246 и 247 - метки контрольных групп, а 248 - тестируемой.

- **Библиотеки**: `pandas`, `Matplotlib`, `Seaborn`, `NumPy`, `SciPy`

- **Краткие выводы по проекту**:
    - Данные за актуальный период - 2 недели;
    - Воронка приложения включает 5 событий: туториал, главный экран, карточки товаров, корзина, экран успешной покупки;
    - Высокая конверсия в покупку (47,7%), но спад конверсии в просмотр товара (38%);
    - Высокий показатель оттока на этапе корзины (18,7%);
    - Введение шрифта не привело к статистически значимым различиям в конверсии на всех этапах воронки.

- **Статус проекта**: завершен, планируется изменение визуализаций.
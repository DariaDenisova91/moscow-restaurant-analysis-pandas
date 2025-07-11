# moscow-restaurant-analysis-pandas

# Исследование рынка заведений общественного питания Москвы
## Задача: Провести анализ рынка общепита Москвы для инвесторов, планирующих открыть новое заведение (кафе, ресторан или бар).

## О проекте
Исследование основано на данных сервисов Яндекс Карты и Яндекс Бизнес (лето 2022). Анализ включает:

Распределение заведений по категориям и районам.
Соотношение сетевых/несетевых заведений.
Рейтинги, средние чеки и посадочные места.
Рекомендации для инвесторов.

## Данные
Использованы 2 датасета:

rest_info.csv — название, адрес, категория, рейтинг, сетевой статус, количество мест.
rest_price.csv — средний чек, цена чашки капучино.

## Этапы работы
Предобработка данных (пропуски, дубликаты, преобразование типов).
EDA с визуализацией (Matplotlib/Seaborn).
Ответы на ключевые вопросы (топ-15 сетей, корреляция рейтинга, цены по районам).

## Основные выводы
Категории: Больше всего кофеен и кафе, меньше всего — баров.
Сети: 80% заведений — несетевые, но в категории "фастфуд" доминируют сети.
Цены: Средний чек в центре выше на 30-50%.
Рекомендации: Открывать кофейню в ЦАО с ценником «выше среднего».

## Jupyter Notebook с анализом ()

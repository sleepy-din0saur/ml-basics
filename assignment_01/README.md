## ❓ problem 
задача представляет собой бинарную классификацию для предсказания закончится ли текущая сессия пользователя покупкой товара

## ℹ️ dataset
- источник - [kaggle: Online Shoppers Purchasing Intention Dataset](https://www.kaggle.com/datasets/imakash3011/online-shoppers-purchasing-intention-dataset)
- размер - 12330, 18 признаков (10 числовых и 8 категориальных)
- целевая переменная - Revenue (булевый тип: True - сессия завершилась покупкой, False иначе)

### 📖 Data Dictionary (Словарь данных)

| Feature (Признак) | Type (Тип) | Description (Описание) |
| :--- | :--- | :--- |
| Administrative | int64 | количество посещенных административных страниц. |
| Administrative_Duration | float64 | общее время, проведенное на административных страницах. |
| Informational | int64 | количество посещенных информационных страниц. |
| Informational_Duration | float64 | общее время на информационных страницах. |
| ProductRelated | int64 | количество посещенных страниц, связанных с товарами. |
| ProductRelated_Duration | float64 | общее время на страницах с товарами. |
| BounceRates | float64 | процент посетителей, которые зашли на страницу и сразу ушли (отказы). |
| ExitRates | float64 | процент просмотров страниц, которые были последними в сессии. |
| PageValues | float64 | средняя ценность страницы, которую посетитель просмотрел перед покупкой. |
| SpecialDay | float64 | близость времени посещения к особому дню (например, 8 марта). от 0 до 1. |
| Month | object | месяц посещения сайта (feb, mar, may, etc.). |
| OperatingSystems | int64 | идентификатор операционной системы пользователя. |
| Browser | int64 | идентификатор браузера пользователя. |
| Region | int64 | идентификатор географического региона пользователя. |
| TrafficType | int64 | идентификатор источника трафика (откуда пришел пользователь). |
| VisitorType | object | тип посетителя (returning_visitor, new_visitor, other). |
| Weekend | bool | является ли день посещения выходным. |
| Revenue | bool | [target] совершил ли пользователь покупку. |
## 🧰 approach
...

## 📈 results
...

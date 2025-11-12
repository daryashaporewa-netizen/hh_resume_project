# Анализ резюме из HeadHunter

Итоговый проект по курсу "Python для анализа данных".

## Состав репозитория
- **Основной ноутбук проекта:**  
  `Python_для_анализа_данных__Итоговый_проект__ВдовинаДН.ipynb`
- **Датасеты не загружены в GitHub (ограничение 25 МБ).**  
  По требованиям задания они хранятся на Google Drive.

### Ссылки на датасеты:

- [dst-3.0_16_1_hh_database.csv]([https://drive.google.com/file/d/1NjUwFTK32MkcascWiWntsxOznrI8gidl/view?usp=sharing](https://drive.google.com/file/d/1NjuUFTK32MkcacSiWVntsxOznrI8gidl/view?usp=sharing))
- [ExchangeRates.csv]([https://drive.google.com/file/d/1j19WEt5NUBWMy61fSNCOrcsF1IaD7gH/view?usp=sharing](https://drive.google.com/file/d/1jl9WEt5NUBWWNy61fSNC0rcsF1laD7gH/view?usp=drive_link))

## Как запустить проект
1. Скачайте датасеты по ссылкам выше.
2.  Поместите их в папку `/data/` **или измените путь в ноутбуке под своё расположение файлов.**
3.  . В ноутбуке укажите путь к датасетам в функции `pd.read_csv()`:
   ```python
   hh_data = pd.read_csv('ПУТЬ_К_ФАЙЛУ/dst-3.0_16_1_hh_database.csv', sep=';')
   rates = pd.read_csv('ПУТЬ_К_ФАЙЛУ/ExchangeRates.csv')
4. Откройте Jupyter Notebook и запустите проект.

## Что было сделано

- Исследование структуры данных  
- Очистка и преобразование данных    
- Анализ зарплат  
- Анализ навыков соискателей  
- Визуализации  
- Работа с внешними данными о курсах валют

## Используемые библиотеки

`pandas`, `numpy`, `matplotlib`, `seaborn`, `plotly`, `re`

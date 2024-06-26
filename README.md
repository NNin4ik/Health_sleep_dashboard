# Health_sleep_dashboard
Дашборд «Анализ зависимостей показателей сна от здоровья и образа жизни человека» <!-- описание репозитория -->
<!--Блок информации о репозитории в бейджах-->
![Static Badge](https://img.shields.io/badge/NNin4ik-Health_sleep_dashboard-Health_sleep_dashboard)
![GitHub top language](https://img.shields.io/github/languages/top/NNin4ik/Health_sleep_dashboard)
![GitHub Repo stars](https://img.shields.io/github/stars/NNin4ik/Health_sleep_dashboard)
![GitHub issues](https://img.shields.io/github/issues/NNin4ik/Health_sleep_dashboard)

![Logotype](./assets/night2.png)

<!--Описание проекта-->
## Описание проекта
Данный проект представляет собой многостраничный дашборд, состоящий из различных графиков, построенных на основе набора данных "Sleep Health and Lifestyle Dataset".

## Описание датасета 
Набор данных о здоровье, сне и образе жизни включает широкий спектр переменных, связанных со сном и повседневными привычками. Он содержит такие аспекты, как пол, возраст, род занятий, продолжительность сна, качество сна, уровень физической активности, уровень стресса, категория ИМТ, артериальное давление, частота сердечных сокращений, ежедневные шаги, а также наличие или отсутствие нарушений сна.
Ознакомиться с датасетом и скачать его можно [здесь](https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset)

## Содержание проекта 
1.	Страница «О проекте». На ней представлена основная информация о наборе данных, а также предоставлено описание страниц дашборда. 
2.	На странице «Образ жизни» представлено три графика, демонстрирующих, как качество сна зависит от образа жизни человека:
      * На пузырьковой диаграмме можно отследить зависимость качества сна от его продолжительности и уровня стресса человека.
      * Кольцевая диаграмма показывает, как количество пройденных за день шагов влияет на качество сна.
      * На линейном графике представлена зависимость качества сна от его продолжительности.
    Помимо этого, на странице присутствуют фильтры, на которых вы можете выбрать интересующие Вас показатели и посмотреть, как изменяются графики.  
3.	На странице «Здоровье» представлено три графика и два индикатора:
      * Половозрастная пирамида демонстрирует зависимость качества сна от возраста и пола человека.
      * Линейный график показывает зависимость продолжительности сна и давления.
      * Круговая диаграмм показывает процент людей с различными расстройствами сна (бессоница, апноэ).
      * Индикаторы показывают средний уровень стресса и среднюю оценку качества сна. 
    На данной странице также присутствуют фильтры по профессии и индексу массы тела. 

<!--Установка-->
## Установка
У вас должны быть установлены [зависимости проекта](https://github.com/NNin4ik/Health_sleep_dashboard#зависимости)

1. Клонирование репозитория 

```git clone https://github.com/NNin4ik/Health_sleep_dashboard```

2. Переход в директорию Health_sleep_dashboard

```cd Health_sleep_dashboard```

3. Создание виртуального окружения

```python -m venv venv```

4. Активация виртуального окружения

```source venv/Scripts/activate```

5. Установка зависимостей

```pip install dash pandas```
```pip install dash-bootstrap-components```
```pip install pandas plotly```

<!--Поддержка-->
## Поддержка
Авторы проекта: [Нина](https://github.com/NNin4ik), [Тимур](https://github.com/inte11ectua1). 

Если у вас возникли сложности или вопросы по использованию пакета, создайте 
[обсуждение](https://github.com/NNin4ik/Health_sleep_dashboard/issues/new/choose) в данном репозитории.

<!--зависимости-->
## Зависимости
Эта программа зависит от интепретатора Python версии 3.11 или выше. Если вы заметили, что он данное ПО можно запустить на версии ниже, или он не работает на какой-либо версии, то напишите в [поддержку](https://github.com/NNin4ik/Health_sleep_dashboard#поддержка) 

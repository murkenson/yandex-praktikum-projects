# Аналитик данных — Яндекс.Практикум

Этот репозиторий посвящен учебным проектам, которые я выполнила за время прохождения курса по «Анализу Данных» на [Яндекс.Практикуме](https://praktikum.yandex.ru/data-analyst/).




Программа обучения помогла мне научиться исследовать, обрабатывать и систематизировать данные, выявлять закономерности, делать предположения и четко сообщать важные выводы.

# Описание проектов

Номер проекта| Название проекта| Описание| Использованные библиотеки
:---------------|:-------------------|:---------------------------------------|:---------------------------
1|Исследование надежности заемщиков [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/14KW8ymCNu3t70-ySzsKXUANXgXJiGyTy?usp=sharing)| Определил, влияет ли семейное положение и количество детей на погашение кредита в срок. Использовал лемматизацию, категоризацию и последующий анализ групп клиентов.| ```pandas, pymystem3, Counter (from collections).```
2|Исследование объявлений о продаже квартир [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1nPwTk8VQ-Ui7CEwn-dH_7wu4bZ8jDflC?usp=sharing)|Провел исследовательский анализ рынка жилья, составил типовую выборку и на ее основании изучил влияние различных факторов на стоимость недвижимости. Установил параметры для определения рыночной стоимость объектов недвижимости, чтобы остлеживать аномалии и мошенническую деятельность на сайте он-лайн сервиса.|```pandas, matplotlib.pyplot. Визуализации: boxplot, histogram, scatterplot, line plot.```
3|Определение перспективного тарифа для телеком компании [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1LUwULQqgzBfSf2tEKeQsZMnJr6Q5XXXn?usp=sharing)| Подобрал типовые характеристики пользователей, исследовал использование ресурсов оператора, определил, какой тариф приносит больше денег, чтобы перераспределить бюджеты на рекламу.|```pandas, math, matplotlib.pyplot, stats from scipy, numpy. Визуализации: boxplot, histogram.```
4|Исследование рынка компьютерных игр [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1M1cVfj_ohYZmdevLL6cL9YJsxnLv1hR7?usp=sharing)|Провел исследовательский анализ данных о продажах игр, составил портрет пользователей из каждого региона, спрогнозировал приоритетные направления для продаж на следующий год.|pandas, matplotlib.pyplot, stats from scipy, numpy. Визуализации: boxplot, histogram, line plot, group bar, scatterplot.
5|Анализ бизнес-показателей данных Яндекс.Афиши [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1-orOjzhjUZ33cP_CkBOzFUs3o57ejR5T?usp=sharing)|Провел исследование и рассчитала метрики: DAU, WAU, MAU, sticky factor, Retention Rate, LTV, SAS, ROMI. Выяснил, как люди пользуются продуктом, когда они начинают покупать, сколько денег приносит каждый клиент, когда клиент окупается.|```pandas, matplotlib.pyplot, seaborn, numpy. Визуализации: boxplot, histogram, line plot, heatmap, group bar, stacked bar.```
6|Принятие решений в бизнесе на основе данных [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1O2gh4vlv6X1uC7f0j2P3IObbW5x6Zv3I?usp=sharing)|Приоритизировал гипотезы, проанализировала данные, полученные за время проведения А/В теста: кумулятивная выручка, средний чек и конверсия по группам. Проанализировал статистическую значимость с помощью критерия Манна-Уитни: конверсии, различий в среднем чеке между группами, сырыми и очищенными данными.|```pandas, matplotlib.pyplot, matplotlib.lines, numpy, datetime, scipy.stats.```
7|Анализ рынка заведений общественного питания Москвы [![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1lgMe1H6klw4H36xODGdAahA3t4G0XzVJ?usp=sharing)|Провел исследовательский анализ данных о заведениях общественного питания Москвы. Cделал общий вывод и дал рекомендации о виде заведения, количестве посадочных мест, а также районе расположения для открытия небольшого кафе.|```pandas, plotly.express, re.```
8|Анализ мобильного приложения продуктового магазина. Воронка продаж, А/А/В-тест[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/11J8bFPJjdfLRGACDlNroONI4UMZvH-7D?usp=sharing)|Изучил воронку конверсии, проанализировал все шаги, которые покупатель проходит до покупки, выявила вероятные проблемы. Исследовал результаты проведенного А/А/В-теста, чтобы выяснить, какой шрифт лучше.|```pandas, plotly.express, numpy, math, proportions_ztest from statsmodels.stats.proportion.```
9|Анализ взаимодействия пользователей с карточками Яндекс.Дзен|[Дашборд](https://public.tableau.com/app/profile/murad1841/viz/YandexZenAnalysisDashboard_16231755621970/sheet0) для менеджеров по анализу контента. Сгрегировал данные и сверстал дашборд с основными типами графиков и элементами управления. (в первоначальном варианте проект был выполнен на локальной машине с помощью dash, но позже я разобрался с Tableu.Public и разместила в сети в этом варианте). Подготовил [презентацию](https://docs.google.com/presentation/d/1-edFpQyjorAYpj0njkRX8cKD4uhDusc-IeCTPQybPAc/edit?usp=sharing) для клиента|```pandas, dash, dash_core_components, dash_html_components, dash.dependencies, datetime, plotly.graph_objs.```

<div align="center">


<a href="https://github.com/iampawan">
  <img align="left" alt="Pawan's Github" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/github.svg" />
</a>
<a href="https://t.me/imthepk">
  <img align="left" alt="Pawan's Telegram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/telegram.svg" />
</a>
<a href="https://instagram.com/codepur_ka_superhero/">
  <img align="left" alt="Pawan's Instagram" width="22px" src="https://cdn.jsdelivr.net/npm/simple-icons@v3/icons/instagram.svg" />
</a>
</div>
<br/>
<br/>
<br/>






![Diploma](https://drive.google.com/uc?export=view&id=1tFv6hM0jwUZlhKNiAZD-P7JuHNaPhx6D)

</span>



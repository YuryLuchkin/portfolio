# Портфолио: аналитик данных

## Обо мне

Здравствуйте! Меня зовут ``Юрий Лучкин``, я начинающий аналитик данных. 
``Мне 21. Я начал изучать IT посколку мне интересна эта сфера своей многогранностью``
В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.
<br>

## Навыки и технологии
- Инструменты анализа данных: ``SQL``, ``Excel``: 
- Языки программирования и библиотеки: ``Python``, ``Pandas``, ``math`` 
- Системы управления базами данных: ``MySQL``, ``PostgreSQL``
- Средства визуализации данных: ``PowerBi``, ``Matplotlib``, ``seaborn``
- Инструменты для машинного обучения: ``scikit-learn``, ``TensorFlow``

## Проекты
### <p> Проект 1: Калькулятор юнит-экономики онлайн-школы</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Задача №1</li>
  Учесть в калькуляторе корректировку планов маркетинга на расчётное количество студентов 
  <li>Задача №2.</li>
  Пересчитать план найма преподавателей 
</ol>

<p>Как решал: краткое описание решения (автореферат)<p>
<ol>
<li>Добавил в список параметров калькулятора показатель "Поправочный коэф-т на привлечение"</li>
<li>Установил значение этого показателя по умолчанию как 100% и добавил возможность изменять этот показатель для расчётного периода</li>
<li>Настроил динамический расчёт количества новых студентов за период с поправкой на этот коэффициент.</li>
<li>Просчитал сценарий, при котором планы маркетинга будут увеличены на 12%</li>
</ol>

[Проект №1](https://github.com/YuryLuchkin/portfolio/blob/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%20%E2%84%961.md)

<p>Выводы (итоги):<p>
<ol>
  <li>Итог №1</li>
  Обновленный лист с калькулятором + новое расчётное количество студентов
  <li>Итог №2</li>
  Обновлённый план по найму - с количеством новых преподавателей по месяцам
</ol>
<br> 

### <p> Проект 2: Калькулятор юнит-экономики онлайн-кинотеатра</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Задача №1</li>
  Посчитать юнит-экономику продукта и предложить сценарий по настройке параметров для выхода на 25%-ную маржинальность.
  <li>Задача №2.</li>
  Собрать визуализации основных бизнес-показателей.
</ol>

<p>Как решал: краткое описание решения (автореферат)<p>
  <ol>
<li>Собрал калькулятор юнит-экономики с его помощью рассчитал retention, LT, LTR, CAC маржинальность.
</ol>

[Проект №2](https://github.com/YuryLuchkin/portfolio/blob/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%20%E2%84%962.md)

<p>Выводы (итоги):<p>
<ol>
  <li>Итог №1</li>
  Калькулятор юнит-экономики с параметрами которые приводят к 25% маржинальности.
  <li>Итог №2</li>
  Подборка графиков которые демонстрируют базовые показатели бизнеса.
</ol>
<br>

### <p> Проект 3: Когортный анализ онлайн-кинотеатра с помощью SQL</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Задача №1</li>
  Для каждого партнера необходимо рассчитать, какой процент клиентов дошел до второй покупки, до третьей покупки и т. д.
</ol>

<p>Как решал: краткое описание решения (автореферат)<p>
С помощью оконной функции создал табличку на основе которой произвел расчеты

[Проект №3](https://github.com/YuryLuchkin/portfolio/blob/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%20%E2%84%963.md)

<p>Выводы (итоги):<p>
<ol>
  <li>Итог №1</li>
  Таблица которая дает понят сколько клиентов дошло до n-ой покупки у различных партнеров.
</ol>
<br> 

### <p>Проект 4: Построение витрины для модели машинного обучения в банке </p> 
<p>Что нужно было сделать:<p>
 <ol>
  <li>Задача №1</li>
  Написать скрипт, который сделает витрину
  </ol>
  
<p>Как решал: краткое описание решения (автореферат)<p>
С помощью оконных функций и подзапросов произвел расчеты и выбрал столбцы которые интересуют задачу

[Проект №4](https://github.com/YuryLuchkin/portfolio/blob/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%20%E2%84%964.md)

<p>Выводы (итоги):<p>
<ol>
  <li>Итог №1</li>
  Витрина для модели машинного обучения в банке
</ol>
<br> 

### <p>Проект 5: Моделирование изменения балансов студентов</p> 
<p>Что нужно было сделать:<p>
<ol>
<li>Задача №1</li>
Смоделировать изменение балансов студентов. Баланс — это количество уроков, которое есть у каждого студента.
<li>Задача №2.</li>
Создать визуализацию (линейную диаграмму) итогового результата. 
</ol>

<p>Как решал: краткое описание решения (автореферат)<p>
<ol>
Собрал данные по каждому пользователю с помощью CTE,<br>
найшел все изменения балансов, связанные с успешными транзакциями,<br>
создал CTE для хранения кумулятивной суммы количества пройденных уроков,<br>
создал CTE с вычисленными балансами каждого студента.<br>
</ol>

>Ссылка на проект

<p>Выводы (итоги):<p>
<ol>
  <li>Итог №1</li>
  Запрос, который собирает данные о балансах студентов за каждый прожитый ими день.
  <li>Итог №2</li>
  Визуализация итогового результата
</ol>

## Контактная информация
- Email: i@yura04.ru
- Личный сайт: https://t.me/ThisGuy869

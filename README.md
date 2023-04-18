# Портфолио: аналитик данных
## Обо мне 
Привет! Я Дарья Костюк, начинающий аналитик данных. 
<p>Ранее работала в сфере гостиничного бизнеса на позиции менеджера. Занималась оценкой эффективности систем онлайн-бронирования и контрагентов, корректировкой системы ценообразования и политики продвижения.
<p>Закончила магистратуру в РЭУ им. Г.В.Плеханова по направлению Экономика (профиль "Бизнес-аналитика"). Данное направление включает финансовый анализ, инвестиционный и инновационный анализ на основе бухгалтерской и финансовой отчетности компаний.
<p>Для изучения и освоения других инструментов и технологий анализа данных потребовалась проф. переподготовка на курсе "Аналитик данных".
В этом репозитории вы можете найти некоторые из моих проектов, выполненных во время обучения и практики.
<br>
  
## Навыки и технологии
- Инструменты анализа данных: ``SQL``, ``Excel``: 
- Языки программирования и библиотеки: ``Python``, ``Pandas``, ``math`` 
- Системы управления базами данных: ``MySQL``, ``PostgreSQL``
- Средства визуализации данных: ``PowerBi``, ``Matplotlib``, ``seaborn``
- Инструменты для машинного обучения: ``scikit-learn``, ``TensorFlow``
## Проекты
<p> Проект 1: Калькулятор юнит-экономики онлайн-школы</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Задача №1</li>
  <li>Задача №2.</li>
</ol>
<p>Как решала(-а): краткое описание решения (автореферат)<p>
> <a href="https://github.com/Skyproportfolio/data-analytics-5month/blob/main/Проект%20№1.xlsx">Ссылка на проект</a>
  (ссылка должна содержать демонстративные материалы: скриншоты, таблички, запросы, код. Работодатель должен иметь возможность быстро посмотреть результаты работы)
<p>Выводы (итоги):<p>
<ol>
  <li>Итог №1</li>
  <li>Итог №2</li>
</ol>
<br> 
<p> Проект 2: Калькулятор юнит-экономики онлайн-кинотеатра</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Задача №1</li>
  <li>Задача №2.</li>
</ol>
<p>Как решала(-а): краткое описание решения (автореферат)<p>
> <a href="https://drive.google.com/drive/folders/11HcEeqniyrCMjuwHZ0GLysX0A2SEv-_x">Ссылка на проект</a>
 (ссылка должна содержать демонстративные материалы: скриншоты, таблички, запросы, код. Работодатель должен иметь возможность быстро посмотреть результаты работы)
 
<p>Выводы (итоги):<p>
<ol>
  <li>Итог №1</li>
  <li>Итог №2</li>
</ol>
<br> 
<br> 
<p> Проект 3: Когортный анализ онлайн-кинотеатра с помощью SQL</p>
<p>Что нужно было сделать:<p>
<ol>
  <li>Задача №1</li>
  <li>Задача №2.</li>
</ol>
<p>Как решала(-а): краткое описание решения (автореферат)<p>
  
> <a href="https://drive.google.com/drive/folders/1wdD-mfSeIsHWgrMLJz8Tv_ClAuP_EAOQ?usp=sharing">Ссылка на проект</a>
(ссылка должна содержать демонстративные материалы: скриншоты, таблички, запросы, код. Работодатель должен иметь возможность быстро посмотреть результаты работы)
  <p>Выводы (итоги):<p>
<ol>
  <li>Итог №1</li>
  <li>Итог №2</li>
</ol>
<br> 
<p>Проект 4: Построение витрины для модели машинного обучения в банке </p> 
<p>Что нужно было сделать: Написать скрипт, который сделает витрину в соответствии с запрашиваемыми полями.<p>
  
<p>Как решала: Поля, в которых необходимо было предоставить бинарные значения, были вычислены при помощи простой конструкции case when. Такие показатели как доля данного кредита среди всех кредитов, суммарный объем кредитов выданных в рамках данного типа кредита, количество кредитов, выданных в данном городе и т.д. были получены применением агрегирующих оконных функций.<p>
  
> <a href="https://github.com/Kostiuk-Daria/My-portfolio/tree/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%204">Ссылка на проект</a>
 
 <p>Выводы (итоги):<p>
<ol>
  <li>Получена витрина для модели машинного обучения со всеми требуемыми полями.</li>
  <li>Оконные функции сильно упрощают жизнь аналитика. )))</li>
</ol>
<br> 
<p>Проект 5: Моделирование изменения балансов студентов для онлайн-школы</p> 
<p>Что нужно было сделать:<p>
<ol>
  <li>Создать запрос, который собирает данные о балансах студентов за каждый "прожитый" ими день.</li>
  <li>Смоделировать изменение суммарного баланса. Создать визуализацию результата. </li>
</ol>
<p>Имеющиеся данные: датасет по всем транзакциям (оплатам и начислениям бонусов) по каждому студенту; датасет по всем занятиям студентов, включающий id студента, дату, статус и тип занятия<p>
<p>Как решала: Решение осуществлялось при помощи CTE конструкций. Сначала были определены все даты "жизни" студента после его первой транзакции. Далее найдены все изменения балансов студентов, связанные с успешными транзакциями, и определен кумулятивный баланс по каждому студенту. Также найдено изменение баланса из-за прохождения уроков и рассчитаны кумулятивные показатели (с отрицательными значяениями). Суммированием баланса по транзакциям и баланса по прохождению уроков найден искомый баланс каждого студента за каждый "прожитый" им день. 

> <a href="https://github.com/Kostiuk-Daria/My-portfolio/tree/main/%D0%9F%D1%80%D0%BE%D0%B5%D0%BA%D1%82%205">Ссылка на проект</a>
<br>
  
 
 <p>Выводы (итоги):<p>
<ol>
  <li> Вопрос к инженерам: после вычисления баланса занятий для каждого студента на каждый день по некоторым студентам были обнаружены отрицательные значения баланса, чего по идее не должно быть. Необходимо проверить все ли транзакции отображаются по перечисленным юзерам.
</li>
  <li> По визуализации по скользящим средним видно, что и количество оплаченных уроков в день, и количество проведенных уроков в день растет, 
что говорит о развитии и увеличении масштабов деятельности. Однако накопленное значение суммы оплаченных уроков растет более быстрыми темпами, чем накопленное значение суммы проведенных уроков, что отражается в росте суммарного баланса всех учеников.
<p>Гипотеза 1. Проблема в данных - имеем не все данные по урокам.
<p>Гипотеза 2. Проблема в контенте/учителях - ученики бросают обучение, не использовав все оплаченные уроки, и уроки остаются висеть на счете.
</li>
</ol>

## Контактная информация
- Email: klepikovadarya@yandex.ru

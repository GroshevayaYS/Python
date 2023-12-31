Задание 8. Проверка гипотез

Инструкция:

Шаг 1.  Изучите материалы лекционных и практических занятий по темам раздела 4.

Шаг 2. Составьте и проверьте гипотезы о данных по предложенному датасету (Алгоритм выполнения представлен в практическом занятии по теме 4.4).

Шаг 3. Выполните анализ корреляции признаков  (Алгоритм выполнения представлен в практическом занятии по теме 4.4).

Шаг 4. Опубликуйте файл расширения ipynb на платформе.

# Описание данных
Каждый клиент описывается следующим набором признаков:
- `Возраст`, `Среднемесячный расход`, `Средняя продолжительность разговоров`, `Звонков днем за месяц`, `Звонков вечером за месяц`, `Звонков ночью за месяц`, `Звонки в другие города`, `Звонки в другие страны`, `Доля звонков на стационарные телефоны`, `Количество SMS за месяц`, `Дата подключения тарифа`.

## Примерный план по выполнению проекта

**Шаг 1.** Загрузка данных;

**Шаг 2.** Сформулировать и проверить следующие гипотезы
- клиенты чаще звонят днем или вечером по количеству звонков;
- клиенты чаще звонят днем или (вечером + ночью) по количеству звонков;
- клиенты больше звонили в 2019 году по сравнению с 2021 годом по количеству звонков.

**Шаг 3**. Построить матрицу корреляции для всех признаков, кроме `Дата подключения тарифа`.

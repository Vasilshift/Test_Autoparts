# Test_Sulution Autoparts T-SQL 

1) Создать таблицу сотрудников: ProductionResources
Колонки: id, Name
2) Создать таблицу заданий на набор: MaterialPicking
Колонки: id, LocationName, [MaterialName], [Quantity] [ProductionResource_id], RecordDate
ProductionResource_id - это id сотрудника таблицы ProductionResources
Необходима проверка на существование сотрудника при вставке его в таблицу наборов
3) Предоставить данные: Сколько наборов/пикингов, штук, время начала и окончания обработки наборов для каждого сотрудник за период времени.

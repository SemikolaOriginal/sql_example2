# sql_example2
В файле SQL Queries содержатся 25 пунктов с текстом заданий и ответами на них.
Все запросы предназначены для работы с БД HW-4-SQL.sql.
Ниже представлен список заданий:

1. Show a list the Company Name and Country for all Suppliers located in Japan or Germany.

2. Show a list of Product Name, Quantity per Unit and Unit Price for products with a Unit Price less than $7 but more than $ 4.

3. Show a list of Company Name, City and Country for Customers whose Country is USA and City is Portland OR Country is Canada and City is Vancouver.

4. Show a list the Contact Name and Contact Title for all Suppliers with a SupplierID from 5 to 8 (inclusive) and sort in descending order by ContactName.

5. Show a product name and unit price of the least expensive product (i.e. lowest unit price)?

6. Display Order Count by their Ship Country for all except USA for Shipped Date between May 4th and 10th 2015 whose Order Count is greater than 3.

7. Show a list of all employees with their first name, last name and hiredate (formated to mm/dd/yyyy) who are NOT living in the USA and have been employed for at least 5 years.

8. Show a list of Product Name and their 'Inventory Value' (Inventory Value = units in stock multiplied by their unit price) for products whose 'Inventory Value' is over 3000 but less than 4000.

9. Show a list of Products' product Name, Unit in Stock and ReorderLevel level whose Product Name starts with 'S' that are currently in stock (i.e. at least one Unit in Stock) and Unit in Stock is at or below the reorder level.

10. Show a Product Name, Unit Price for all products, whose Quantity Per Unit has/measure in 'box' that have been discontinued (i.e. discontinued = 1).

11. Show a list of Product Name and their TOTAL inventory value (inventory value = UnitsInStock * UnitPrice) for Supplier's Country from Japan.

12. Show a list country and their customer's count that is greater than 8.

13. Show a list of Orders' Ship Country, Ship City and their Order count for Ship Country 'Austria' and 'Argentina'. 

14. Show a list of Supplier's Company Name and Product's Product Name for supplier's country from Spain.

15. What is the 'Average Unit Price' (rounded to two decimal places) of all the products whose ProductName ends with 'T'?

16. Show a list of employee's full name (i.e. firstname, lastname), title and their Order count for employees who has more than 120 orders.

17. Show a list customer's company Name and their country who has NO Orders on file (i.e. NULL Orders).

18. Show a list of Category Name and Product Name for all products that are currently out of stock (i.e. UnitsInStock = 0).

19. Show a list of products' Product Name and Quantity Per Unit, which are measured in 'pkg' or 'pkgs' or 'jars' for a supplier’s country from Japan.

20. Show a list of customer's company name, their Order’s ship name and total value of all their orders (rounded to 2 decimal places) for customer's from Mexico. (value of order = (UnitPrice multiplied by Quantity) less discount).

21. Show a list of products' Product Name and suppliers' Region whose product name starts with 'L' and Region is NOT blank/empty.

22. Show a list of Order's Ship Country, Ship Name and Order Date (formatted as MonthName and Year, e.g. March 2015) for all Orders from 'Versailles' Ship City whose Customer's record doesn't exists in Customer table.

23. Show a list of products' Product Name and Units In Stock whose Product Name starts with 'F' and Rank them based on UnitsInStock from highest to lowest (i.e. highest UnitsInStock rank = 1, and so on). Display rank number as well.

24. Show a list of products' Product Name and Unit Price for ProductID from 1 to 5 (inclusive) and Rank them based on UnitPrice from lowest to highest. Display rank number as well.

25. Show a list of employees' first name, last name, country and date of birth (formatted to mm/dd/yyyy) who were born after 1984 and Rank them by date of birth (oldest employee rank 1st, and so on) for EACH country, i.e. Rank number should reset/restart for EACH country

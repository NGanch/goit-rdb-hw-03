# goit-rdb-hw-03
SELECT * FROM products;
![р1_](https://github.com/NGanch/goit-rdb-hw-03/assets/86801593/88e72ff5-932b-4c94-9024-5c35e9ecb9e1)

SELECT name, phone FROM shippers;
![р2_](https://github.com/NGanch/goit-rdb-hw-03/assets/86801593/26f24dac-235b-44b1-b58d-fc935118fa6e)

SELECT AVG(price) AS average_price, MAX(price) AS max_price, MIN(price) AS min_price FROM products;
![р3_](https://github.com/NGanch/goit-rdb-hw-03/assets/86801593/9e23030c-14c8-495d-8763-192441e643fd)

SELECT DISTINCT category_id, price FROM products ORDER BY price DESC LIMIT 10;
![р4_](https://github.com/NGanch/goit-rdb-hw-03/assets/86801593/6920630b-e89e-44e5-88aa-e59e5fa15c39)

SELECT COUNT(*) AS product_count FROM products WHERE price BETWEEN 20 AND 100;
![р5_](https://github.com/NGanch/goit-rdb-hw-03/assets/86801593/4c9e1aef-35d5-4af6-9ced-e3ec86d4b77c)

SELECT supplier_id, COUNT(*) AS product_count, AVG(price) AS average_price FROM products GROUP BY supplier_id;
![р6_](https://github.com/NGanch/goit-rdb-hw-03/assets/86801593/b7c10732-d415-48ad-8e43-08571838ca29)

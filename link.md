# Link records

We can create use column of type "link to other records" to link records in the same table or different tables.

Here we use a base called "Products and Orders" to show

* how to link records of different tables
* how to show a specific column of a linked record
* how to summarize a column of linked records

<img src="https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/image (51).png?raw=1" height="null" width="698" />

<img src="https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/image (52).png?raw=1" height="null" width="700" />

The Products table contains two products and each product associated with size and stock quantity.

The Orders table records the orders of every products. The Product column is a link column, that links to the Products table.

To display the product size from the product table, we use a formula `{Product.Size}` . This formula shows a specific column of a linked record.

<img src="https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/image (53).png?raw=1" height="null" width="457" />

In the products table, we'd like to show the total ordered quantity and **make sure it does not exceed the stock quantity**. We use a formula column `Sold` with formula `rollup('Orders', 'Quantity', 'sum')` .

<img src="https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/image (54).png?raw=1" height="null" width="451" />



 

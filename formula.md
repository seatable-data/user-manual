# Formula

If you want to display the results that can be calculated from other columns, you can use the formula column.

The following example uses the same-day salary of a part-time team as an example to introduce how to create and use calculated formula columns.

## Add formula column

If in a table we have recorded the working hours and hourly wages of each employee, and now we need to calculate his salary for that day for each employee.

Let's create a new column and choose the type 'formula', and use the formula `{Hours} * {Per Hour}` 

<img src="https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/image (35).png?raw=1" width="357.609375" height="null" />

After submit the formula, we have a table below:

<img src="https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/image (32).png?raw=1" width="762.609375" height="null" />

## Formula types

The calculation formula is divided into the following types according to the type of data processed: 

* Mathematics: used for mathematical operations, such as addition, subtraction, multiplication, and division
* Text: used to process text, such as converting all characters of a string to lower case
* Date and time: used to calculate the date and time, such as get the current date and time
* Statistics: Contains some common statistical functions such as averaging and maximizing
* Logic: Contains common logic processing functions, such as AND, OR, NOT

Formula can also be nested to form more complex formula. The list of all formulas is presented in the next section. 

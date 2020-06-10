# Formula Reference

Formula name is case-insensitive.

Formula parameters can a predefined constant like E (e, 2.71828183), or a number or a string or a column name.

A column name should be reference by `{Column Name}` .

Functions can be nested, like:  ABS(SUM(-20, -200, 3)) => 217

## Math

### Operator

| Operator | Description                          | Examples         |
| :------- | :----------------------------------- | ---------------- |
| \+       | Add two numbers                      | 1 + 1  => 2      |
| \-       | Minus                                | 2 - 1 => 1       |
| \*       | Multiply                             | 2 \* 3 => 6      |
| /        | Divide                               | 4 / 2 => 2       |
| %        | Remainder of division of two numbers | 5 % 2 => 1       |
| ^        | Power                                | 2^3 => 8         |
| ===      | If two numbers are equal             | 2 === 3 => false |
| \<>      | If tow numbers are not equal         | 2 \<> 3 => true  |
| \>       | Greater                              | 3 > 3  => false  |
| \>=      | Greater or equal                     | 3 >= 3 => true   |
| \<       | Less than                            | 3 \< 3 => false  |
| \<=      | Less or equal                        | 3 \<= 3 => true  |

### Function

| Function Name                   | Description                                                                                                                                                                          | Examples                                                                                  |
| :------------------------------ | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------- |
| _ABS(number)_                   | The absolute value of a number                                                                                                                                                       | ABS(-2) => 2                                                                              |
| _ADD(number1, number2)_         | Add two numbers                                                                                                                                                                      | ADD(2, 3) => 5                                                                            |
| _CEILING(number)_               | Rounding a number up                                                                                                                                                                 | CEILING(2.3) => 3                                                                         |
| _DIVIDE(number1, number2)_      | Divide two numbers                                                                                                                                                                   | DIVIDE(2, 3) => 0.66666667                                                                |
| _E_                             |                                                                                                                                                                                      | e => 2.71828183                                                                           |
| _EQUAL(number1, number2)_       |                                                                                                                                                                                      | EQUAL(1, 2) => false                                                                      |
| _EVEN(number)_                  | Rounding a number up to an even number                                                                                                                                               | EVEN(3) => 4                                                                              |
| _EXP(number)_                   |                                                                                                                                                                                      | EXP(1) => 2.71828183                                                                      |
| _FLOOR(number)_                 | Rounding a number down                                                                                                                                                               | floor(2.3) => 2                                                                           |
| _GREATER(number1, number2)_     | Greater                                                                                                                                                                              | GREATER(2, 3) => false                                                                    |
| _GREATEREQ(number1, number2)_   | Greater or equal                                                                                                                                                                     | GREATEREQ(3, 2) => true                                                                   |
| _INT(number)_                   | Get the integer part of a number                                                                                                                                                     | INT(3.2) => 3                                                                             |
| _LESSTHAN(number1, number2)_    | Less than                                                                                                                                                                            | LESSTHAN(2, 3) => true                                                                    |
| _LESSTHANEQ(number1, number2)_  | Less or equal                                                                                                                                                                        | LESSTHANEQ(2,3) => true                                                                   |
| LG(number)                      | Calculate the logarithm of base 10                                                                                                                                                   | LG(100) => 2                                                                              |
| _LN(number)_                    | Calculate the logarithm of base e                                                                                                                                                    | LN(E) => 1                                                                                |
| _LOG(number, base)_             | Calculate the logarithm of the base                                                                                                                                                  | LOG(100) => 2; LOG(8, 2) => 3                                                             |
| _MOD(number1, number2)_         |  The remainder when two numbers are divided                                                                                                                                          | MOD(2, 3) => 2                                                                            |
| _MULTIPLY(number1, number2)_    |                                                                                                                                                                                      | MULTIPLY(2, 3) => 6                                                                       |
| _ODD(number)_                   | Rounding a number up to an odd number                                                                                                                                                | ODD(2.3) => 3                                                                             |
| _PI_                            | π                                                                                                                                                                                    | PI => 3.14159265                                                                          |
| _POWER(base, number)_           | The power                                                                                                                                                                            | POWER(3, 2) => 9                                                                          |
| _ROUND(number, numDigits)_      | Calculates a number after rounding to the nearest decimal place. Note on parameters: If numDigits is negative, then it will be rounded to the decimal `numDigits`  before the point. | ROUND(3.1415923, 3) => 3.142;   ROUND(3.1415923, -3) => 0; ROUND(999.1415923, -3) => 1000 |
| _ROUNDDOWN(number, numDigits)_  |                                                                                                                                                                                      | ROUNDDOWN(3.1415923, 3) => 3.141; ROUNDDOWN(999.1415923, -3) => 0                         |
| _ROUNDUP(number, numDigits)_    |                                                                                                                                                                                      | ROUNDUP(3.1415923, 3) => 3.142; ROUNDUP(345.1415923, -3) =>1000                           |
| _SIGN(number)_                  | Determine whether a number is 0, negative or positive. If 0, return 0; if negative, return -1; if positive, return 1                                                                 | SIGN(-2) => -1                                                                            |
| _SQRT(number)_                  | Calculate the root of a number                                                                                                                                                       | SQRT(4) => 2                                                                              |
| _SUBTRACT(number1, number2)_    |                                                                                                                                                                                      | SUBTRACT(2, 3) => -1                                                                      |
| _SUM(number1, \[number2, ...])_ |                                                                                                                                                                                      | SUM(1, 2, 3) => 6                                                                         |
| _UNEQUAL(number1, number2)_     |                                                                                                                                                                                      | UNEQUAL(1, 2) => true                                                                     |

## Text

### Operator

| Operator | Description                  | **Examples**                                                         |
| :------- | :--------------------------- | -------------------------------------------------------------------- |
| &        | Concatenate multiple strings | "SeaTable" & " is" & " very" & " good."  => "SeaTable is very good." |

### Function

| Function                                                   | Description                                                                                                                                                         | Examples                                                                                                                                                                                                   |
| :--------------------------------------------------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| CONCATENATE(string1, \[string2, ...])                      | Concatenate multiple strings                                                                                                                                        | CONCATENATE('Sea', 'Table') => 'SeaTable'                                                                                                                                                                  |
| _EXACT(string1, string2)_                                  | Determine if two strings are equal                                                                                                                                  | EXACT('SeaTable', 'SeaTable') => true                                                                                                                                                                      |
| _FIND(findString, sourceString, startPosition)_            | Find a string in another string from a startPosition. The start position counted from 1. Return the position if found, else 0.                                      | FIND('sea', 'SeaTable', 1) => 0                                                                                                                                                                            |
| _LEN(string)_                                              | The length of a string                                                                                                                                              | LEN(“SeaTable”) => 8                                                                                                                                                                                       |
| _LEFT(string, count)_                                      | Get truncated string from the beginning of a string                                                                                                                 | LEFT("SeaTable", 3) => Sea                                                                                                                                                                                 |
| _LOWER(string)_                                            |                                                                                                                                                                     | LOWER("SeaTable") => seatable                                                                                                                                                                              |
| _MID(string, startPosition, count)_                        | Gets the string whose length is count from the startPosition of a string.                                                                                           | MID("SeaTable is very good.", 1, 8 ) => SeaTable;                      MID("SeaTable is very good.", -1, 8 ) => #value!                               MID("SeaTable is very good.", 1.2, 8 ) => "SeaTable" |
| _REPLACE(sourceString, startPosition, count, newString)_   | Replace the count characters starting from startPosition in sourceString with newString.                                                                            | REPLACE("SeaTable is very good.", 1, 8, "Seafile") => Seafile is very good.                                                                                                                                |
| _REPT(string, number)_                                     | Repeat a string                                                                                                                                                     | REPT("Sea", 3) => "SeaSeaSea"                                                                                                                                                                              |
| _RIGHT(string, count)_                                     | Gets a certain number of strings from the end of the string.                                                                                                        | RIGHT("SeaTable is very good.", 5) => good.                                                                                                                                                                |
| _SEARCH(findString, sourceString, startPosition)_          | Search in a string                                                                                                                                                  | SEARCH("sea", “SeaTable”, 1) => 1                                                                                                                                                                          |
| _SUBSTITUTE(sourceString, oldString, newString, \[index])_ | Replace oldString with newString at the index in sourceString. Note on parameters: 1. When index is 0, replace all 2. When there are only 3 parameters, replace all | SUBSTITUTE("SeaTableTable", "Table", "file", 0) => Seafilefile                                                                                                                                             |
| _T(value)_                                                 | Get string part of value                                                                                                                                            | T("123") => "123"; T(123) => ""                                                                                                                                                                            |
| _TRIM(string)_                                             | Remove spaces from both ends of a string                                                                                                                            | TRIM("  SeaTable  ") => "SeaTable"                                                                                                                                                                         |
| _UPPER(string)_                                            |                                                                                                                                                                     | UPPER("SeaTable") => "SEATABLE"                                                                                                                                                                            |
| _VALUE(string)_                                            | Convert string to number                                                                                                                                            | VALUE("123") => 123                                                                                                                                                                                        |

## Date and time

| Function                                                    | Description                                                                                                              | Examples                                                  |
| :---------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------- | --------------------------------------------------------- |
| _DAY(date)_                                                 | Get the day part of a date. \[1, 31]                                                                                     | DAY("2020-01-03") => 3                                    |
| _DAYS(startDate, endDate)_                                  | The number of days from startDate to endDate. (excluding endData)                                                        | DAYS("2020-01-01", "2020-02-03") => 33                    |
| _HOUR(date)_                                                | Get the hour part \[0-23]                                                                                                | HOUR("2020-02-14 13:14:52") => 13                         |
| _MINUTE(date)_                                              | Get the minutes part \[0-59]                                                                                             | MINUTE("2020-02-14 13:14:52") => 14                       |
| _MONTH(date)_                                               | Get the month part \[1-12]                                                                                               | MONTH("2020-02-14 13:14:52") => 2                         |
| _NETWORKDAYS(startDate,endDate,holiday1, \[holiday2, ...])_ | The number of work days from startDate to endDate. (excluding endData)                                                   | NETWORKDAYS("2020-01-01", "2020-01-07","2020-01-01") => 6 |
| _NOW()_                                                     | Get current time (YYYY-MM-DD hh:mm)                                                                                      | NOW() => 2020-02-14 13:14                                 |
| _SECOND(date)_                                              | Get the second part                                                                                                      | SECOND("2020-02-14 13:14:52") => 52                       |
| _TODAY()_                                                   | Get current date (YYYY-MM-DD)                                                                                            | TODAY() => 2019-12-14                                     |
| _WEEKDAY(date, \[weekStart])_                               | Get the weekday number (1-7)。weekStart is for setting the start day of a week, default is 'sunday'.                      | WEEKDAY("2020-01-01", "Monday") => 3                      |
| _WEEKNUM(date, \[weekStart])_                               | Get the week number of `date`  in a year. (1-53). weekStart is for setting the start day of a week, default is 'sunday'. | WEEKNUM("2020-01-13", "Monday") => 2                      |
| _YEAR(date)_                                                | Get the year part                                                                                                        | YEAR("2020-01-01") => 2020                                |

## Statictics

| Function                                           | Description                          | Examples                         |
| :------------------------------------------------- | :----------------------------------- | -------------------------------- |
| _AVERAGE(number1, \[number2, ...])_                | Get the average number               | AVERAGE(1, 2, 3, 4, 5) => 3      |
| _COUNT(number2, \[number2, ...])_                  | Get the count of numbers in an array | COUNT(1, '', 2, '3') => 2        |
| _COUNTA(textOrNumber2, \[textOrNumber2, ...])_     | Get non-empty items in an array      | COUNTA(1, '', 2, '3' ) => 3      |
| _COUNTALL(textOrNumber2, \[textOrNumber2, ...])_   | Get the number of items in an array  | COUNTALL(1, '', 2, 3) => 4       |
| _COUNTBLANK(textOrNumber2, \[textOrNumber2, ...])_ | Get empty items in an array          | COUNTBLANK(1, '', 2, 3, '') => 2 |
| _MAX(number1, \[number2, ...])_                    | Get the maximum number               | MAX(1, 3, 4, 2, -1) => 4         |
| _MIN(number1, \[number2, ...])_                    | Get the minimum number               | MIN(1, 3, 4, 2, -1) => -1        |

## Logic

| Function                                                       | Description                                                                  | Example                                                                                               |
| :------------------------------------------------------------- | :--------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------- |
| _AND(logical1, \[logical2, ...])_                              | If every condition is true (non-empty, not 0), return true, else false.      | AND(1, '', 2) => false                                                                                |
| FALSE()                                                        | Return false                                                                 | FALSE() => false                                                                                      |
| _IF(logical, value1, value2)_                                  | If logical is true，return value1，else return value2.                         | IF(1 > 2, 1, 2)                                                                                       |
| _NOT(boolean)_                                                 |                                                                              | NOT(true) => false                                                                                    |
| _OR(logical1, \[logical2, ...])_                               | If one of the condition is true (non-empty, not 0), return true, else false. | OR(1, '', false) => true                                                                              |
| _TRUE()_                                                       | Return true                                                                  | TRUE() => true                                                                                        |
| _XOR(logical1, \[logical2, ...])_                              | If there are odd number of true items, return true, else return false.       | XOR(1, '', 2, '', 3) => true                                                                          |
| _SWITCH(logical, matcher1, value1, matcher2, value2, default)_ |                                                                              | SWITCH(INT(68/10), 6, 'Good', 7, 'Bad', 8, 'So so', 9, 'Excellent', 10, 'Great', 'Unknown') => 'Good' |





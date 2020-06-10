# Filter

The purpose of filtering is to help us filter out the records that do not meet the conditions and only show the records that meet the conditions. This section then uses recruitment interviews as an example to show the use of filtering.

Click the "Filter" button in the upper left corner of the interface. The pop-up box is shown below. There are three options from left to right:

* Column: It means to filter a certain column. You can select any column from all non-file and image type columns.
* Logical predicates: Represents the relationship between columns and filtered values. There are multiple logical predicates to choose from.
* Filter value: It means to filter based on a certain value.

You can set "column", "filter value" and select "logical predicate" to specify a logical relationship between the two, so that the three items are combined into a filter condition. For example, in an `Issues`  table if you want to filter all issues with status `wont-fix` , you can set column" to "Name", logical predicate to "is not", and the filter value should be set to "wont-fix".

<img src="https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/image (38).png?raw=1" height="null" width="538.390625" />

## Logical predicates

SeaTable also provides more logical predicates for you to choose from. 

For Text column, the predicates include:

* contains: the string should contain a certain sub-string.
* does not contain: the string should not contain a certain sub-string.
* Is: It means exactly the same.
* Is not: the complement of "Is".
* Is empty: The value is empty.
* Is not empty: The value is not empty.

For Date column, the predicates include:

* During a certain period of time: Provide many common options, such as
  * the past week and the next week.
  * In the past year / month / week
  * This year / this month / this week
  * Next year / month / week
  * Specified days after today
  * Specified days before today
* Before a day: You can quickly select a week ago, a month ago, or a specific date.
* After a certain day: You can quickly select a week, a month, or a specified date.
* On or before: Similar to "Before", except that the day of the specified date is included.
* On or after: Similar to "after", except that the day of the specified date is included.

## Relationship between conditions

Click "Add a filter" to add a filter condition, we can create several conditions. Conditions can have the following two relationships:

* And: several filter conditions are "and" relationship, as long as one of the conditions does not meet, records will be filtered out. Only records that satisfy all conditions at the same time will be filtered and displayed.
* Or: There is an "or" relationship between several filter conditions. As long as one of the conditions is met, the records will be filtered and displayed. Only records that do not meet any of these conditions will be filtered out.

Note that several conditions are either "and" or "or" relationships, and the two relationships cannot be mixed.

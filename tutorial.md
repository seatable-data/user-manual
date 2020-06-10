# Tutorial

SeaTable is an online lightweight database with a spreadsheet interface. It helps you to easily record and manage all kinds of scattered information.

Below we take the collaborative processing recruitment process as an example to demonstrate the basic use of SeaTable.

## Create a base

A base is equivalent to a container and can be used to store multiple tables of the same type of business. For example, by clicking the "Add base" button in the red box below to create a form called "Recruitment", you can then create several subtables related to recruitment business.

<img src="https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/image (49).png?raw=1" height="null" width="708" />

## Share base

The base created in My Tables is only visible to you. If you need other people to have access, you need to share the base with them first. 

The base created in a group is visible to all group members.

## Create table

The recruitment process involves many steps, and interview is one of the important steps. We take the interview as an example to create a table, click into the base called "Recruitment", and then click the button '**+**' in the upper left corner to create a new table called "Interviews".

<img src="https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/image (46).png?raw=1" width="513" height="null" />

The table is created, but there is only one column with default properties. In the next section, we will create more columns.

<img src="https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/image (47).png?raw=1" width="406" height="null" />

## Create columns

An interview arrangement needs to record a lot of information, such as the interviewer's name, resume, work experience, interview time, etc., each of them requires us to create a column of corresponding type. Click the "+" button in the table header to create a new column.

When you create a column, SeaTable requires you to associate a data type for the column. Setting the data type can prevent you from entering meaningless or malformed data. For example, now we create the "Resume" column. The resume should be a Word or PDF document, so the type should be "File". After the column is created, only files can be uploaded when entering data for this column.

<img src="https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/image (48).png?raw=1" width="385" height="null" />

In addition to the above, SeaTable also provides more rich data types as follows:

* Text: suitable for entering phrases
* Numbers: Provide a variety of commonly used number formats, such as percentages, currencies, etc.
* Check: You can select "Check" or "Uncheck"
* Date: Provides multiple common date formats
* Single Select: User can select a label from multiple labels
* Long text: suitable for entering large paragraphs of text, supporting easy insertion of pictures, links, tables, lists, etc.
* Picture: Only insert pictures
* File: Only upload files
* Multiple select: Multiple tags can be created, allowing users to insert multiple of them
* Collaborators: Can insert users who have access to the form (for assigning tasks, etc.)

## Insert data

Referring to the method of creating columns, we can also create the columns "Work experience", "Interview time", "Interview evaluation", "Status", "Job category", etc., but there is no data in the table. As shown in the red box below, click "+" to create a new row to insert more data.

![](<https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/1 (9).png?raw=1>)

Then enter all the data of the interviewers into the table, and you will get a complete table. Results as shown below

![](<https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/2 (16).png?raw=1>)

## Get internal links

When there is a lot of data in the table, you may only want colleagues to focus on one of the records. It is time-consuming for colleagues to look up in massive data, you can generate a separate link for a record. By clicking the button in the red box below, you can see all the information in this record.

<img src="https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/3 (5).png?raw=1" width="717" height="null" />

Then click the "Get Link" button above, the system will automatically copy the record link. You can send the link to a colleague. If the colleague has permission to access this table, SeaTable will directly display this record instead of the entire table.

<img src="https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/4 (3).png?raw=1" width="501" height="null" />

## Create views

The "Interview Schedule" table now contains records of all interviewers, but everyone actually wants to see only the part of the record we care about, which can be achieved by creating a view.

A view is a data set obtained by setting certain processing rules on the original table. It has the same columns as the original table. Its advantage is that it can help us focus on specific data. As shown in the red box in the figure, click the "▽" button in the "View Bar" above the table, select "Add a View", and follow the prompts to complete the creation.

<img src="https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/5 (3).png?raw=1" width="502" height="null" />

Next, you need to set processing rules for the view. The interface is shown in the following figure. The currently supported rules include the following:

* Filter
* Sort
* Group
* Hide

![](<https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/6 (2).png?raw=1>)

The following examples introduce the rules one by one.

## Filter

There are a lot of records in the "Interview Schedule" form, but we don't care about the interviewers who have canceled or been eliminated. We only want to check the situation of those who are waiting for an interview or have been offered. In this case, filters can help us filter out unqualified interviewers.

Click the "Filter" button in the toolbar, as shown below, select the "+" button to add a filter. Multiple filters can have an "and" or "or" relationship. Here we set two filters for the "Status" column, the purpose is to filter out the "Status" column is neither "Eliminated" nor "Canceled" status of the interviewer.

![](<https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/7 (2).png?raw=1>)

After the filter is executed, only the information of those who have been offered or to be interviewed are retained in the view. The effect is shown in the figure below.

![](<https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/8 (1).png?raw=1>)

## Sort

You can sort the interviewers based on the value of some columns. For example, when you want to view interviewers who have more work experience and a later interview time, you can click the Sort button in the toolbar. As shown in the figure below, select the "+" button to add sorting conditions. You only need to set the "Work Experience" and "Interview Time" in descending order respectively. Among multiple sorting conditions, the highest priority has the highest priority, and the lowest priority has the lowest priority.

![](<https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/9 (2).png?raw=1>)

The results will be sorted in descending order of work experience, and then in the descending order of interview time, so that the interviewers with the most work experience and the latest interview time will be ranked first. Results as shown below

![](<https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/10 (1).png?raw=1>)

## Group

Sometimes when HR wants to choose some senior engineer positions, he/she hopes to group interviewers with long working years into a group to facilitate the selection and comparison of their information. This can be achieved by grouping.

Click the "Group" button in the toolbar as shown in the figure below. SeaTable does not support grouping by multiple columns yet. Here we choose to group by work experience.

![](https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/11.png?raw=1)

After the grouping is performed, as shown in the following figure, the interviewers with 7 years of work experience are in the first group, the interviewers with 3 years are in the second group, and the interviewers with 2 years are in the third group. HR can select the required resume directly in the 7-year experience group.

![](https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/12.png?raw=1)

## Hide

Some unnecessary columns can be hidden in the view. Click the "Hide" button in the toolbar. You can drag unwanted columns to gray and the columns in orange will still display normally.

![](https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/13.png?raw=1)

Hide is complete, the effect is shown below

<img src="https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/14.png?raw=1" width="806" height="null" />

## Conclusions

Through the introduction above, presumably you have learned how to use SeaTable. SeaTable also has some advanced features waiting for you to discover! Please continue reading other documents or find out during use.

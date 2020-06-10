# View locking

Because SeaTable tables support collaborative editing by multiple people, in order to prevent others from modifying views and tables at will, SeaTable provides two locking mechanisms:

* Lock filtering and sorting conditions: After locking, you cannot change the filtering, sorting, grouping, and hiding conditions
* Lock table header: After locking, the width and order of the columns cannot be changed

As shown in the figure below, there are two "lock" buttons in the red box. The "lock" button above is on the right side of the view name, used to lock the filtering and sorting conditions of a view. The "lock" button below is on the left side of table headers,  used to lock the header of the entire table. By default, they are open locks, which represent unlocked states.

<img src="https://docs.seatable.io/lib/77cbe12e-72a7-488b-972d-0ca6376cd056/file/images/auto-upload/image (31).png?raw=1" height="null" width="777.390625" />





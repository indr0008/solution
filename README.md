# solution
solution for Dkatalis

# the step by step thinking process are included in the jupyter notebook file. We will discuss the transactions in this notebook

The transactions are on the following rows of the final merged table:

10	a1	Jakarta	c1	anthony@anotherbank.com	a1globalid	Anthony	u	87654321	sa1	1578313800000	...	12000.0	c1globalid	30000.0	ACTIVE	15000.0	sa1globalid	3.0	sa1	
11	a1	Jakarta	c1	anthony@anotherbank.com	a1globalid	Anthony	u	87654321	sa1	1578420000000	...	19000.0	c1globalid	30000.0	ACTIVE	15000.0	sa1globalid	3.0	sa1	
12	a1	Jakarta	c1	anthony@anotherbank.com	a1globalid	Anthony	u	87654321	sa1	1578648600000	...	19000.0	c1globalid	30000.0	ACTIVE	40000.0	sa1globalid	3.0	sa1
13	a1	Jakarta	c1	anthony@anotherbank.com	a1globalid	Anthony	u	87654321	sa1	1578654000000	...	0.0	c1globalid	30000.0	ACTIVE	21000.0	sa1globalid	3.0	sa1	
20	a1	Jakarta	c2	anthony@anotherbank.com	a1globalid	Anthony	u	87654321	sa1	1579361400000	...	37000.0	c2globalid	70000.0	ACTIVE	21000.0	sa1globalid	4.0	sa1	
21	a1	Jakarta	c2	anthony@anotherbank.com	a1globalid	Anthony	u	87654321	sa1	1579505400000	...	37000.0	c2globalid	70000.0	ACTIVE	33000.0	sa1globalid	4.0	sa1

1st transaction: occured at ts 1578313800000, credit used +12000, savings account +15000
2nd transaction: occured at ts 1578420000000, credit used +7000, savings account +0
3rd transaction: occured at ts 1578648600000, credit used +0, savings account +25000
4th transaction: occured at ts 1578654000000, credit used -19000, savings account -19000
5th transaction: occured at ts 1579361400000, credit used +37000, savings account +0
6th transaction: occured at ts 1579505400000, credit used +0, savings account +12000

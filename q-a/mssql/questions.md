# MSSQL questions

1 What super useful feature about DB projects does VS2012+ has?
2 If you do repeated select without order, can you expect same result order every time?
3 What should be done to xml column so that it could have index?
4 What is the Maximum Size per Database for SQL Server Express?
5 Is It Possible to have non-Clustered Index on Separate Drive From Original Table Location?
6 Is It Possible to have Clustered Index on Separate Drive From Original Table Location?
7 What is the difference between varchar(N) and varchar (MAX)? (size and place)
8 Which one large text type is recommended - varchar(max) or text?
9 What is BCP? When is it Used?
10 Global temp table vs local temp table. Both are dropped when connection A is dropped. What is the difference?
11 The process of automating the backup of database and transaction log files on a production SQL server and then restoring them onto a standby server. - How is it called?
12 Can procedures be called recursively?
13 Connection pools - what kind of app uses it? - A. Web app (ASP.NET) - B. Any .Net app (ADO.NET)
14 When UPDATE_STATISTICS command is recomended?
15 What interesting feature does truncate command have (related to ids)
16 Primary key vs unique key - what kind of index do they create?
17 Primary key vs unique key - how many null records does they allow?
18 What are the leaf nodes of non-clustered index?
19 What problems will you face, if you want search by full text search and then sort by some other column?
20 A join that displays only the rows that have a match in both joined tables
21 Join that does not have a WHERE clause produces the Cartesian product of the tables involved in the join - how is it called?
22 Can functions be used in joins like tables?
23 A set of rules that determine how data is sorted and compared. How is it called?
24 What MS SQL feature allows to join tables from different servers?
25 DDL Triggers - can there be instead of type of DDL trigger?
26 What are two types of DML Triggers?
27 if you do select @a = a from table... and no row is selected, will @a be set to null?
28 What does EXEPT statement does in selects?
29 If you have a<> 1 in where condition, will nulls be taken?
30 Waht is the syntax in BEGIN TRY END TRY BEGIN CATCH ... END CATCH
31 In management studio, if you want to change column type in designer and it blocks this action saying, that rows need to be recreated. Is there a way to workaround this?
32 What is the difference between union and union all?
33 Are subselects allowed?
34 Are self joins allowed?
35 As left joins are not allowed, what is the workaround?
36 Can I have a foreign key referencing a column in a view in SQL Server?
37 View is created, then table column type is changed. Will view column type change automatically?
38 What view is logically to his caller?
39 What view is physically?
40 Can views have indexes?
41 Does view indexes have more restrictions, than normal indexes?
42 What can you create for column if you want some checks?
43 What can you create for table if you want to have before/after "handlers" for insert/update/delete actions?
44 What can you create if you want some scheduled tasks on sql server?
45 What tool should be used to watch and kill processes?
46 Can stored procedure return more than one select?
47 What are leaf levels of clustered index?
48 Which is faster - index seek, or index scan?
49 Which is better in where condition: a=isnull(@a, a) or @a is null or a = @a?
50 Is index used in "where is null..."
51 Is index used in "WHERE .A. AND .B."?
52 Is index used in "WHERE .A. OR .B."
53 If both indexes are used in "WHERE .A. AND .B.", if they are created separately, how it is done
54 Is hash join expensive, compared to other joins?
55 What does SELECT (nolock) mean?
56 Does SELECT without nolock cause table to lock?
57 Is there table data type?
58 What is the difference between nVarcharMax and nVarChar?
59 How local variables are marked
60 How global variables are marked?
61 Does Like '%..' use index?
62 Does Like '..%' use index?
63 Does negatives (!=, NOT IN) use index?
64 How to add rownumber column?
65 What are three types of joins?
66 What nice feature does construct "With tmpTable (...) AS {SELECT}" support?
67 What is better alternative to delete, if all table is deleted?
68 How view should be created to support view indexes?
69 Can execution plans be logged in profiler?
70 Is Convert and Cast any different?
71 How to set some free space in index pages to avoid index fragmentation?
72 What are usual FILLFACTOR values?
73 What needs to be done to avoid index fragmentation besides initial fillfactor setting?
74 What does index xreate directive pad_index mean?
75 If >50% of rows are selected, will it use index?
76 If ntext field needs index, what should be done?
77 Can free text index search for similar words?
78 Why statistics should be renewed regularly?
79 What usually can be passed for tuning advisor?
80 What bad effect has stream aggregate execution plan step?
81 What bad effect has "sort" or "filter" execution plan step?
82 How many read operations does it take to read one page?
83 Why it is possible that nonclustered index works faster than clustered?
84 Can secondary xml index be created without creating primary xml index?
85 What are three main services in replication?
86 What two of three main replication services can be on same machine?
87 Can stored procedure be an replication article?
88 How set of articles is called in replication?
89 How request to replicate a publication is called in replication?
90 What are two types of subscriptions?
91 Where "push" type subscription agent runs?
92 Where "pull" type subscription agent runs?
93 What 3 types of replication there are?
94 What two types of repliaction use push subscription?
95 What type of repliaction use pull subscription?
96 What is the first action, which transactional replication takes on initialization?
97 What is msmq analog service in ms sql?
98 For huge replicated tables, when need to add column, how not to cause reinitialization?
99 Is it possible, that sometimes better way to update replicated table rows is to stop repliaction and reinitialize it afterwards?
100 In query analyser, what command selects main info about table?
101 When foreign keys become to have disadvantages?
102 If query always selects the same subset of table (lets say not null) what is the way to make smaller index, than default. What syntax (roughly) should be used?
103 If you alter the procedure, and it throws error, that there were problems finding query plan, what needs to be done?
104 When multiple usages of different DB are needed, what is the construct to give a name for all calls to this DB?
105 Can column be altered from int to decimal? Will it delete and recreate all rows?
106 If where condition filters smthing, will row_number have gaps?
107 What makes a little bit more trouble - to add param for procedure or function? Why?
108 In which construct - where, group, having, order, - can you use given name for calculated "column"?
109 If we have declare'd xmlvar xml, what is the syntax to select relational data from it?
110 What does cross apply do?
111 If you have just added new object to DB, what small inconvenience can be expected in management studio?
112 What is the super strange behaviour when comparing null value?
113 When writing scripts, which command in the begginning would control, that only limited number of rows would be updated?
114 If you write script: begin tran, XXX, rollback - and stop execution at XXX - will transaction be reverted?
115 If transaction is in progress in one management studios window - can it be rolled back in other? Why?
116 Why column type datetime2 is useful? Give two reasons)
117 Why date and time column types are useful? Give two reasons.
118 What single best feature related to indexes is in MS SQL 2008?
119 Why are nvarchar(max) and varbinary(max) better than blob?
120 If I want to get some stats about how indexes are used, what indexes sql server wanted to have, - what are two ways to do it?
121 If ORM generates queries dynamically, what SQL server does to execution plans?
122 If you write order by x, from which number columns are indexed?
123 If you need to skip some rows and take some rows, how to do it in sql? What version of sql server would allow that?
124 In what situation it is needed to have ids like this - 50000000001 400000000002...?
125 What is the biggest disadvantage of Guid's big space?
126 When does Guid is very useful?
127 Of two similar methods - ResolveClientUrl and ResolveUrl - which one returns path relative to site root? Which one relative to current page?
128 If you see error msg "unable to generate query plan", what can be wrong with your stored procedure?
129 There is xml type variable @xml - what is the syntax to insert tag?
130 If IDENTITY gives not what you need inside the trigger, what alternative could be used?
131 What to do, if there are '[' symbols in like statement, and it behaves stangely?
132 What is the main restriction, if you want to do xml.modify?

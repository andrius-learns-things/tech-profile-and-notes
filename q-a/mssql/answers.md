# MSSQL answers

1 Keeping track of changes in structure
2 No, it may take different index
3 Xml schema should be set
4 SQL Server Express supports a maximum size of 4 GB per database, which excludes all the log files.
5 yes
6 No
7 varchar is stored in row, must be under 8KB. varchar(max) must be under 2GB (pinter outside of row)
8 varchar(max)
9 BCP or BulkCopy is a tool used to copy huge amounts of data from tables and views
10 Global temp table can be seen in different connections while it exists
11 Log shipping
12 Yes
13 B
14 After many changes
15 Truncate resets the identity
16 Primary - clustered, unique - nonclustered
17 Primary - 0, Unique - 1
18 Index rows
19 Performance
20 inner join
21 Cross join
22 Yes
23 Collation
24 LinkedServers
25 No, only after
26 Instead of and after
27 No
28 Set minus operation - cxompares two sets and removes duplicating ones
29 No
30 do smth ERROR_MESSAGE();
31 Uncheck checkbox in mamagement studio
32 union - takes unique, union all - all.
33 No
34 No
35 inner joins with isnull
36 You can't reference a view in a foreign key
37 No
38 Virtual table
39 Stored select
40 Yes
41 Yes
42 Constraints
43 Triggers
44 Jobs
45 Activity Monitor
46 Yes
47 Data pages
48 Seek
49 Second one
50 No
51 Yes
52 No
53 Index join
54 Yes
55 Dirty read
56 No
57 Yes
58 First is BLOB
59 @name
60 @@variable
61 No
62 Yes
63 No
64 ROW_NUMBER() OVER()
65 Nested loop, hash join and merge join
66 Recursive selects
67 Truncate
68 WITH SCHEMABINDING
69 Yes
70 No
71 FILLFACTOR option while creating
72 70-90
73 Recreation of indexes
74 FILLFACTOR usage not only in leaf level
75 No
76 Free Text index
77 Yes
78 Because query optimiser uses it
79 Trace file
80 Tmp table creation
81 Not using an index
82 1
83 More rows per page
84 No
85 Publisher, distributor, subscriber
86 Publicator and distributor
87 Yes
88 Publication
89 Subscription
90 Push and pull
91 On distributor
92 On subscriber
93 Snapshot, transactional, merge
94 Snapshot and transactional
95 Merge
96 Takes snapshot and checks, if it needs to be transmitted
97 Service Broker
98 Add column in replication
99 Yes
100 Alt F1
101 When doing import of lots of tables, classifiers, etc. Then it is wise to get all data without them and recreate.
102 Filtered index - create index ... where a is not null
103 Drop and create with recompile
104 Synonim
105 Yes, no.
106 No
107 function, change all calling places
108 Order
109 select a.b.value() from xmlvar.nodes() a(b)
110 Checks condition on every row join
111 It will not recongnize it, until its cache is refreshed
112 It is false even after NOT opperation
113 set rowcount x
114 No
115 No, one window - one connection - one transaction
116 compatible with .net zero date, can be smaller without miliseconds
117 Smaller, can be sure that no bad data will be stored
118 Filtered indexes
119 They are included in the row, except if it exceeds 8K
120 DB reports menu and dynamic management views
121 Caches for the same queries
122 1
123 top, subselect and row_number. 2005 and more
124 Merge replication with several sources
125 One read will read too little rows, this is important for index structures
126 1. When you need to have id before saving in db 2. Merge replication
127 ResolveUrl returns a path relative to the site root
128 Need to have statements "set quated identifiers on/off"
129 @xml.modify('insert...
130 SCOPE IDENTITY
131 use escape keyword
132 Cannot be done for several rows

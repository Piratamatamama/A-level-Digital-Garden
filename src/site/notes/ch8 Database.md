---
{"dg-publish":true,"permalink":"/ch8-database/"}
---

sql
```

CREATE DATABASE <database name> 
CREATE TABLE <Table name>
(courseID VARCHAR(9) NOT NULL,
teacherID VARCHAR(9),
primary key(courseID)

);


```

order by/ group by
```
SELECT <field name1>, <field name 2>
FROM <table name 1>, <table name 2>
WHERE < condition> AND < condition2>
ORDER BY < ASC>/<DESC>
GROUP BY < Field name>;

```
inner join
```
SELECT <field name1>, <field name 2>
FROM <table name 1> 
INNER JOIN <table name 2>
ON <table 1>.<primary key> = <table 2>.<foreign key>
WHERE < condition> AND < condition2>;

```

sum/avg and count
``` 
# count number of teacher 
# use teacherID since unique
COUNT(TeacherID) AS NumOfTeacher 

# sum of exam marks for all row for field ExamMarks
SUM(ExamMarks) AS SumMarks

# avg of exam marks 
AVG(ExamMarks) AS AvgMarks
```

maintenance
```
DELETE FROM < table name>
WHERE <condition>;
```
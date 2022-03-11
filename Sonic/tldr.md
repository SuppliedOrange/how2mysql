# Make Database

```sql
CREATE DATABASE db; 
``` 

# Delete Database
```sql
DROP DATABASE db;
```

# Use Database
```sql
USE db;
```

# Make Table
```sql
CREATE TABLE tb (
    columnName datatype,
    columnName datatype,
    ...
    columnName datatype
);
```

# Delete Table
```sql
DROP TABLE tb;
```

# Alter Table
```sql
ALTER TABLE tb
ADD columnName datatype,
DROP COLUMN columnName,
MODIFY COLUMN columnName datatype;
```

# Read table
```sql
SELECT * FROM tb;
```
```sql
SELECT columnName,columnName2 FROM tb;
```

# Show Databases
```sql
SHOW DATABASES (condition)? --optional
```

# Show Tables
```sql
SHOW TABLES (condition)? --optional
```

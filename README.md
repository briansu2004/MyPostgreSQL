# MyPostgreSQL

My PostgreSQL

## Use PostgreSQL with Docker in Windows

### pgAdmin 4

<http://www.pgadmin.org>

### IntelliJ

Install "Database Navigator" plugin!

![1671895288627](image/README/1671895288627.png)

![1671897002593](image/README/1671897002593.png)

![1671896942823](image/README/1671896942823.png)

Note:

- Mind the "Auto-Commit" setting!

- "Database tools" plugin is not free - uninstall / disable it!

- This doc is good but didn't mention the plugin!

<https://www.jetbrains.com/help/idea/running-a-dbms-image.html#connect_to_psql>

## Reference

<https://wiki.postgresql.org/wiki/PostgreSQL_Clients>

## Use PostgreSQL with Docker in Mac

...

## Basic syntax

```sql
DROP TABLE [IF EXISTS] table_name [CASCADE | RESTRICT];

CREATE TABLE [IF NOT EXISTS] table_name (
   column1 datatype(length) column_contraint,
   column2 datatype(length) column_contraint,
   column3 datatype(length) column_contraint,
   table_constraints
);
```

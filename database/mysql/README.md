# MySQL Queries

## Search columns of specific name in all tables of a database
SELECT DISTINCT TABLE_NAME 
    FROM INFORMATION_SCHEMA.COLUMNS
    WHERE COLUMN_NAME like %nome%
        AND TABLE_SCHEMA='your database';
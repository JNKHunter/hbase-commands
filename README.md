### Create table
```
create 'table_name','column_family_name'
```

### Count
```
count 'table_name', CACHE=>1000
```

### Put
```
put 'table_name', 'row_name', 'column_value', 'value'
```
### Alter
You can operate on several column families:
```
hbase> alter ‘table_name’, {NAME => ‘family_1’, VERSIONS => 3}, {NAME => ‘family_2’, VERSIONS => 5}
```

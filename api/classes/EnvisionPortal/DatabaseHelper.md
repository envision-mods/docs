***

# DatabaseHelper





* Full name: `\EnvisionPortal\DatabaseHelper`




## Methods


### fetchBy

Fetches data from the database based on specified criteria.

```php
public static fetchBy(array $selects, string $from, array $params = [], array $joins = [], array $where = [], array $order = [], array $group = [], int $limit = null, int $offset = null): array
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$selects` | **array** | Table columns to select. |
| `$from` | **string** | FROM clause. |
| `$params` | **array** | Parameters to substitute into query text. |
| `$joins` | **array** | Zero or more *complete* JOIN clauses.<br />E.g.: &#039;LEFT JOIN messages AS m ON (a.id_msg = m.id_msg)&#039; |
| `$where` | **array** | Zero or more conditions for the WHERE clause.<br />Conditions will be placed in parentheses and concatenated with AND.<br />If this is left empty, no WHERE clause will be used. |
| `$order` | **array** | Zero or more conditions for the ORDER BY clause.<br />If this is left empty, no ORDER BY clause will be used. |
| `$group` | **array** | Zero or more conditions for the GROUP BY clause.<br />If this is left empty, no GROUP BY clause will be used. |
| `$limit` | **int** | Maximum number of results to retrieve.<br />If this is left empty, all results will be retrieved. |
| `$offset` | **int** | Offset for LIMIT clause. |


**Return Value:**

The result as associative array of database rows.




***

### insert

Inserts data into a table.

```php
public static insert(string $table_name, array $columns): void
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$table_name` | **string** | Name of the table to insert data into. |
| `$columns` | **array** | Associative array of column name =&gt; [type, data]. |





***

### update

Updates data in a table.

```php
public static update(string $table_name, array $columns, string $col, int $id): void
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$table_name` | **string** | Name of the table to update. |
| `$columns` | **array** | Associative array of column name =&gt; [type, data]. |
| `$col` | **string** | Column to update. |
| `$id` | **int** | ID of the row to update. |





***

### delete

Deletes a record from the specified table based on the given column and ID.

```php
public static delete(string $table_name, string $col, int $id): void
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$table_name` | **string** | Name of the table from which to delete the record. |
| `$col` | **string** | Column to match for deletion. |
| `$id` | **int** | ID of the record to delete. |





***

### deleteMany

Deletes multiple records from the specified table based on the given column and array of IDs.

```php
public static deleteMany(string $table_name, string $col, array $ids): void
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$table_name` | **string** | Name of the table from which to delete the records. |
| `$col` | **string** | Column to match for deletion. |
| `$ids` | **array** | Array of IDs of the records to delete. |





***

### deleteAll

Deletes all records from the specified table.

```php
public static deleteAll(string $table_name): void
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$table_name` | **string** | Name of the table from which to delete all records. |





***

### increment

Increments the value of a column in the specified table based on the given condition.

```php
public static increment(string $table_name, string $increment_col, string $where_col, int $id): void
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$table_name` | **string** | Name of the table in which to increment the column value. |
| `$increment_col` | **string** | Column to increment. |
| `$where_col` | **string** | Column to match for the condition. |
| `$id` | **int** | ID of the record to match for the condition. |





***


***
> Automatically generated on 2024-05-11

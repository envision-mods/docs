***

# DataMapperInterface





* Full name: `\EnvisionPortal\DataMapperInterface`



## Methods


### fetchBy

Fetches data from the database based on specified criteria.

```php
public fetchBy(array $selects, array $params = [], array $joins = [], array $where = [], array $order = [], array $group = [], int $limit = null, int $offset = null): array
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$selects` | **array** | Table columns to select. |
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

Inserts a new record into the database.

```php
public insert(\EnvisionPortal\EntityInterface $entity): void
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$entity` | **\EnvisionPortal\EntityInterface** | The entity to insert. |





***

### update

Updates an existing record in the database.

```php
public update(\EnvisionPortal\EntityInterface $entity): void
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$entity` | **\EnvisionPortal\EntityInterface** | The entity to update. |





***

### delete

Deletes a record from the database.

```php
public delete(\EnvisionPortal\EntityInterface $entity): void
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$entity` | **\EnvisionPortal\EntityInterface** | The entity to delete. |





***

### deleteMany

Deletes multiple records from the database.

```php
public deleteMany(array $ids): void
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$ids` | **array** | Array of IDs of the records to delete. |





***

### deleteAll

Deletes all records from the database.

```php
public deleteAll(): void
```












***

### incrementViews

Increments the views counter for a specific entity in the database.

```php
public incrementViews(\EnvisionPortal\EntityInterface $entity): void
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$entity` | **\EnvisionPortal\EntityInterface** | The entity for which to increment the views counter. |





***


***
> Automatically generated on 2024-05-11

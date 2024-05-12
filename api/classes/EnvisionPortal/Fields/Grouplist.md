***

# Grouplist





* Full name: `\EnvisionPortal\Fields\Grouplist`
* This class implements:
[`\EnvisionPortal\CacheableFieldInterface`](../CacheableFieldInterface.md), [`\EnvisionPortal\UpdateFieldInterface`](../UpdateFieldInterface.md)



## Properties


### membergroups



```php
private array $membergroups
```






***

### field



```php
private array $field
```






***

### key



```php
private string $key
```






***

### type



```php
private string $type
```






***

## Methods


### __construct



```php
public __construct(array $field, string $key, string $type): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$field` | **array** |  |
| `$key` | **string** |  |
| `$type` | **string** |  |





***

### fetchData

Fetch data from the database to "cache", or store in memory.

```php
public fetchData(): array
```

This is useful when multiple fields of the same type are loaded
and a static (unchanging) query is used to fetch data.







**Return Value:**

The fetched data.




***

### setData

Store shared data from another field of the same type.

```php
public setData(array $data): void
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$data` | **array** | Data from another field of the same type. |





***

### beforeSave

Transform data before it is saved.

```php
public beforeSave(mixed $val): string
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$val` | **mixed** | The value from POST. |


**Return Value:**

The value to save to the database.




***

### __toString



```php
public __toString(): string
```












***


***
> Automatically generated on 2024-05-12

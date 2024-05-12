***

# CacheableFieldInterface

Interface for cacheable fields, allowing fetching and storing data.



* Full name: `\EnvisionPortal\CacheableFieldInterface`
* Parent interfaces: [`\EnvisionPortal\FieldInterface`](./FieldInterface.md)


## Methods


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


## Inherited methods


### __construct

FieldInterface constructor.

```php
public __construct(array $field, string $value, string $type): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$field` | **array** | An array representing the field properties. |
| `$value` | **string** | The current value of the field. |
| `$type` | **string** | The type of the field. |





***

### __toString

Convert the field to its HTML representation.

```php
public __toString(): string
```









**Return Value:**

The HTML representation of the field.




***


***
> Automatically generated on 2024-05-12

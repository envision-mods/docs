***

# CacheableFieldInterface





* Full name: `\EnvisionPortal\CacheableFieldInterface`
* Parent interfaces: [`\EnvisionPortal\FieldInterface`](./FieldInterface.md)


## Methods


### fetchData

Fetch data from the database to "cache", or store in memory.  This is
useful when multiple fields of the same type are loaded and a static
(unchanging) query is used to fetch data.

```php
public fetchData(): array
```












***

### setData

Grab shared data from another field of the same type.

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



```php
public __construct(array $field, string $value, string $type): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$field` | **array** |  |
| `$value` | **string** |  |
| `$type` | **string** |  |





***

### __toString

Output the HTML control for this field.

```php
public __toString(): string
```












***


***
> Automatically generated on 2024-05-11

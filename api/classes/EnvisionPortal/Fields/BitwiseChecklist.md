***

# BitwiseChecklist





* Full name: `\EnvisionPortal\Fields\BitwiseChecklist`
* This class implements:
[`\EnvisionPortal\UpdateFieldInterface`](../UpdateFieldInterface.md)



## Properties


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

### beforeSave

Transform data right before it is saved.

```php
public beforeSave(mixed $val): string
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$val` | **mixed** | ?string Value from POST. |


**Return Value:**

Value to save to the database.




***

### __toString



```php
public __toString(): string
```












***


***
> Automatically generated on 2024-05-11

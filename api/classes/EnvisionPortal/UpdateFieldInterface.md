***

# UpdateFieldInterface

Interface for fields that need to transform data before saving.es/MIT



* Full name: `\EnvisionPortal\UpdateFieldInterface`
* Parent interfaces: [`\EnvisionPortal\FieldInterface`](./FieldInterface.md)


## Methods


### beforeSave

Transform data before it is saved.

```php
public beforeSave(string|null $val): string
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$val` | **string&#124;null** | The value from POST. |


**Return Value:**

The value to save to the database.




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

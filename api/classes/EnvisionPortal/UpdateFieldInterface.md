***

# UpdateFieldInterface





* Full name: `\EnvisionPortal\UpdateFieldInterface`
* Parent interfaces: [`\EnvisionPortal\FieldInterface`](./FieldInterface.md)


## Methods


### beforeSave

Transform data right before it is saved.

```php
public beforeSave( $val): string
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$val` | **** | ?string Value from POST. |


**Return Value:**

Value to save to the database.




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

***

# FieldTrait





* Full name: `\EnvisionPortal\FieldTrait`



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

## Methods


### __construct



```php
public __construct(array $field, string $key): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$field` | **array** |  |
| `$key` | **string** |  |





***

### isRequired



```php
public isRequired(): bool
```












***

### getError



```php
public getError(): array
```












***

### getInputHtml

Returns the input so the user can enter a value.

```php
public getInputHtml(): string
```












***

### getOutputHtml

Returns the output. It's the field's value formatted acccording to its criteria.

```php
public getOutputHtml(): string
```












***

### setOptions



```php
private setOptions(): void
```












***

***
> Automatically generated on 2024-05-11


***

# Online





* Full name: `\EnvisionPortal\Modules\Online`
* This class implements:
[`\EnvisionPortal\ModuleInterface`](../ModuleInterface.md)



## Properties


### totals



```php
private $totals
```






***

### groups



```php
private $groups
```






***

### online_groups



```php
private $online_groups
```






***

### show_online



```php
private $show_online
```






***

### fields



```php
private $fields
```






***

## Methods


### getTotals



```php
public getTotals(): mixed
```












***

### __invoke

Invoke the module with an array of fields.

```php
public __invoke(array $fields): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$fields` | **array** | An array of fields to process. |





***

### __toString

Convert the module to its HTML representation.

```php
public __toString(): string
```









**Return Value:**

The HTML representation of the module.




***

### getDefaultProperties

Get the default properties of the module.

```php
public getDefaultProperties(): array
```









**Return Value:**

The default properties of the module.




***


***
> Automatically generated on 2024-05-12

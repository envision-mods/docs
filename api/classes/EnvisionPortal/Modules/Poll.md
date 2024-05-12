***

# Poll





* Full name: `\EnvisionPortal\Modules\Poll`
* This class implements:
[`\EnvisionPortal\ModuleInterface`](../ModuleInterface.md)



## Properties


### boards_can



```php
private array $boards_can
```






***

### pollinfo



```php
private $pollinfo
```






***

## Methods


### fetchPoll



```php
private fetchPoll(array $where, array $where_params): ?array
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$where` | **array** |  |
| `$where_params` | **array** |  |





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

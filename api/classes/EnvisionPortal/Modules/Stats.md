***

# Stats





* Full name: `\EnvisionPortal\Modules\Stats`
* This class implements:
[`\EnvisionPortal\ModuleInterface`](../ModuleInterface.md)



## Properties


### totals



```php
private $totals
```






***

### stat_choices



```php
private $stat_choices
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


## Inherited methods


### error

Generates an error message.

```php
public error(string $type = &#039;error&#039;, string $error_type = &#039;general&#039;, bool $log_error = false): string
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$type` | **string** | The type of error message. |
| `$error_type` | **string** | The type of error. |
| `$log_error` | **bool** | Whether to log the error. |


**Return Value:**

The error message.




***

### captureOutput

Captures the output of a callback function.

```php
private captureOutput(callable $callback, mixed $args): string
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$callback` | **callable** | The callback function to execute. |
| `$args` | **mixed** | Optional arguments to pass to the callback. |


**Return Value:**

The captured output.




***


***
> Automatically generated on 2024-05-12

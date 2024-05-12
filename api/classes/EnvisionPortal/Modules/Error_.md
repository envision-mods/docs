***

# Error_





* Full name: `\EnvisionPortal\Modules\Error_`



## Properties


### fields



```php
private $fields
```






***

## Methods


### __invoke



```php
public __invoke(array $fields): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$fields` | **array** |  |





***

### __toString



```php
public __toString(): mixed
```












***

### getDefaultProperties



```php
public getDefaultProperties(): array
```












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

***

# ModuleTrait

Trait providing common functionality for modules in Envision Portal.

This trait provides methods for handling errors and capturing output,
which can be used by modules to enhance their implementation.

* Full name: `\EnvisionPortal\ModuleTrait`




## Methods


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


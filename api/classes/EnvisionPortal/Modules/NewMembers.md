***

# NewMembers





* Full name: `\EnvisionPortal\Modules\NewMembers`
* This class implements:
[`\EnvisionPortal\ModuleInterface`](../ModuleInterface.md), [`\EnvisionPortal\SharedMemberDataInterface`](../SharedMemberDataInterface.md)



## Properties


### groups



```php
private $groups
```






***

## Methods


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

### fetchMemberIds

Returns member identifiers to load additional data on.

```php
public fetchMemberIds(): array
```

These ids are usually populated during invocation of this
module, then passed directly to SMF (loadMemberData() and
loadMemberContext(), respectively).  This is needed to combine
queries when multiple modules need to show member data.










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

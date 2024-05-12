***

# Recent





* Full name: `\EnvisionPortal\Modules\Recent`
* This class implements:
[`\EnvisionPortal\ModuleInterface`](../ModuleInterface.md)



## Properties


### topics



```php
private $topics
```






***

## Methods


### getTopics

Fetches the topics and their respective boards, ignoring those that the
user cannot see or wants to ignore. Returns an empty array if none are found.

```php
private getTopics(int $num_recent = 8, bool $ignore = true, array $exclude_boards = [], array $include_boards = []): array
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$num_recent` | **int** | Maximum number of topics to show. Default is 8. |
| `$ignore` | **bool** | Whether to honor ignored boards. Default is true. |
| `$exclude_boards` | **array** | Boards to exclude as array values. Default is null. |
| `$include_boards` | **array** | Boards to include as array values. Do note that, if<br />specifiied, posts coming only from these boards<br />will be counted. Default is null. |





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

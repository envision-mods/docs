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



```php
public error(mixed $type = &#039;error&#039;, mixed $error_type = &#039;general&#039;, mixed $log_error = false): string
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$type` | **mixed** |  |
| `$error_type` | **mixed** |  |
| `$log_error` | **mixed** |  |





***

### captureOutput



```php
private captureOutput(callable $callback, mixed $args): string
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$callback` | **callable** |  |
| `$args` | **mixed** |  |





***


***
> Automatically generated on 2024-05-11

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

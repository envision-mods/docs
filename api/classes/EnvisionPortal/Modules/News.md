***

# News





* Full name: `\EnvisionPortal\Modules\News`
* This class implements:
[`\EnvisionPortal\ModuleInterface`](../ModuleInterface.md)



## Properties


### posts



```php
private $posts
```






***

## Methods


### truncate

Cuts a string up until a given number of words.

```php
private truncate(string $str, mixed $n = 300, mixed $delim = &#039;…&#039;): string
```

- Doesn't slice words. It CAN interrupt a sentence, however...
- Preserves all whitespace characters.






**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$str` | **string** | The text string to split |
| `$n` | **mixed** |  |
| `$delim` | **mixed** |  |


**Return Value:**

The truncated string.




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

### findMessageIcons



```php
private findMessageIcons(mixed $icon): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$icon` | **mixed** |  |





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

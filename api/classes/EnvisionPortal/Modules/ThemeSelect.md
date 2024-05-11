***

# ThemeSelect





* Full name: `\EnvisionPortal\Modules\ThemeSelect`
* This class implements:
[`\EnvisionPortal\ModuleInterface`](../ModuleInterface.md)



## Properties


### available_themes



```php
private array $available_themes
```






***

### current_theme



```php
private int $current_theme
```






***

## Methods


### getThemeId

Resolves the ID of a theme.

```php
private getThemeId(): int
```

The identifier can be specified in:
- a GET variable
- the session
- user's preferences
- board
- forum default







**Return Value:**

Theme ID to load




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

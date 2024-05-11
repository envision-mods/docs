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



```php
public __invoke(array $fields): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$fields` | **array** |  |





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

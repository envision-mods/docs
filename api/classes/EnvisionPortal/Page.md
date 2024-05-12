# Page





* Full name: `\EnvisionPortal\Page`
* This class implements:
[`\EnvisionPortal\EntityInterface`](./EntityInterface.md), [`\ArrayAccess`](../ArrayAccess.md)



## Properties


### id



```php
public int $id
```






***

### slug



```php
public ?string $slug
```






***

### name



```php
public ?string $name
```






***

### type



```php
public ?string $type
```






***

### body



```php
public ?string $body
```






***

### permissions



```php
public ?array $permissions
```






***

### status



```php
public ?string $status
```






***

### description



```php
public ?string $description
```






***

### mode



```php
private \EnvisionPortal\PageModeInterface $mode
```






***

### views



```php
public int $views
```






***

## Methods


### __construct



```php
public __construct(int $id, ?string $slug, ?string $name, ?string $type, ?string $body, ?array $permissions, ?string $status, ?string $description, int $views): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$id` | **int** |  |
| `$slug` | **?string** |  |
| `$name` | **?string** |  |
| `$type` | **?string** |  |
| `$body` | **?string** |  |
| `$permissions` | **?array** |  |
| `$status` | **?string** |  |
| `$description` | **?string** |  |
| `$views` | **int** |  |





***

### getName



```php
public getName(): ?string
```












***

### getBody



```php
public getBody(): ?string
```












***

### isAllowed



```php
public isAllowed(): bool
```












***

### getDescription



```php
public getDescription(): ?string
```












***

### getId



```php
public getId(): int
```












***


## Inherited methods


### offsetExists

Whether the given offset exists.

```php
public offsetExists(mixed $offset): bool
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$offset` | **mixed** |  |





***

### offsetGet

Fetch the offset if it exists othwerwise return NULL.

```php
public offsetGet(mixed $offset): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$offset` | **mixed** |  |





***

### offsetSet

Assign the offset.

```php
public offsetSet(mixed $offset, mixed $value): void
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$offset` | **mixed** |  |
| `$value` | **mixed** |  |





***

### offsetUnset

Unset the offset.

```php
public offsetUnset(mixed $offset): void
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$offset` | **mixed** |  |





***


***
> Automatically generated on 2024-05-11

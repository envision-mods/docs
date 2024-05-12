***

# ArrayAccessTrait

Provides a uniform interface for accessing and modifying the properties
of an object as if it were an array.

Exposing an object as an array is necessary when interacting with SMF, such
as when using createList() to operate on an array of {@link} objects.

* Full name: `\EnvisionPortal\ArrayAccessTrait`




## Methods


### offsetExists

Check whether the given offset exists.

```php
public offsetExists(mixed $offset): bool
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$offset` | **mixed** | The offset to check. |


**Return Value:**

True if the offset exists, false otherwise.




***

### offsetGet

Retrieve the value of the given offset.

```php
public offsetGet(mixed $offset): mixed|null
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$offset` | **mixed** | The offset to retrieve. |


**Return Value:**

The value of the offset, or null if it does not exist.




***

### offsetSet

Set the value of the given offset.

```php
public offsetSet(mixed $offset, mixed $value): void
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$offset` | **mixed** | The offset to set. |
| `$value` | **mixed** | The value to assign to the offset. |





***

### offsetUnset

Unset the given offset.

```php
public offsetUnset(mixed $offset): void
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$offset` | **mixed** |  |





***

***
> Automatically generated on 2024-05-12


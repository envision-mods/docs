***

# Util

Utility class providing various helper functions.



* Full name: `\EnvisionPortal\Util`




## Methods


### decamelize

Convert a camelCase string to snake_case.

```php
public static decamelize(string $string): string
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$string` | **string** | The input string in camelCase format. |


**Return Value:**

The converted string in snake_case format.




***

### camelize

Convert a snake_case string to camelCase.

```php
public static camelize(string $string): string
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$string` | **string** | The input string in snake_case format. |


**Return Value:**

The converted string in camelCase format.




***

### find_integrated_classes

Find classes implementing a specified interface.

```php
public static find_integrated_classes(string $interface): \Generator
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$interface` | **string** | The fully qualified interface name. |


**Return Value:**

A generator yielding the found class names.




***

### map

Apply a callback to each element of the iterable.

```php
public static map(callable $callback, iterable $iterator): \Generator
```

Similar to array_map, but maps key-value pairs (tuples).

Applies the callback to the elements of the given iterable.
Original values (and keys) are lost during transformation!

The callback must return a list (array) with two elements; the
first one becomes the key and the second one becomes the value.

* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$callback` | **callable** | The callback function to apply. |
| `$iterator` | **iterable** | The iterable to apply the callback to. |


**Return Value:**

A generator yielding the results of applying the callback.




***

### find_classes

Find classes in a specified namespace implementing a specified interface.

```php
public static find_classes(\FilesystemIterator $iterator, string $ns, string $interface): \Generator
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$iterator` | **\FilesystemIterator** | The iterator for the namespace. |
| `$ns` | **string** | The namespace of the classes to search. |
| `$interface` | **string** | The fully qualified interface name. |


**Return Value:**

A generator yielding the found class names.




***

### replaceVars

Replace placeholders in a string with provided variables.

```php
public static replaceVars(string $template, array $variables): string
```

Example:
"The book {title} was written by {author_name}" becomes
"The book Harry Potter was written by J.K. Rowling"

* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$template` | **string** | The template string with placeholders. |
| `$variables` | **array** | The key-value store of variables and values. |


**Return Value:**

The processed template string.




***

### listGroups

Get a list of membergroups based on specified criteria.

```php
public listGroups(int[] $checked = [], bool $inherited = false): array
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$checked` | **int[]** | List of group IDs to be marked. |
| `$inherited` | **bool** | Whether to filter out inherited groups. |


**Return Value:**

The list of membergroups filtered according to the criteria.




***

### process

Process a list of items, sorting and slicing as needed.

```php
public static process(int $start, int $items_per_page, string $sort, array $list): array
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$start` | **int** | The index to start slicing from. |
| `$items_per_page` | **int** | The number of items per page. |
| `$sort` | **string** | The sorting criteria. |
| `$list` | **array** | The list of items to process. |


**Return Value:**

The processed list of items.




***


***
> Automatically generated on 2024-05-12

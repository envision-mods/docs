# Util





* Full name: `\EnvisionPortal\Util`




## Methods


### decamelize



```php
public static decamelize(string $string): string
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$string` | **string** |  |





***

### camelize



```php
public static camelize(string $string): string
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$string` | **string** |  |





***

### find_integrated_classes



```php
public static find_integrated_classes(string $interface): \Generator
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$interface` | **string** |  |





***

### map

Similar to array_map, but maps key-value pairs (tuples).

```php
public static map(callable $callback, iterable $iterator): \EnvisionPortal\Generator
```

Applies the callback to the elements of the given iterable.
Original values (and keys) are lost during transformation!

* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$callback` | **callable** | This must return a list with two<br />elements; the first one becomes the key<br />and the second one becomes the value. |
| `$iterator` | **iterable** | An iterable to run through $callback. |





***

### find_classes



```php
public static find_classes(\FilesystemIterator $iterator, string $ns, string $interface): \Generator
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$iterator` | **\FilesystemIterator** |  |
| `$ns` | **string** |  |
| `$interface` | **string** |  |





***

### replaceVars

Replaces placeholders from a string with the provided variables.

```php
public static replaceVars(string $template, array $array): string
```

Example:
"The book {title} was written by {author_name}" becomes "The book Harry Potter was written by J.K. Rowling"

* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$template` | **string** | A template with variables placeholders {$variable}. |
| `$array` | **array** |  |





***

### listGroups

Gets all membergroups and filters them according to the parameters.

```php
public listGroups(int[] $checked = [], bool $inherited = false): array
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$checked` | **int[]** | list of all id_groups to be checked (have a mark in the checkbox).<br />Default is an empty array. |
| `$inherited` | **bool** | Whether to filter out the inherited groups. Default is false. |


**Return Value:**

All the membergroups filtered according to the parameters; empty array if something went wrong.




***

### process



```php
public static process(int $start, int $items_per_page, string $sort, array $list): array
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$start` | **int** | The item to start with. |
| `$items_per_page` | **int** | How many items to show per page. |
| `$sort` | **string** | A string indicating how to sort results. |
| `$list` | **array** | Array of arrays or objects implementing<br />ArrayAccess to sort and slice. |


**Return Value:**

An array of info.




***


***
> Automatically generated on 2024-05-11

# Portal





* Full name: `\EnvisionPortal\Portal`



## Properties


### sharedModuleData



```php
private array $sharedModuleData
```






***

## Methods


### canSkipAction



```php
private static canSkipAction(mixed $da_action): bool
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$da_action` | **mixed** |  |


**Return Value:**

whether this is an attachment, avatar, toggle of editor buttons, theme option, XML feed, popup, etc.




***

### getMatch



```php
private getMatch(mixed $da_action): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$da_action` | **mixed** |  |





***

### getGeneralMatch



```php
private getGeneralMatch(): string
```












***

### getMatchedLayout



```php
private getMatchedLayout(mixed $da_action): ?int
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$da_action` | **mixed** |  |





***

### fromAction

Load a layout that is assigned to the current SMF action.

```php
public static fromAction(string|null $init_action = null): mixed
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$init_action` | **string&#124;null** |  |





***

### getLoadedLayoutFromName



```php
public static getLoadedLayoutFromName(string|null $init_action = null): array|null
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$init_action` | **string&#124;null** |  |





***

### loadModule



```php
public static loadModule(int $id_position): ?array
```



* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$id_position` | **int** |  |





***

### getLoadedLayoutFromId

Fetch a layout from the database based on ID.

```php
public static getLoadedLayoutFromId(int $id_layout, int $module_mode = 1): array|null
```

The returned data depends on the mode:

- `0`: Only return layout positions;
- `1`: Sane as `0`, but also load all module data;
- `2`: Same as `0`, but also load module titles.

* This method is **static**.




**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$id_layout` | **int** | Exact layout id as is from the database. |
| `$module_mode` | **int** | Mode. Returns `null` if out of bounds. |


**Return Value:**

Layout data or `null` if not found.




***

### main



```php
public static main(): mixed
```



* This method is **static**.








***

### loadLayoutData

Fetch a layout from the database based on ID.

```php
protected loadLayoutData(int $id_layout, int $module_mode = 1): array|null
```

The data to fetch from the depends on the mode:

- `0`: Only fetch layout positions;
- `1`: Also fetch module data from the database.






**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$id_layout` | **int** | Exact layout id as is from the database. |
| `$module_mode` | **int** | Mode. |


**Return Value:**

Layout data or `null` if not found.




***

### loadLayoutContext



```php
protected loadLayoutContext(array $data): array
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$data` | **array** |  |





***

### process_module



```php
private process_module(array $module_fields, array $data): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$module_fields` | **array** |  |
| `$data` | **array** |  |





***


***
> Automatically generated on 2024-05-11

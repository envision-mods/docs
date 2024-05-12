***

# ModuleInterface

Interface for defining modules in Envision Portal.

Modules are callable objects that provide properties which can be
configured by the admin to change the module's behavior.

* Full name: `\EnvisionPortal\ModuleInterface`



## Methods


### __invoke

Invoke the module with an array of fields.

```php
public __invoke(array $fields): mixed
```








**Parameters:**

| Parameter | Type | Description |
|-----------|------|-------------|
| `$fields` | **array** | An array of fields to process. |





***

### getDefaultProperties

Get the default properties of the module.

```php
public getDefaultProperties(): array
```









**Return Value:**

The default properties of the module.




***

### __toString

Convert the module to its HTML representation.

```php
public __toString(): string
```









**Return Value:**

The HTML representation of the module.




***


***
> Automatically generated on 2024-05-12

***

# SharedMemberDataInterface





* Full name: `\EnvisionPortal\SharedMemberDataInterface`



## Methods


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


***
> Automatically generated on 2024-05-12

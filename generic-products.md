# FSTab (Mount Points) Schema

```txt
https://ns.adobe.com/helix/shared/fstab
```

Defines a mapping between mount points and source URLs. Mount points **must** start with a slash (`/`) but may not end with one.

This configuration can typically be found in the `helix-fstab.yaml` file.

The name and format are inspired by the [UNIX file system table](https://en.wikipedia.org/wiki/Fstab).

| Abstract            | Extensible | Status         | Identifiable | Custom Properties | Additional Properties | Access Restrictions | Defined In                                                    |
| :------------------ | :--------- | :------------- | :----------- | :---------------- | :-------------------- | :------------------ | :------------------------------------------------------------ |
| Can be instantiated | No         | Unknown status | No           | Forbidden         | Forbidden             | none                | [fstab.schema.json](fstab.schema.json "open original schema") |

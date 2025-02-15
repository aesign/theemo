---
id: theemo.basetoken
title: BaseToken
hide_title: true
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[theemo](./theemo.md) &gt; [BaseToken](./theemo.basetoken.md)

## BaseToken interface

The base token, with all properties shared amongst various token types used throughout theemo.

<b>Signature:</b>

```typescript
export interface BaseToken 
```

## Remarks

That is, figma is subclassing this with its own token and specific figma-related properties.

## Properties

|  Property | Type | Description |
|  --- | --- | --- |
|  [colorScheme?](./theemo.basetoken.colorscheme.md) | string | <i>(Optional)</i> Indicates the color scheme, to which the token belongs |
|  [description?](./theemo.basetoken.description.md) | string | <i>(Optional)</i> The description for the token |
|  [name](./theemo.basetoken.name.md) | string | The tokens name |
|  [reference?](./theemo.basetoken.reference.md) | string | <i>(Optional)</i> The name of the reference this token points to |
|  [type?](./theemo.basetoken.type.md) | string | <i>(Optional)</i> The type helps token translation tools to generate the respective value in the appropriate format. |

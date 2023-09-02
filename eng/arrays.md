# Arrays

[← Primitives](./primitives.md) | [Index](./index.md) | [Composites →](./composites.md)

> **NOTE**
> As stated in the [style](./style.md) doc, identifiers that are written in snake-case and enclosed in `<>` are meta variables. For example below `Array[<lower>:<upper>]` could potentially be written as `Array[0:5]`.

## Declaring

1. One-dimensional
```
  DECLARE <identifier> : Array[<lower>:<upper>] OF <type>
```
2. Two-dimensional
```
  DECLARE <identifier> : Array[<lower>:<upper>, <lower>:<upper>] OF <type>
```

## Using

1. Access item
```
  <array_identifier>[<index>]
```
2. Access range of items
```
  <array_identifier>[<lower>:<upper>]
```
3. Add item to start
```
  <array_identifier>.add_to_start(<item>)
```
4. Add item to end
```
  <array_identifier>.add_to_end(<item>)
```
5. Remove from start
```
  <array_identifier>.remove_from_start()
```
6. Remove from end
```
  <array_identifier>.remove_from_end()
```
7. Assign to index
```
  <array_identifier>[<index>] ← <item>
```

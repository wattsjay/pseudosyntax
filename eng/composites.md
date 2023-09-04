# Composites

[← Arrays](./arrays.md) | [Index](../readme.md) | [Enumerations →](./enumerations.md)

## Declaring

If you would like to make a property optional, you can add the `OPTIONAL` keyword after the `DECLARE` keyword.

```
  TYPE <identifier>
    DECLARE <property_identifier>: <type>
    DECLARE OPTIONAL <property_identifier>: <type>
  ENDTYPE
```

## Initializing

```
  DECLARE <identifier> : <type>
  DECLARE <identifier>.<property_identifier> ← <value>
```

## Using

```
  <identifier>.<property_identifier>
```
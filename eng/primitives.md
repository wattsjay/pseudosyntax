# Primitives

[← Style](./style.md) | [Index](./index.md) | [Arrays →](./arrays.md)

## Types

1. Integer: whole number.
```
  DECLARE count : Integer ← 618  
```
2. Float: a factional number.
```
  DECLARE golden_ratio : Float ← 1.618  
```
3. Char: a single character.
```
  DECLARE operator : Char ← '<'  
```
4. String: a sequence of characters.
```
  DECLARE name_and_surname : String ← 'John Doe'  
```
5. Boolean: true OR false.
```
  DECLARE is_read : Boolean ← false  
```
6. Date: A calendar date in the format of `YYYY-MM-DD`.
```
  DECLARE birthday : Date ← '1984-06-30'  
```
7. Literal: A primitive with a set value.
```
  CONSTANT frames_per_second ← 60 // It does not have a Type annotation
```
8. Function or Procedures
```
  // This only applies to functions and procedures
  // used as types.
  (args) => Boolean
```

## Variables

```
  DECLARE <identifier> : <type>
```

## Constants

Constants have to be initialized and because they are literals, they are not given type declarations.

```
  CONSTANT <identifier> ← <value>
```

## Assignments

Assignments are not denoted with the `=` symbol, but rather `←` (Unicode 2190).

```
  <identifier> ← <value>
```
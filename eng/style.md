# Style

[Index](../readme.md) | [Primitives →](./primitives.md)

## Case

1. Keywords are in _upper-case_.
```
  IF <condition>
  ENDIF
```
2. Identifiers, properties, and methods are in _snake-case_.
```
  number_of_items : Integer ← 100
  DECLARE user.date_of_birth ← 1984
```
3. Types and Classes are in _camel-case_.
```
  items : PriorityQueue ← [] 
```
3. Meta-variables are enclosed in <> and in _snake-case_.
```
  WHILE <condition>
  ENDWHILE
```

## Quotes

Single quotes are to be used over double quotes.

```
  DECLARE name : String ← 'John Doe'
```

## Comments

Single-, multi-, or in-line comments are preceded by two forward slashes `//`.
```
  // Multi line comment
  // with each line preceded with
  // double slashes.
  IF <condition>
    // Single line comment
    CALL print('foo bar baz') // in-line comment
  ENDIF
```
# Object-Oriented-Programming

[← Procedures & Functions](./procedures_and_functions.md) | [Index](../readme.md)

## Methods and Properties

Methods and properties are public unless stated otherwise.

```
  PRIVATE count : Integer ← 10

  PROCEDURE setCount(newCount: Integer)
    count ← newCount
  ENDPROCEDURE

  PRIVATE FUNCTION getCount() RETURNS Integer
    RETURN count
  ENDFUNCTION
```

## Constructors

```
  CLASS <identifier>
    CONSTRUCTOR()
      // statements
    ENDCONSTRUCTOR
  ENDCLASS
```

## Inheritance

```
  ABSTRACT CLASS Foo
    // body
  ENDCLASS

  CLASS Bar INHERITS Foo
    // body
  ENDCLASS
```

## Instantiation

```
  DECLARE <identifier> ← NEW <ClassIdentifier>()
```
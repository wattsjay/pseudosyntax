# Procedures & Functions

[← Iterations](./iterations.md) | [Index](../readme.md) | [OOP →](./oop.md)

> **NOTE**
> Procedures do not return a value, while functions do.

## Defining Procedures

```
  PROCEDURE <identifier>()
    // statements
  ENDPROCEDURE
```

With parameters:

```
  PROCEDURE <identifier>(<param1>: <Type>, <param2>: <Type>)
    // statements
  ENDPROCEDURE
```

## Calling Procedures

```
  CALL <identifier>()
```

## Defining Functions

Generally the same as procedures, but functions have to specify their return type as well as return a value.

```
  FUNCTION <identifier>(<param1>: <Type>) RETURNS <Type>
    // statements
    RETURN <value>
  ENDFUNCTION
```

## Calling Functions

Same as procedures.

```
  CALL <identifier>()
```


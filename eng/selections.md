# Selections

[← Operations](./operations.md) | [Index](../readme.md) | [Iterations →](./iterations.md)

## IF

Else clauses are not required.

```
  IF <condition> THEN
    // statements
  ENDIF  
```

```
  IF <condition> THEN
    // statements
  ELSE
    // statements
  ENDIF
```

## CASE

An otherwise clause can be the last case.

```
  CASE OF <identifier>
    <value 1>:  <statement 1>
                <statement 2>
    <value 2>:  <statement 1>
                <statement 2>
  ENDCASE
```
  
```
  CASE OF <identifier>
    <value>:   <statement>
    OTHERWISE: <statement>
  ENDCASE
```
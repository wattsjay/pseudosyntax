# Iterations

[← Selections](./selections.md) | [Index](../readme.md) | [Procedures & Functions →](./procedures_and_functions.md)

## FOR

Identifiers must be a variable of type `Integer`.

```
  FOR <identifier> ← <value1> TO <value2>
    // statements
  NEXT <identifier>
```

Identifiers can be incremented as follows using the `STEP` keyword:

```
  FOR <identifier> ← <value1> TO <value2> STEP <increment>
    // statements
  NEXT <identifier>
```

## REPEAT (Post-condition)

```
  REPEAT
    // statements
  UNTIL <condition>
```

## WHILE (Pre-condition)

```
  WHILE <condition>
    // statements
  ENDWHILE
```
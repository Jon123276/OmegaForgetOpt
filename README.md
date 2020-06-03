# Optimizing OF

## The read.

```
Record like normal, but do both base 36 -> base 8 and base 64 -> base 10.
```

### How to do base conversion.

#### Base 36 -> Base 8.

##### Step 1

```
Do the first digit/(letter+9), multiply it by 36, then add the second number/(letter+9).
```

##### Step 2

```
Modulo 8 for the digit, divide 8 to get the new number, and floor. Do this step till you get to 0.
```

#### Base 64 -> Base 10.

##### Before anything happens.

```
Keep in mind that A = 0 and 0 = 52.
```

##### Step 1

```
Convert both characters from base 64, then multiply the first value with 64 before adding both together.
```


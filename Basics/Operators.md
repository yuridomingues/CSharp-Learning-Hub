# Operators in C#

## What are Operators?

An operator is used to perform specific functions or calculations within a program.  
Example: Assigning a value to a variable with the `=` operator.

---

## Types of Operators

- Arithmetic Operators
- Relational Operators
- Logical Operators
- Assignment Operators
- Bitwise Operators

---

## 1. Arithmetic Operators

These operators are used to perform basic arithmetic operations.

```csharp
int a = 2;
int b = 8;
```

| Operator | Description               | Example       | Result |
|----------|---------------------------|---------------|--------|
| `+`      | Addition                  | `a + b`       | `10`   |
| `-`      | Subtraction               | `a - b`       | `-6`   |
| `*`      | Multiplication            | `a * b`       | `16`   |
| `/`      | Division                  | `b / a`       | `4`    |
| `%`      | Modulus (remainder)       | `7 % 2`       | `1`    |
| `++`     | Increment the value by 1  | `a++` (post)  | `3`    |
| `--`     | Decrement the value by 1  | `a--` (post)  | `1`    |

---

## 2. Relational Operators

These operators are used to compare values.

```csharp
int a = 2;
int b = 4;
```

| Operator | Description                             | Example       | Result  |
|----------|-----------------------------------------|---------------|---------|
| `==`     | Checks if values are equal              | `a == b`      | `False` |
| `!=`     | Checks if values are not equal          | `a != b`      | `True`  |
| `>`      | Checks if left value is greater         | `b > a`       | `True`  |
| `<`      | Checks if left value is smaller         | `a < b`       | `True`  |
| `>=`     | Checks if left value is greater or equal| `b >= a`      | `True`  |
| `<=`     | Checks if left value is less or equal   | `a <= b`      | `True`  |

---

## 3. Logical Operators

These operators are used to combine or invert logical conditions.

```csharp
int a = 2;
int b = 4;
```

| Operator | Description                            | Example                  | Result  |
|----------|----------------------------------------|--------------------------|---------|
| `&&`     | Logical AND: Both conditions must be true. | `(a == 2 && b == 4)` | `True`  |
| `||`     | Logical OR: At least one condition is true. | `(a == 2 || b == 2)`| `True`  |
| `!`      | Logical NOT: Inverts the logical state. | `!(a == 2)`             | `False` |

---

## 4. Assignment Operators

These operators assign or modify values in variables.

```csharp
int a = 2;
int b = 4;
```

| Operator | Description                                      | Example       | Result  |
|----------|--------------------------------------------------|---------------|---------|
| `=`      | Assigns the value to a variable.                 | `c = a + b`   | `6`     |
| `+=`     | Adds the value and assigns the result.           | `a += 1`      | `3`     |
| `-=`     | Subtracts the value and assigns the result.      | `a -= 1`      | `1`     |
| `*=`     | Multiplies the value and assigns the result.     | `a *= 2`      | `4`     |
| `/=`     | Divides the value and assigns the result.        | `b /= 2`      | `2`     |
| `%=`     | Finds the remainder and assigns the result.      | `b %= 2`      | `0`     |

---

## 5. Bitwise Operators

Bitwise operators work at the bit level.

```csharp
int a = 2;
int b = 4;
```

| Operator | Description                                  | Example  | Result  |
|----------|----------------------------------------------|----------|---------|

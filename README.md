# Bitwise-Operators-in-C-

# C++ Operators and Their Usage

## Aim
To study and implement various operators in C++, including bitwise, assignment, miscellaneous operators, and understand operator precedence.

---

## Bitwise Operators

Bitwise operators perform operations on the binary representation of integers.

| Operator | Description                                                             | Example Result                        |
|----------|-------------------------------------------------------------------------|----------------------------------------|
| `&`      | AND: Copies bit if it exists in both operands                          | `A & B` → `12 (00001100)`              |
| '|'     | OR: Copies bit if it exists in either operand                          | `A | B` → `61 (00111101)`              |
| `^`      | XOR: Copies bit if it exists in one operand but not both               | `A ^ B` → `49 (00110001)`              |
| `~`      | One's Complement: Flips all bits (unary operator)                      | `~A` → `-61 (in 2's complement)`       |
| `<<`     | Left Shift: Shifts bits to the left                                    | `A << 2` → `240 (11110000)`            |
| `>>`     | Right Shift: Shifts bits to the right                                  | `A >> 2` → `15 (00001111)`             |

---

## Assignment Operators

Used to assign and manipulate values in variables.

| Operator | Description                                              | Example                |
|----------|----------------------------------------------------------|------------------------|
| `=`      | Simple assignment                                        | `C = A + B`            |
| `+=`     | Add AND assign                                            | `C += A` → `C = C + A` |
| `-=`     | Subtract AND assign                                       | `C -= A` → `C = C - A` |
| `*=`     | Multiply AND assign                                       | `C *= A` → `C = C * A` |
| `/=`     | Divide AND assign                                         | `C /= A` → `C = C / A` |
| `%=`     | Modulus AND assign                                        | `C %= A` → `C = C % A` |
| `<<=`    | Left shift AND assign                                     | `C <<= 2`              |
| `>>=`    | Right shift AND assign                                    | `C >>= 2`              |
| `&=`     | Bitwise AND AND assign                                    | `C &= 2`               |
| `^=`     | Bitwise XOR AND assign                                    | `C ^= 2`               |

---

## Miscellaneous Operators

| Sr.No | Operator         | Description                                                                 |
|-------|------------------|-----------------------------------------------------------------------------|
| 1     | `sizeof`         | Returns the size of a variable (e.g., `sizeof(a)` → `4`)                    |
| 2     | `?:`             | Ternary conditional operator                                                |
| 3     | `,`              | Evaluates multiple expressions; returns the last                            |
| 4     | `.` and `->`     | Access members of structures/unions                                         |
| 5     | Cast             | Converts data types (e.g., `int(2.2000)` → `2`)                             |
| 6     | `&`              | Returns the address of a variable                                           |
| 7     | `*`              | Pointer to a variable                                                       |

---

## Operator Precedence in C++

Operator precedence determines how expressions are evaluated.

| Category       | Operators                                 | Associativity     |
|----------------|-------------------------------------------|-------------------|
| Postfix        | `() [] -> . ++ --`                        | Left to Right     |
| Unary          | `+ - ! ~ ++ -- (type)* & sizeof`          | Right to Left     |
| Multiplicative | `* / %`                                   | Left to Right     |
| Additive       | `+ -`                                     | Left to Right     |
| Shift          | `<< >>`                                   | Left to Right     |
| Relational     | `< <= > >=`                               | Left to Right     |
| Equality       | `== !=`                                   | Left to Right     |
| Bitwise AND    | `&`                                       | Left to Right     |
| Bitwise XOR    | `^`                                       | Left to Right     |
| Bitwise OR     | `|`                                       | Left to Right     |
| Logical AND    | `&&`                                      | Left to Right     |
| Logical OR     | `||`                                      | Left to Right     |
| Conditional    | `?:`                                      | Right to Left     |
| Assignment     | `= += -= *= /= %= >>= <<= &= ^= |=`       | Right to Left     |
| Comma          | `,`                                       | Left to Right     |

---

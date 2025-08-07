Aim:
To implement bitwise operators and bit manipulation (set/reset bit) in C++.

Algorithm:
(01) Bitwise Operators in C++
Start the program.

Declare two integer variables a and b, and assign values (e.g., a = 5, b = 3).

Calculate bitwise AND of a and b, store it in bitwise_and.

Calculate bitwise OR of a and b, store it in bitwise_or.

Calculate bitwise XOR of a and b, store it in bitwise_xor.

Calculate bitwise NOT of a, store it in bitwise_not.

Calculate left shift of a by 2 positions, store it in left_shift.

Calculate right shift of a by 1 position, store it in right_shift.

Print the results of all bitwise operations.

End the program.

(02) Setting and Resetting a Bit
Start the program.

Declare two integer variables: number and bitPosition.

Prompt the user to enter an integer and read the value into number.

Prompt the user to enter the bit position to modify and read the value into bitPosition.

Set the bit at bitPosition using the expression (number | (1 << bitPosition)) and print the result.

Reset the bit at bitPosition using the expression (number & (~(1 << bitPosition))) and print the result.

End the program.

Theory:
(01) Bitwise Operators in C++
This program demonstrates bitwise operators using two integers a and b.

It uses:

Bitwise AND (&)

Bitwise OR (|)

Bitwise XOR (^)

Bitwise NOT (~)

Left Shift (<<)

Right Shift (>>)

These operations help in understanding how binary data is manipulated at the bit level.

The results of all operations are stored in separate variables and displayed using cout.

(02) Setting and Resetting a Bit
This program allows users to modify a specific bit in an integer using bitwise operators.

The user inputs an integer number and a bit position (starting from 0 for LSB).

To set a bit, the expression (number | (1 << bitPosition)) is used.

1 << bitPosition creates a binary mask with 1 at the target position.

| (bitwise OR) sets that bit to 1 while preserving other bits.

To reset a bit, the expression (number & (~(1 << bitPosition))) is used.

~(1 << bitPosition) creates a mask with 0 at the target bit.

& (bitwise AND) clears that bit to 0 while keeping others unchanged.

Conclusion:
Both programs demonstrate bitwise manipulation in C++:

The first program showcases how to use fundamental bitwise operators for logical operations on binary data.

The second program demonstrates practical bitwise techniques to set and reset specific bits — crucial in low-level programming, embedded systems, and performance optimization.

These programs provide a clear understanding of bit-level logic and how C++ can be used for efficient data manipulation.


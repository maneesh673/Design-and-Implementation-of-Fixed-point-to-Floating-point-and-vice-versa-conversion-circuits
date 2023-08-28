# Implementation-of-Fixed-point-to-Floating-point-and-vice-versa-converter-circuits
Design and implement the following circuits using Verilog:
• Fixed point representation (n-bits for integer, m-bits for decimal) to Floating point representation (1-bit for sign, e-bits for exponent, m-bits for mantissa) converter
• Floating point representation (1-bit for sign, e-bits for exponent, m-bits for mantissa) to
fixed point representation (n-bits for integer, m-bits for decimal) convertor

# THEORY
Real numbers can be represented as floating-point numbers in a computer system. A number with both a fractional portion and an exponent is referred to as a floating-point number. The fractional portion of the integer represents its accuracy, while the exponent determines its size. The IEEE 754 standard, which stipulates a binary representation for floating-point numbers, is a widely used floating-point format. This standard uses 32 or 64 bits to represent floatingpoint numbers. These bits are split into three fields: a sign bit, an exponent field, and a fraction
field. The exponent field holds the exponent value, the fraction field stores the fractional portion of the number, and the sign bit denotes the sign of the number. The range and precision of the  floating-point number representation depend on the size of the exponent field and fraction field.Fixed-point numbers have a fixed amount of bits for the fractional component and the integer part, unlike floating-point numbers, which have a fractional part and an exponent. The binary point, which divides the input into an integer and a fractional portion, has a fixed location in a fixed-point format. The number of bits utilized to represent each part can be
used to specify the size of the integer and fractional parts. For instance, in a 16-bit fixed-point format, the integer and fractional parts may each require 8 bits.

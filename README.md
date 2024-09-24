# Binary Addition 
Binary addition is like regular addition, but instead of using the numbers 0 through 9, it only uses 0 and 1. Think of it like counting with just two fingers! When you add two binary numbers, you follow these simple rules:

0 + 0 = 0 (nothing plus nothing is still nothing!)

0 + 1 = 1 (adding one to nothing gives you one)

1 + 0 = 1 (same as above)

1 + 1 = 10 (this is where it gets a little tricky—1 plus 1 equals 2, but since we only have 0s and 1s, we write it as "10," meaning 0 and carry over a 1 to the next column).

It’s just like how in regular addition, sometimes you carry over a number when the total is more than 9.

# Half Adders

A half adder is a simple machine used in computers to help them add two small numbers together, just like when you add numbers in math class. 
But instead of adding big numbers, a half adder only adds two tiny numbers, either 0 or 1.

# Truth Table for a Half Adder

![image](https://github.com/user-attachments/assets/4279e31a-8d78-4584-b94f-a06585b8a226)

Here’s how it works:

If both numbers are 0 (like two tails on coins), the sum is 0, and there’s no carry.

If one number is 0 and the other is 1 (like a heads and a tails), the sum is 1, and still no carry.

If one number is 1 and the other is 0 (like heads and tails), the sum is 1, and still no carry.

If both numbers are 1 (like two heads), the sum is 0, but now there’s a carry of 1 because the total becomes 2 (which is too big to fit in one place, so the extra goes to the carry).

# Truth table for a half adder; outputs match XOR, AND

![image](https://github.com/user-attachments/assets/52e42979-4531-44e7-8dd9-773833f2c93b)


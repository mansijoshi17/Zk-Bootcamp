## Answers

**1. Modular arithmetic - you just need to find examples, you don't need to prove anything.**
   **1. Is it true that all odd squares are ≡ 1 (mod 8) ?**
   **2.  what about even squares (mod 8) ?**

All odd squares are congruent to 1 modulo 8: (2k + 1)<sup>2</sup> = 1 (mod 8).
All even squares are congruent to 0 modulo 8: (2k)<sup>2</sup> = 1 (mod 8).

**2. Try out the vanity bitcoin address example at asecurity or the Ethereum version**

**3. What do you understand by**
   **1. O(n)**
   **2. O(1)**
   **3. O(log n)**
**For a proof size, which of these would you want ?**

O(n): This is called linear time complexity. It means that the running time of the algorithm grows linearly with the size of the input. If the input size doubles, the running time also doubles.

O(1): This is constant time complexity. It means that the running time of the algorithm is constant. The efficiency of the algorithm does not depend on the input size.

O(log n): This is logarithmic time complexity. It often represents algorithms that divide the problem into smaller sub-problems in each step. 

For a proof size, We will typically prefer algorithms with lower time complexity, as they are more efficient, especially for large inputs. Therefore, O(1) is the most desirable, as the running time is constant, regardless of input size. 

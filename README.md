# DSAIUebung-002 --  

To prove the equivalence 𝑃≡𝑄 where:
P≡¬(A∨B)
Q≡¬A∧¬B,
we will construct a truth table for both P and 𝑄 and compare their truth values in all cases. If the truth values for 𝑃 and 𝑄 match in every case, then 𝑃≡𝑄.

Step 1: Build the truth table
The truth table will include columns for 
𝐴
A, 
𝐵
B, 
𝐴
∨
𝐵
A∨B, 
¬
(
𝐴
∨
𝐵
)
¬(A∨B), 
¬
𝐴
¬A, 
¬
𝐵
¬B, and 
¬
𝐴
∧
¬
𝐵
¬A∧¬B. We need to compute the truth values for both formulas based on all possible truth assignments to 
𝐴
A and 
𝐵
B.

𝐴
A	
𝐵
B	
𝐴
∨
𝐵
A∨B	
¬
(
𝐴
∨
𝐵
)
¬(A∨B)	
¬
𝐴
¬A	
¬
𝐵
¬B	
¬
𝐴
∧
¬
𝐵
¬A∧¬B
T	T	T	F	F	F	F
T	F	T	F	F	T	F
F	T	T	F	T	F	F
F	F	F	T	T	T	T
Step 2: Compare 
𝑃
≡
¬
(
𝐴
∨
𝐵
)
P≡¬(A∨B) and 
𝑄
≡
¬
𝐴
∧
¬
𝐵
Q≡¬A∧¬B
From the truth table:

𝑃
=
¬
(
𝐴
∨
𝐵
)
P=¬(A∨B) gives the column 
¬
(
𝐴
∨
𝐵
)
¬(A∨B).
𝑄
=
¬
𝐴
∧
¬
𝐵
Q=¬A∧¬B gives the column 
¬
𝐴
∧
¬
𝐵
¬A∧¬B.
The truth values of 
𝑃
P and 
𝑄
Q match in every row of the truth table.

Conclusion
Since the truth values for 
𝑃
P and 
𝑄
Q are identical in all cases, we conclude that:

𝑃
≡
𝑄
P≡Q
Thus, 
¬
(
𝐴
∨
𝐵
)
≡
¬
𝐴
∧
¬
𝐵
¬(A∨B)≡¬A∧¬B. This is an example of De Morgan's Law.

# DSAIUebung-002 -- AussagenLogik  

# <p align="center"> 1 a </p>  
### *To* **prove the equivalence `𝑃 ≡ 𝑄`** *where*:  
  - `𝑃 ≡ ¬(𝐴 ∨ 𝐵)`  
  - `𝑄 ≡ ¬𝐴 ∧ ¬𝐵`  

    > *we will construct a truth table for both `𝑃` & `𝑄` and compare their truth values in all cases.  
    > If the truth values for `𝑃` & `𝑄` match in every case, then `𝑃 ≡ 𝑄`.*  

### Step 1 ) *Build the truth table*  

The truth table will *include columns* for `𝐴`, `𝐵`, `𝐴 ∨ 𝐵`, `¬(𝐴 ∨ 𝐵)`, `¬𝐴`, `¬𝐵`, `¬𝐴 ∧¬𝐵`.   
We need to compute the truth values for both formulas based on all possible truth assignments.  

<div align="center">

| 𝐴 | 𝐵 | 𝐴∨𝐵 | ¬(𝐴∨𝐵) | ¬𝐴 | ¬𝐵 | ¬𝐴∧¬𝐵 |  
|:-:|:-:|:----:|:------:|:--:|:--:|:------:|  
| T | T |   T  |  **F** |  F |  F |  **F** |  
| T | F |   T  |  **F** |  F |  T |  **F** |  
| F | T |   T  |  **F** |  T |  F |  **F** |  
| F | F |   F  |  **T** |  T |  T |  **T** |  
</div>

### Step 2 ) *Compare*   
  - `𝑃 ≡ ¬(𝐴 ∨ 𝐵)`  
  - `𝑄 ≡ ¬𝐴 ∧ ¬𝐵`  

#### *From the truth table*:  
  > - **`𝑃 ≡ ¬(𝐴 ∨ 𝐵)`** *gives the column* **`¬(𝐴 ∨ 𝐵)`**.
  > - **`𝑄 ≡ ¬𝐴 ∧ ¬𝐵` ** *gives the column* **`¬𝐴 ∧¬𝐵`**.  
  > - *The* **truth values of `𝑃` & `𝑄` match in every row** *of the truth table*.  

## Step 3) *Conclusion*  

  ***Since the truth values for `𝑃` & `𝑄` are  identical in all cases, we conclude that***:  

## <p align="center"> 𝑃 ≡ 𝑄 </p>  
### <p align="center"> therefor:  ¬(𝐴 ∨ 𝐵) ≡ ¬𝐴 ∧¬𝐵. </p>  

> *<p align="right"> This is an example of De Morgan's Law </p>*  

---  

# <p align="center"> 1 b </p>  

### *To* **prove the equivalence 𝑃 ≡ 𝐴** *where*:  
  - 𝑃≡𝐴  ⟹  ¬𝐵  
  - 𝑄≡¬(𝐴∧𝐵)  
  
  > *To show that 𝑃≡𝑄 , we'll construct a truth table and compare the truth values for both 𝑃& 𝑄.  
  > If the truth values match for all combinations of 𝐴 & 𝐵, then 𝑃≡𝑄.*  

### Step 1 ) *Build the truth table*  
 
 

𝐴
A	
𝐵
B	
𝐴
∧
𝐵
A∧B	
¬
(
𝐴
∧
𝐵
)
¬(A∧B)	
¬
𝐵
¬B	
𝐴
  
⟹
  
¬
𝐵
A⟹¬B
T	T	T	F	F	F
T	F	F	T	T	T
F	T	F	T	F	T
F	F	F	T	T	T
Step 3: Compare 
𝑃
≡
𝐴
  
⟹
  
¬
𝐵
P≡A⟹¬B and 
𝑄
≡
¬
(
𝐴
∧
𝐵
)
Q≡¬(A∧B)
The column for 
𝑃
=
𝐴
  
⟹
  
¬
𝐵
P=A⟹¬B matches the column for 
𝑄
=
¬
(
𝐴
∧
𝐵
)
Q=¬(A∧B) in all rows of the truth table.
Conclusion
Since the truth values for 
𝑃
P and 
𝑄
Q are identical for every possible truth assignment of 
𝐴
A and 
𝐵
B, we conclude that:

𝑃
≡
𝑄
P≡Q
Thus, 
𝐴
  
⟹
  
¬
𝐵
≡
¬
(
𝐴
∧
𝐵
)
A⟹¬B≡¬(A∧B). This equivalence also follows from the properties of implication and De Morgan's laws.
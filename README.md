# DSAIUebung-002 -- AussagenLogik  

# 1a )  
### *To* **prove the equivalence 𝑃 ≡ 𝑄** *where*:  
  - 𝑃 ≡ ¬(𝐴 ∨ 𝐵)  
  - 𝑄 ≡ ¬𝐴 ∧ ¬𝐵  

    > *we will construct a truth table for both P and 𝑄 and compare their truth values in all cases.  
    > If the truth values for 𝑃 and 𝑄 match in every case, then 𝑃 ≡ 𝑄.*  

### Step 1 ) *Build the truth table*  

The truth table will *include columns* for 𝐴, 𝐵, 𝐴 ∨ 𝐵, ¬(𝐴 ∨ 𝐵), ¬𝐴, ¬𝐵, ¬𝐴 ∧¬𝐵.   
We need to compute the truth values for both formulas based on all possible truth assignments.  

| 𝐴 | 𝐵 | 𝐴∨𝐵 | ¬(𝐴∨𝐵) | ¬𝐴 | ¬𝐵 | ¬𝐴∧¬𝐵 |  
|:-:|:-:|:----:|:------:|:--:|:--:|:------:|  
| T | T |   T  |  **F** |  F |  F |  **F** |  
| T | F |   T  |  **F** |  F |  T |  **F** |  
| F | T |   T  |  **F** |  T |  F |  **F** |  
| F | F |   F  |  **T** |  T |  T |  **T** |  


### Step 2 ) *Compare*   

  - 𝑃 ≡ ¬(𝐴 ∨ 𝐵)  
  - 𝑄 ≡ ¬𝐴 ∧¬𝐵  

#### *From the truth table*:  
  > - **𝑃 = ¬(𝐴∨𝐵)** *gives the column* **¬(𝐴 ∨ 𝐵)**.
  > - **𝑄 = ¬𝐴 ∧¬𝐵** *gives the column* **¬𝐴 ∧¬𝐵**.  
  > - *The* **truth values of 𝑃 & 𝑄 match in every row** *of the truth table*.  

## Step 3) *Conclusion*  

 - ***Since the truth values for 𝑃 & 𝑄 are  identical in all cases, we conclude that***:  


 - ### 𝑃 ≡ 𝑄 therefor ¬(𝐴 ∨ 𝐵) ≡ ¬𝐴 ∧¬𝐵.  

> *This is an example of* ***De Morgan's Law***.  

---  


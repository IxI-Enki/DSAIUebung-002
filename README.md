<!-- ============================================================================================================ -->
<!--                         made by               Jan Ritt       -       https://github.com/IxI-Enki                                                                                                                                                                     -->
<!-- ============================================================================================================ -->

<div style="page-break-before: always;">

# DSAIUebung-002 -- AussagenLogik  

## <p align="center"> 1 - Using Truth Tables </p>  
### <p align="left"> 1 a ) </p>  
### *To* **prove the equivalence `𝑃 ≡ 𝑄`** *where*:  
  - `𝑃 ≡ ¬(𝐴 ∨ 𝐵)`  
  - `𝑄 ≡ ¬𝐴 ∧ ¬𝐵`  

    > *we will construct a truth table for both `𝑃` & `𝑄` and compare their truth values in all cases.  
    > If the truth values for `𝑃` & `𝑄` match in every case, then `𝑃 ≡ 𝑄`.*  

### - *Build the truth table*  

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

### - *Compare*   
  - `𝑃 ≡ ¬(𝐴 ∨ 𝐵)`  
  - `𝑄 ≡ ¬𝐴 ∧ ¬𝐵`  

#### *From the truth table*:  
  > - **`𝑃 ≡ ¬(𝐴 ∨ 𝐵)`** *gives the column* **`¬(𝐴 ∨ 𝐵)`**.
  > - **`𝑄 ≡ ¬𝐴 ∧ ¬𝐵`** *gives the column* **`¬𝐴 ∧¬𝐵`**.  
  > - *The* **truth values of `𝑃` & `𝑄` match in every row** *of the truth table*.  

## - *Conclusion*  

  ***Since the truth values for `𝑃` & `𝑄` are  identical in all cases, we conclude that***:  

## <p align="center"> `𝑃 ≡ 𝑄` </p>  
### <p align="center"> therefor:  `¬(𝐴 ∨ 𝐵) ≡ ¬𝐴 ∧¬𝐵`. </p>  

> *<p align="right"> This is an example of De Morgan's Law </p>*  

</div>


<div style="page-break-before: always;">

### <p align="left"> 1 b ) </p>  

### *To* **prove the equivalence `𝑃 ≡ 𝐴`** *where*:  
  - `𝑃 ≡ 𝐴  ⟹  ¬𝐵`  
  - `𝑄 ≡ ¬(𝐴 ∧ 𝐵)`  
  
  > *To show that `𝑃 ≡ 𝑄` , we'll construct a truth table and compare the truth values for both `𝑃` & `𝑄`.  
  > If the truth values match for all combinations of `𝐴` & `𝐵`, then `𝑃 ≡ 𝑄`.*  

### - *Build the truth table*  
 
 <div align="center"> 

| 𝐴 | 𝐵 | 𝐴∧𝐵 | ¬(𝐴∧𝐵) | ¬𝐵 | 𝐴⟹¬𝐵 |  
|:-:|:-:|:----:|:-------:|:--:|:------:|    
| T | T |   T  |  **F**  |  F | **F**  |    
| T | F |   F  |  **T**  |  T | **T**  |    
| F | T |   F  |  **T**  |  F | **T**  |    
| F | F |   F  |  **T**  |  T | **T**  |    
</div> 

### - *Compare*  
  - `𝑃 ≡ 𝐴  ⟹  ¬𝐵`  
  - `𝑄 ≡ ¬(𝐴 ∧ 𝐵)`  
 
#### *From the truth table*:  
  > - *The* **truth values of `𝑃 ≡ 𝐴  ⟹  ¬𝐵` match the columns of `𝑄 ≡ ¬(𝐴 ∧ 𝐵)` in every row**.  

 
## - *Conclusion*  

  ***Since the truth values for `𝑃` & `𝑄` are identical in all cases, we conclude that***:  

## <p align="center"> `𝑃 ≡ 𝑄` </p>  
### <p align="center"> therefor:  `𝐴  ⟹  ¬𝐵 ≡ ¬(𝐴 ∧ 𝐵)`. </p>  

 
 > *<p align="right"> This equivalence also follows from the properties of implication and De Morgan's laws.</p>*  


---  
 </div>

<div style="page-break-before: always;">

## <p align="center"> 2 - De Morgan’s laws </p>  
### *Take a close look at De Morgan’s laws.*  
###### ***De Morgan's laws are two important logical equivalences that express the negation of conjunctions and disjunctions:***

> <p align="right"> In simple terms: </p>
>
> The **negation of "A or B"** is *equivalent to* **"not A and not B**."  
> The **negation of "A and B"** is *equivalent to* **"not A or not B**."  
</p>

---  

### <p align="left"> 2 a ) </p>  
## ***Negation of Disjunction***: 
<div align="center">

`¬(𝐴 ∨ 𝐵) ≡ ¬𝐴 ∧ ¬𝐵`  
</div>

> ###### Inspired by Diogenes' encounter with Alexander the Great, where he asked Alexander to step aside as he blocked the sun.  
- `A` = "You are a king."  
- `B` = "You have the power to control the sun."  
- `¬(A ∨ B)` = "It is not the case that you are a king or you have the power to control the sun."  
- `¬A ∧ ¬B` = "You are not a king and you do not have the power to control the sun."  

---  

### <p align="left"> 2 b ) </p>  
## ***Negation of Conjunction***: 
<div align="center">

`¬(𝐴 ∧ 𝐵) ≡ ¬𝐴 ∨ ¬𝐵` 
</div>

> ###### Inspired by Diogenes' statement: "I am a citizen of the world."  
- `A` = "I am a citizen of Greece."
- `B` = "I am a citizen of another country."
- `¬(A ∧ B)` = "It is not the case that I am a citizen of Greece and I am a citizen of another country."
- `¬A ∨ ¬B` = "Either I am not a citizen of Greece or I am not a citizen of another country."

---  
</div>


<div style="page-break-before: always;">

## <p align="center"> 3 - From Propositions to Truth Tables </p>  

### *You have the following propositions*:  
- `𝐴` = It’s cold.  
- `𝐵` = It’s breezy.  

Use these propositions to recreate the following sentences as propositional formulas and create a truth table for each one!

<div align="left">

- ### It’s cold and breezy.  
<div align="center">

  | A | B | A ∧ B |  
  |:-:|:-:|:------:|  
  | T | T |   T   |  
  | T | F |   F   |  
  | F | T |   F   |  
  | F | F |   F   |  
</div>

- ### It’s cold but not breezy.
<div align="center">

  | A | B | ¬A | ¬B | ¬A ∧ ¬B |  
  |:-:|:-:|:--:|:--:|:-------:|  
  | T | T |  F |  F |    F    |  
  | T | F |  F |  T |    F    |  
  | F | T |  T |  F |    F    |  
  | F | F |  T |  T |    T    |  
</div>

- ### It’s not cold and not breezy.
<div align="center">

  | A | B | ¬A | ¬B | ¬A ∧ ¬B |  
  |:-:|:-:|:--:|:--:|:-------:|  
  | T | T |  F |  F |    F    |  
  | T | F |  F |  T |    F    |  
  | F | T |  T |  F |    F    |  
  | F | F |  T |  T |    T    |  
</div>
</div>

<div style="page-break-before: always;">

- ### It’s either cold or breezy (or both).
<div align="center">

  | A | B | A ∨ B |  
  |:-:|:-:|:------:|  
  | T | T |   T   |  
  | T | F |   T   |  
  | F | T |   T   |  
  | F | F |   F   |  
</div>

- ### It’s cold or breezy, but it’s not breezy when it’s cold.
<div align="center">

  | A | B | A → B | ¬(A → B) | (A ∨ B) ∧ ¬(A → B) |  
  |:-:|:-:|:-----:|:--------:|:-------------------:|  
  | T | T |   T   |     F    |          F          |  
  | T | F |   F   |     T    |          T          |  
  | F | T |   T   |     F    |          F          |  
  | F | F |   T   |     F    |          F          |  
</div>

- ### When it’s breezy, it’s cold.
<div align="center">

  | A	| B |	¬B	| ¬B ∨ A |  
  |:-:|:-:|:--:|:------:|  
  | T | T |  F |    T   |  
  | T | F |  T |    T   |  
  | F | T |  F |    F   |  
  | F | F |  T |    T   |  
</div>
</div>

---  
</div>

<div style="page-break-before: always;">

## <p align="center"> 4. Translate Complex Sentences </p>  


- ###### *Im Donauparkstadion trinke ich gerne einen Radler oder esse eine Bosna - aber nur wenn sie vegane Würstchen haben! Manchmal konsumiere ich auch beides.**  
### Aussagenvariablen:   
  >  - `R` = Ich trinke einen Radler im Donauparkstadion.   
  >  - `B` = Ich esse eine Bosna im Donauparkstadion.   
  >  - `V` = Die Bosna hat vegane Würstchen.   
### Logische Formel: `(R ∨ B) ↔ V`   

### LÖSUNG: 

---  

- ###### *Mittwochs gehen wir zur Schule und lernen DSAI oder C#, aber nur, wenn es kein Feiertag ist. Wenn es aber Feiertag ist, sind wir unglücklich.*
### Aussagenvariablen:   
  >  - `M` = Es ist Mittwoch.   
  >  - `S` = Wir gehen zur Schule.   
  >  - `D` = Wir lernen DSAI.   
  >  - `C` = Wir lernen C#.   
  >  - `F` = Es ist Feiertag.   
  >  - `U` = Wir sind unglücklich.   
### Logische Formel: `((M → (S ∧ (D ∨ C))) ∧ (¬F → (S ∧ (D ∨ C)))) ∧ (F → U)`

## LÖSUNG: `((M ∧ ¬F)  → (S ∧ (D ∨ C)) ∧ (F → U)`

--- 
</div>


<!-- ============================================================================================================ -->
<!--                         made by               Jan Ritt       -       https://github.com/IxI-Enki             -->
<!-- ============================================================================================================ -->

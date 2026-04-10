# MARVIN'S LEFT-RIGHT RULE OF DIFFERENTIATION
**Official Publication:** April 2026  
**Author:** Marvin Musaasizi - S6 PEM/ICT Candidate at Sam Iga Memorial College

---

## 0. THE FORMAL STATEMENT
**Marvin’s Rule of Trigonometric Differentiation** states: 
> "The derivative of any trigonometric function is determined by its mechanical position within the Pythagorean Identities. Functions on the **Left** of the identity ($+1$) differentiate into the **square** of the opposite side; functions on the **Right** differentiate into the **product** of the two bases. The final parity (sign) is determined by the prefix 'Co' in the original base."

---

## 1. Introduction
Marvin's Rule is a unified, logical framework designed to simplify and speed up the process of differentiating trigonometric functions, especially those with powers. Instead of rote memorization, this rule relies on the mathematical relationships found in the Pythagorean identities (the "Mother Formulas") and a systematic 3-step process. 

---

## 2. The "Mother Formulas"
The core of the rule is built upon the two primary Pythagorean identities. Notice the "Left Side" and "Right Side" of the equation:
1. **$\tan^2 x + 1 = \sec^2 x$** *(Left Base: $\tan$, Right Base: $\sec$)*
2. **$\cot^2 x + 1 = \csc^2 x$** *(Left Base: $\cot$, Right Base: $\csc$)*

*(Note: The base pair of sine and cosine naturally differentiate into each other: $\sin x \leftrightarrow \cos x$).*

---

## 3. The 3-Step General Rule
When differentiating any trigonometric function in the form $f(x)^n$, apply these steps:

### Step 1: The Power Drop (The Outside)
Bring the power down as a multiplier and subtract 1 from the original power.
* *Example: $\tan^4 x \rightarrow 4\tan^3 x$*

### Step 2: The Mother Formula (The Inside)
Multiply by the derivative of the base:
* **Left Side ($\tan, \cot$):** Derivative is the term on the *right* side, squared. 
* **Right Side ($\sec, \csc$):** Derivative is the *left base* multiplied by the *right base*. 

### Step 3: The Universal "Co" Sign
If the **original base function** starts with **"Co"** (Cosine, Cotangent, Cosecant), the answer must be **negative (-)**.

---

## 4. Worked Examples

### Example 1: Differentiating $\tan^4 x$
* **Power Drop:** $4\tan^3 x$
* **Mother Formula:** $\tan$ is Left $\rightarrow$ multiply by Right Squared ($\sec^2 x$).
* **Sign:** Positive.
* **Final Answer:** $4\tan^3 x \sec^2 x$

### Example 2: Differentiating $\csc^4 x$
* **Power Drop:** $4\csc^3 x$
* **Mother Formula:** $\csc$ is Right $\rightarrow$ multiply by Product ($\cot x \csc x$).
* **Sign:** Starts with **Co**secant $\rightarrow$ Negative.
* **Final Answer:** $-4\csc^4 x \cot x$

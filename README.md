### **Basic Calculus Printable Reviewer & Cheat Sheet**  
This document serves as both a **reviewer** and a **cheat sheet** for fundamental concepts in Basic Calculus, covering **limits, continuity, and differentiation**.  

---

## **PART 1: LIMITS**  

### **1. Limit of a Function**  
- The **limit of a function** describes the behavior of the function **as x approaches a certain value**.  
- If the function approaches a specific value $\( L \)$ as $\( x \)$ gets closer to $\( a \)$, we write:  
  $\(\lim\limits_{x \to a} f(x) \ = L
  \)$  
- **Illustrating the Limit**:  
  - **Table of Values:** Check the function's output for values approaching $\( a \)$.  
  - **Graph:** Observe the trend of $\( f(x) \)$ as $\( x \)$ nears $\( a \)$.  

---

### **2. Types of Limits**  
- **Two-sided limit**: $\(\lim\limits_{x \to a} f(x) \)$ exists if both left-hand and right-hand limits are equal.  
- **Left-hand limit**: $\( \lim\limits_{x \to a^-} f(x) \)$ (approaching from the left).  
- **Right-hand limit**: $\( \lim\limits_{x \to a^+} f(x) \)$ (approaching from the right).  

---

### **3. Limit Laws**  
- **Sum Law**: $\( \lim\limits_{x \to a} [f(x) + g(x)] = \lim\limits_{x \to a} f(x) + \lim\limits_{x \to a} g(x) \)$.  
- **Product Law**: $\( \lim\limits_{x \to a} [f(x) g(x)] = \lim\limits_{x \to a} f(x) \cdot \lim\limits_{x \to a} g(x) \)$.  
- **Quotient Law**: $\( \lim\limits_{x \to a} \frac{f(x)}{g(x)} = \frac{\lim\limits_{x \to a} f(x)}{\lim\limits_{x \to a} g(x)} \)$, provided $\( g(a) \neq 0 \)$.  
- **Power Law**: $\( \lim\limits_{x \to a} [f(x)]^n = \left( \lim\limits_{x \to a} f(x) \right)^n \)$.  

---

### **4. Evaluating Limits**  
- **Direct Substitution**: If no indeterminate form appears, substitute $\( x = a \)$.  
- **Factoring**: If substitution leads to $\( \frac{0}{0} \)$, factor and simplify.  
- **Rationalization**: Multiply by the conjugate if radicals are involved.  
- **L'Hôpital's Rule**: If the limit is $\( \frac{0}{0} \)$ or $\( \frac{\infty}{\infty} \)$, differentiate numerator and denominator.  

---

### **5. Special Limits**  
- **Limits of Exponential, Logarithmic, and Trigonometric Functions**:  
  $\[
  \lim_{x \to 0} \frac{\sin x}{x} = 1, \quad \lim_{x \to 0} (1 + x)^{1/x} = e
  \]$
- **Limits Involving $\(\frac{0}{0}\)$ Forms**: Use algebraic techniques or L’Hôpital’s Rule.  

---

## **PART 2: CONTINUITY**  

### **6. Continuity of a Function at a Point**  
A function $\( f(x) \)$ is **continuous at $\( x = a \)$** if:  
1. $\( f(a) \)$ exists.  
2. $\( \lim\limits_{x \to a} f(x) \)$ exists.  
3. $\( \lim\limits_{x \to a} f(x) = f(a) \)$.  

---

### **7. Types of Discontinuity**  
- **Removable (Hole)**: $\( \lim\limits_{x \to a} f(x) \)$ exists, but $\( f(a) \)$ is undefined.  
- **Jump Discontinuity**: Left-hand and right-hand limits exist but are not equal.  
- **Infinite (Asymptotic)**: The function approaches $\( \pm\infty \)$ as $\( x \)$ nears $\( a \)$.  

---

### **8. Intermediate Value Theorem**  
If $\( f(x) \)$ is continuous on $\( [a, b] \)$, then for any value $\( k \)$ between $\( f(a) \)$ and $\( f(b) \)$, there exists a $\( c \)$ such that $\( f(c) = k \)$.  

---

## **PART 3: DERIVATIVES**  

### **9. Definition of a Derivative**  
The derivative of $\( f(x) \)$ at $\( x = a \)$ is:  
$\[
f'(a) = \lim_{h \to 0} \frac{f(a+h) - f(a)}{h}
\]$  
- It represents the **slope of the tangent line** to the curve at $\( x = a \)$.  

---

### **10. Differentiation Rules**  
- **Power Rule**: $\( \frac{d}{dx} x^n = n x^{n-1} \)$.  
- **Sum/Difference Rule**: $\( (f \pm g)' = f' \pm g' \)$.  
- **Product Rule**: $\( (fg)' = f'g + fg' \)$.  
- **Quotient Rule**: $\( \left(\frac{f}{g}\right)' = \frac{f'g - fg'}{g^2} \)$.  
- **Chain Rule**: $\( \frac{d}{dx} f(g(x)) = f'(g(x)) g'(x) \)$.  

---

### **11. Implicit Differentiation**  
Used when $\( y \)$ is defined implicitly:  
- Differentiate both sides with respect to $\( x \)$.  
- Solve for $\( \frac{dy}{dx} \)$.  

---

### **12. Applications of Derivatives**  
- **Optimization Problems**: Find max/min values by setting $\( f'(x) = 0 \)$.  
- **Related Rates**: Differentiate equations involving multiple variables with respect to time.  

---

## **CHEAT SHEET**  

| Concept | Formula/Key Idea |
|---------|-----------------|
| **Limit Definition** | $\( \lim\limits_{x \to a} f(x) = L \)$ |
| **Limit Laws** | Sum, Product, Quotient, Power |
| **L'Hôpital’s Rule** | $\( \frac{0}{0} \)$ or $\( \frac{\infty}{\infty} \Rightarrow \)$ Differentiate numerator & denominator |
| **Continuity Conditions** | Function exists, limit exists, both are equal |
| **Types of Discontinuity** | Hole, Jump, Asymptote |
| **Derivative Definition** | $\( f'(x) = \lim\limits_{h \to 0} \frac{f(x+h) - f(x)}{h} \)$ |
| **Power Rule** | $\( \frac{d}{dx} x^n = n x^{n-1} \)$ |
| **Product Rule** | $\( (fg)' = f'g + fg' \)$ |
| **Quotient Rule** | $\( \left(\frac{f}{g}\right)' = \frac{f'g - fg'}{g^2} \)$ |
| **Chain Rule** | $\( \frac{d}{dx} f(g(x)) = f'(g(x)) g'(x) \)$ |
| **Implicit Differentiation** | Differentiate both sides with $\( dy/dx \)$ |
| **Optimization** | $\( f'(x) = 0 \)$ for critical points |
| **Related Rates** | Differentiate with respect to time |

---


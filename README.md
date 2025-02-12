### **Basic Calculus Fourth Quarter Printable Reviewer & Cheat Sheet**  
This document serves as both a **reviewer** and a **cheat sheet** for fundamental concepts in Basic Calculus.    

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
  
#### **Chain Rule**: $\( \frac{d}{dx} g(f(x)) = g'(f(x)) f'(x) \)$.  

Examples:

1.

$y = (5x^2 - 4x + 2)^3$

$y' = 3(5x^2 - 4x + 2)^2(10x - 4)$

$y' = (5x^2 - 4x + 2)^2(30x - 12)$

2.

$y = (3x^2 - 4)^\frac{1}{2}$

$y' = \frac{1}{2}(3x^2 - 4)^\frac{-1}{2}(6x)$

$y' = (3x^2 - 4)^\frac{-1}{2}(3x)$

$y' = \frac{3x}{(3x^2 - 4)^\frac{1}{2}}$

3.

$y = \sqrt{5x - 2} = (5x - 2)^\frac{1}{2}$

$y' = \frac{1}{2}(5x - 2)^\frac{-1}{2}(5)$

$y' = \frac{5}{2}(5x - 2)^\frac{-1}{2}$

$y' = \frac{5}{2(5x - 2)^\frac{1}{2}}$

4.

$y = (3x - 2)(5x + 4)^4$

$u = 3x - 2$

$u' = 3$

$v = 5x + 4$

$v' = 4$

$y' = (3x - 2)(20(5x + 4)^3) + (5x + 4)^4(3)$

$y' = (60x - 40)(5x + 4)^3 + (5x + 4)^4(3)$

$y' = (5x + 4)^3[(60x - 40) + (5x + 4)(3)]$

$y' = (5x + 4)^3(60x - 40 + 15x + 12)$

$y' = (5x + 4)^3(75x - 28)$

5.

$y = ( \frac{x - 2}{2x + 1})^9$

$u = x - 2$

$u' = 1$

$v = 2x + 1$

$v' = 2$

$\frac{vu' - uv'}{v^2} = \frac{(2x + 1)(1) - (x - 2)(2)}{(2x + 1)^2} = \frac{2x + 1 - 2x + 4}{(2x + 1)^2} = \frac{5}{(2x + 1)^2}$

$y' = 9( \frac{x - 2}{2x + 1})^8(\frac{5}{(2x + 1)^2})$

$y' = \frac({x - 2})^8{(2x + 1)^8}(\frac{45}{(2x + 1)^2)}$

$y' = \frac{45(x - 2)^8}{(2x + 1)^{10}}$

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


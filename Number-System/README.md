# Number Systems: GitHub Repository Template

This is the complete study material extracted and reconstructed from educational content about number systems and number classification.

## Contents

This repository provides comprehensive coverage of:

1. **Complete Guide** (`number_systems_guide.md`) - In-depth explanations with 12 structured sections
2. **Visual Reference** (`number_systems_visual_companion.md`) - Diagrams, flowcharts, and practice problems
3. **Quick Cheat Sheet** (this file) - Fast reference for exams and interviews

---

## Quick Start: The Number System Hierarchy

```
┌─────────────────────────────────────┐
│  Complex Numbers (a + bi)           │
│  ├─ Real Numbers ───────────────┐   │
│  │  ├─ Rational (p/q)          │   │
│  │  │  ├─ Integers             │   │
│  │  │  │  ├─ Whole (0,1,2...) │   │
│  │  │  │  └─ Negative         │   │
│  │  │  └─ Fractions           │   │
│  │  └─ Irrational (π, √2)     │   │
│  └─ Imaginary (bi)──────────────┘   │
└─────────────────────────────────────┘
```

---

## Essential Facts

### Prime Numbers
- **Definition**: Natural numbers with exactly 2 divisors (1 and itself)
- **Examples**: 2, 3, 5, 7, 11, 13, 17, 19, 23
- **Why 1 is NOT prime**: Has only 1 divisor, needs 2
- **Why 2 is special**: Only even prime
- **Fundamental Theorem**: Every integer > 1 is uniquely factorizable into primes

### Composite Numbers
- **Definition**: Natural numbers with more than 2 divisors
- **Examples**: 4, 6, 8, 9, 10, 12
- **Prime factorization**: 12 = 2² × 3, 30 = 2 × 3 × 5

### Rational Numbers
- **Form**: p/q where p, q are integers, q ≠ 0
- **Decimal**: Terminates (0.25) or repeats (0.333...)
- **Every integer is rational**: 5 = 5/1

### Irrational Numbers
- **Definition**: Cannot be expressed as p/q
- **Decimal**: Never terminates, never repeats
- **Examples**: π ≈ 3.14159..., e ≈ 2.71828..., √2 ≈ 1.41421...
- **Proof technique**: Proof by contradiction (as shown for √2)

### Real Numbers
- **Definition**: Union of rational and irrational numbers
- **Representation**: Every point on the number line
- **Properties**: Ordered, complete (no gaps)

### Complex Numbers
- **Form**: a + bi where a, b ∈ ℝ, i = √(-1)
- **i² = -1** (fundamental property)
- **Examples**: 3 + 4i, 2i, 5
- **Applications**: Electrical engineering, quantum mechanics, signal processing

---

## Common Misconceptions

| Wrong | Correct |
|-------|---------|
| 1 is prime | 1 is neither prime nor composite |
| 0 is positive | 0 is neither positive nor negative |
| All decimals are irrational | Only non-terminating, non-repeating decimals are irrational |
| Can't take square root of negative | Can use imaginary unit i; √(-4) = 2i |
| √2 + √2 = √4 = 2 | √2 + √2 = 2√2 ≈ 2.83 (irrational) |

---

## Interview Q&A

**Q: Is zero a natural number?**
A: Depends on convention. Modern math typically: Natural = {1,2,3,...}. Some include 0. Clarify with interviewer.

**Q: Why isn't 1 prime?**
A: By definition, primes have exactly 2 divisors. 1 has only 1 divisor (itself).

**Q: Prove √2 is irrational.**
A: Assume √2 = p/q in lowest terms. Then 2q² = p². So p² is even, thus p is even (p = 2k). Then q² = 2k², so q is even. But if both are even, p/q isn't in lowest terms—contradiction! Therefore √2 is irrational.

**Q: Can the sum of two irrational numbers be rational?**
A: Yes! Example: √2 + (-√2) = 0 (rational).

**Q: What is i?**
A: The imaginary unit where i² = -1. It enables solving equations like x² + 1 = 0 (x = ±i).

**Q: How do you determine if a number is prime?**
A: Check if it has any divisors besides 1 and itself. Only need to check up to √n. Example: Is 17 prime? √17 ≈ 4.1, so check 2, 3, 4. Not divisible by any → Prime.

---

## Fast Reference: Converting Between Forms

### Fraction to Decimal
```
1/4 = 0.25 (divide)
1/3 = 0.333... (repeating)
5/8 = 0.625 (divide)
```

### Decimal to Fraction
```
0.5 = 1/2
0.333... = 1/3 (use algebra: 10x - x = 3 → 9x = 3 → x = 1/3)
0.25 = 1/4
```

### Fraction to Percentage
```
1/2 = 50%
1/4 = 25%
3/5 = 60%
```

### Percentage to Fraction
```
50% = 1/2
25% = 1/4
60% = 3/5
```

---

## Prime Numbers Reference List

### Primes up to 100
```
2, 3, 5, 7, 11, 13, 17, 19, 23, 29, 31, 37, 41, 43, 47, 
53, 59, 61, 67, 71, 73, 79, 83, 89, 97

Total: 25 primes less than 100
```

### Checking if N is Prime
```
Algorithm:
1. If n ≤ 1: Not prime
2. If n = 2: Prime (only even prime)
3. If n is even: Not prime
4. Check divisibility by odd numbers 3 to √n
5. If no divisor found: Prime

Example: Is 29 prime?
√29 ≈ 5.4, so check 3, 5
29 ÷ 3 = 9.67... (not divisible)
29 ÷ 5 = 5.8... (not divisible)
Result: 29 is PRIME
```

---

## Study Sequence

**Beginner Level**:
1. Counting and whole numbers
2. Integers (positive and negative)
3. Prime and composite numbers
4. Rational numbers and fractions

**Intermediate Level**:
5. Decimal representations
6. Irrational numbers
7. Real numbers
8. Number line and ordering

**Advanced Level**:
9. Complex numbers
10. Imaginary unit (i)
11. Operations with complex numbers
12. Advanced proofs (why √2 is irrational)

---

## Resources for Deeper Learning

### Topics to Explore
1. **Number Theory**: Divisibility, modular arithmetic, GCD/LCM
2. **Algebraic Numbers**: Roots of polynomial equations
3. **Transcendental Numbers**: π, e (not algebraic)
4. **Cardinality**: Comparing sizes of infinite sets
5. **Complex Analysis**: Functions of complex variables
6. **Cryptography**: Prime factorization applications

### Key Theorems
- **Fundamental Theorem of Arithmetic**: Unique prime factorization
- **Fundamental Theorem of Algebra**: Polynomial equations have complex roots
- **Irrationality Proofs**: √n irrational unless n is perfect square

---

## Practice Problems (with answers)

### Easy
1. Is 23 prime? **Yes** (only divisible by 1, 23)
2. Express 3/4 as decimal: **0.75**
3. Is 0.5 rational? **Yes** (0.5 = 1/2)

### Medium
4. Prime factorization of 60: **2² × 3 × 5**
5. Is √4 irrational? **No** (√4 = 2, which is rational)
6. Convert 0.666... to fraction: **2/3**

### Hard
7. Prove √3 is irrational: **Proof by contradiction (similar to √2)**
8. If a is irrational, is a + 1 irrational? **Yes** (if not, then a = (a+1) - 1 = rational)
9. Simplify i⁴: **i⁴ = (i²)² = (-1)² = 1**

---

## Cheat Sheet: Symbol Reference

| Symbol | Meaning | Example |
|--------|---------|---------|
| ∈ | Element of | 3 ∈ ℤ (3 is an integer) |
| ⊂ | Subset | ℕ ⊂ ℤ (naturals are subset of integers) |
| ∅ | Empty set | Q ∩ Q' = ∅ (no number is both rational and irrational) |
| ∪ | Union | ℝ = Q ∪ Q' (reals = rationals ∪ irrationals) |
| ∩ | Intersection | ℤ ∩ ℕ = ℕ (integers AND naturals = naturals) |
| ℕ | Natural numbers | {1, 2, 3, ...} |
| ℤ | Integers | {..., -1, 0, 1, ...} |
| ℚ | Rational | {p/q : p,q ∈ ℤ, q ≠ 0} |
| ℝ | Real | All points on number line |
| ℂ | Complex | {a + bi : a,b ∈ ℝ} |
| i | Imaginary unit | i² = -1 |

---

## How to Use This Material

### For Exams
1. Review quick reference tables first
2. Work through practice problems
3. Understand proofs (not just memorize)
4. Create your own examples

### For Interviews
1. Learn definitions precisely
2. Understand WHY not just HOW
3. Prepare to explain concepts simply
4. Have examples ready

### For Deep Learning
1. Read full guide (`number_systems_guide.md`)
2. Study visual companion diagrams
3. Work through all practice problems
4. Explore advanced topics

---

## Contributing

To improve this material:
1. Clarify any confusing sections
2. Add more examples
3. Include diagrams
4. Expand proof sections
5. Create additional practice problems

---

## License

This educational material is free to use, modify, and distribute for learning purposes.

---

## Final Tips

1. **Understand, don't memorize**: Every definition has a reason
2. **See patterns**: Prime numbers, factorization, decimal representations
3. **Use multiple representations**: Decimal, fraction, percentage, geometric
4. **Practice actively**: Work through problems, don't just read
5. **Ask why**: Why is 1 not prime? Why can't we divide by zero? Why do irrationals exist?

Master number systems, master mathematics.

# Vector Dot-Product Implementation
## Introduction

This is a *bold* statement and this is italic.
> The dot product of two vectors is a scalar value that is the sum of the products of their corresponding components.
For more details, check out [Wikipedia](https://en.wikipedia.org/wiki/Dot_product).


![Dot Product Diagram](https://imgs.search.brave.com/EIarURy_LZMveV8at82_SM2PfLhsRFWzasLyEw9ZFfg/rs:fit:500:0:0:0/g:ce/aHR0cDovL3d3dy5s/ZWFybmluZ2Fib3V0/ZWxlY3Ryb25pY3Mu/Y29tL2ltYWdlcy9E/b3QtcHJvZHVjdC1v/Zi12ZWN0b3JzLnBu/Zw)


- Vector A
- Vector B
1. Define vectors A and B.
2. Compute their dot product.
3. Display the result.
- [ ] Implement dot product function
- [x] Test with sample vectors


Explanation[^1]
> [!NOTE]
> The dot product is only defined for vectors of the same dimension.


| Version        | Time Complexity  | Notes                        |
|----------------|------------------|------------------------------|
| Naive          | O(n)             | Simple implementation        |
| Optimized      | O(n)             | Uses optimized data access   |

### *Adding code*
```python
def dot_product(A, B):
    return sum(a * b for a, b in zip(A, B))
```


###  *Mathematical Expressions*
For mathematical expressions, you can use LaTeX-style syntax wrapped in dollar signs $$ for block-level equations or single dollar signs for inline equations.


The mathematical expression for the dot product is:

$$
\mathbf{a} \cdot \mathbf{b} = \sum_{i=1}^{n} a_i b_i
$$



[^1]:This is a footnote

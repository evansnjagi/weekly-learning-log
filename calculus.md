# Calculus
>Calculus for machine learning and data science.
## 26-07-2026

### What I covered
Derive exactly how neural network learns; mathematically from scratch. 

Defferentiating sigmoid activation function $\sigma (x) = \frac{1}{1 + e^{-x}}$ using both chain and quotient rule. The answer is the same. 

$$\frac{d}{dx} \sigma (x) = \frac{e^x}{(1 + e^{-x})^2} = \sigma(x)\left(1 - \sigma (x) \right)$$

Forward pass is literally solving the functions through direct substitutions. Backpropagration, on the other hand, is differentiating the functions as $\frac{dL}{dx} = \frac{dL}{da} \cdot \frac{da}{dx}$.The last step is updating the weight using $w_{new} = w_{current} - \alpha \cdot \frac{dL}{dx}$, where $\alpha$ is the learning rate.
### Key insight
- Sigmoid activation fuction *shrinks* the gradient leading to a vanishing gradient problem.
- ReLU is an activation function that retains the original nature of the positive gradient. For negative values, ReLU sets them to zero; gradient dies completely. To solve this problem, a small number is set say $\epsilon$.

### Struggle of the week
Computing backpropagation with precision and correctness.

### What's pending
Two milestione projects:
1. Differentiation engine
2. Backpropagation using Python

### Next weeks intentions
Complete the assignment.
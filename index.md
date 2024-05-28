 
<script type="text/javascript" async
  src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

<script type="text/x-mathjax-config">
MathJax.Hub.Config({
  tex2jax: {
    inlineMath: [['$', '$'], ['\\(', '\\)']],
    processEscapes: true
  }
});
</script>

> *[Letters to Abigail](https://www.masshist.org/digitaladams/archive/doc?id=L17800512jasecond)*

![](https://upload.wikimedia.org/wikipedia/commons/4/49/%22The_School_of_Athens%22_by_Raffaello_Sanzio_da_Urbino.jpg)

### Activation Function/$Q$: 1st, 3rd, 5th, [♭♭7th](https://en.wikipedia.org/wiki/Chord_notation#Chord_quality), 9th  
- Hunter-gatherer/`War`: spiritual teachings  (I)
- Peasant/`Economics`: [humanism](https://www.uuftc.org) (B)
        
### Biases/$U()$: 11th, 13th
- Farmer/`Calculus`: judeo, christian (G)
- Manufacturer/`Philosophy`: world religions (Y)
       
### Weights/$\frac{dU()}{dQ}$: ♯9,♭9,♯11,♭13 
- Electricity/`Musick`: prophetic utterances ([O](https://www.youtube.com/watch?v=1aM1KYvl4Dw))
- Railway/`Leisure`: individual experience ([R](https://www.youtube.com/watch?v=fu-3WN9TJNI))     


```python
import numpy as np
import matplotlib.pyplot as plt

# Define the total utility function U(Q)
def total_utility(Q):
    return 100 * np.log(Q + 1)  # Logarithmic utility function for illustration

# Define the marginal utility function MU(Q)
def marginal_utility(Q):
    return 100 / (Q + 1)  # Derivative of the total utility function

# Generate data
Q = np.linspace(1, 100, 500)  # Quantity range from 1 to 100
U = total_utility(Q)
MU = marginal_utility(Q)

# Plotting
plt.figure(figsize=(14, 7))

# Plot Total Utility
plt.subplot(1, 2, 1)
plt.plot(Q, U, label=r'Total Utility $U(Q) = 100 \log(Q + 1)$', color='blue')
plt.title('Total Utility')
plt.xlabel('Quantity (Q)')
plt.ylabel('Total Utility (U)')
plt.legend()
plt.grid(True)

# Plot Marginal Utility
plt.subplot(1, 2, 2)
plt.plot(Q, MU, label=r'Marginal Utility $MU(Q) = \frac{dU(Q)}{dQ} = \frac{100}{Q + 1}$', color='red')
plt.title('Marginal Utility')
plt.xlabel('Quantity (Q)')
plt.ylabel('Marginal Utility (MU)')
plt.legend()
plt.grid(True)

# Adding some calculus notation and Greek symbols
plt.figtext(0.5, 0.02, r"$MU(Q) = \frac{dU(Q)}{dQ} = \lim_{\Delta Q \to 0} \frac{U(Q + \Delta Q) - U(Q)}{\Delta Q}$", ha="center", fontsize=12)

plt.tight_layout()
plt.show()
```

Running this code will generate a visual demonstration of diminishing marginal utility with appropriate calculus notation and Greek symbols.

Here is the generated image:

![Diminishing Marginal Utility](https://abikesa.github.io/johnadams/diminishing_marginalutility.png)

> One needs challenges, a worthy adversary, the embrace of more remote overtones of the harmonic series - ***Q**ualities*

- Brain & Learning
- Computer `Simulations`
- [Geoffrey Hinton](https://www.youtube.com)
- [Terry Sejnowski](https://en.wikipedia.org/wiki/Terry_Sejnowski)
- Ilya Sutskever & "Compute"
- Back Propagation & Compressing information into Weights
- Also known as Encoding
- [David J. C. MacKay](http://www.inference.org.uk/mackay/)

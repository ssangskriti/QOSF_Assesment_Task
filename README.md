### **`Implement a circuit that returns |01> and |10> with equal probability (50% for each).`**

_Requirements_:

1. The circuit should consist only of CNOTs, RXs and RYs
2. Start from all parameters in parametric gates being equal to 0 or randomly chosen.
3. You should find the right set of parameters using gradient descent (you can use more advanced optimization methods if you like).
4. Simulations must be done with sampling (i.e. a limited number of measurements per iteration) and noise.

Compare the results for different numbers of measurements: 1, 10, 100, 1000. 

_Bonus question:_
**How to make sure you produce state |01> + |10> and not |01> - |10> ?**


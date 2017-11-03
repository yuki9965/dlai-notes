# logistic 公式推导

$$
z^{(i)} = w^{T} x^{(i)} + b
$$

$$
a^{(i)} = \sigma(z^{(i)})
$$

$$
J = -\sum_i (y^{(i)} \log a^{(i)} + (1-y^{(i)}) \log(1-a^{(i)}))
$$

$$
\frac{dJ}{da^{(i)}} = \frac{1- y^{(i)}}{1- a^{(i)}} - \frac{y^{(i)}}{a^{(i)}}
$$

$$
\frac{da^{(i)}}{dz^{(i)}} = a^{(i)}(1-a^{(i)})
$$

$$
\frac{dz^{(i)}}{dw} = x^{(i)}
$$

$$
\frac{dJ}{dz^{(i)}} = a^{(i)} - y^{(i)}
$$

$$
\frac{dJ}{dw} = \sum_i (a^{(i)} - y^{(i)})x^{(i)}
$$

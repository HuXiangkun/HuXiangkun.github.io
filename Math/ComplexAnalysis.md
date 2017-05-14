<font size = 4>
# Complex Analysis
--------
## 1. Polar Representation of Complex Numbers
$ z = x+iy \in \mathbb{C} , r = |z|$

$ x = r\cos\theta , y = r\sin \theta$

so: $ z = x + iy = r\cos\theta+ir\sin\theta=r(\cos\theta+i\sin\theta) $

### The Argument of a Complex Number
#### The principal argument of $ z $, called Arg $ z$ is the value of $ \theta$ for which $ -\pi \lt\theta\le \pi$

### Exponential Notation

$$ e^{i\theta}=\cos\theta+i\sin\theta$$

So $ z = r(\cos\theta+i\sin\theta)$ becomes $ z=re^{i\theta}$, the *polar form* of $z$.

### Propreties of the Exponential Notation
- $ |e^{i\theta}|=1$
- $ \overline{e^{i\theta}}=e^{-i\theta}$
- $ \frac{1}{e^{i\theta}}=e^{-i\theta}$
- $ e^{i(\theta+\varphi)}=e^{i\theta}\cdot e^{i\varphi}$

### Conclusions for the Argument Function
- $ arg(\overline{z})=-arg(z)$
- $ arg(\frac{1}{z})=-arg(z)$
- $ arg(z_{1}z_{2})=arg(z_1)+arg(z_2)$

### Multiplication in Polar Form
$$ z_1 z_2 = r_1 e^{i\theta_1} r_2 e^{i\theta_2}=(r_1 r_2) e^{i(\theta_1 \theta_2)}$$

### De Moivre's Formula
$ (e^{i\theta})^n=e^{in\theta}$, So $ (\cos\theta+i\sin\theta)^n=\cos(n\theta)+i\sin(n\theta)$ 

## 2. Roots of Complex Numbers
Let $ w$ be a complex number. An *n*th root of $ w$ is a complex number $ z$ such that $ z^n = w$.

$$ w=\rho e^{i\varphi}$$

$$ z=r e^{i\theta}$$

So $$ r = \rho^{\frac{1}{n}}, n\theta=\varphi+2k\pi \Longrightarrow \theta=\frac{\varphi}{n}+\frac{2k\pi}{n},k=0,1,...,n-1$$
So we write $$ w^{\frac{1}{n}}=\rho^{\frac{1}{n}}e^{i(\frac{\varphi}{n}+\frac{2k\pi}{n})},k=0,1,...,n-1$$

We call *n*th roots of 1 the *n*th roots of *unity*.
$$1=e^{i\cdot 0} \Longrightarrow 1^{\frac{1}{n}}=e^{i\frac{2k\pi}{n}},k=0,1,...,n-1$$

</font>
### Maxwell equations with potentials

![](https://latex.codecogs.com/gif.latex?\vec{B}&space;=&space;\vec{\nabla}&space;\times&space;\vec{A})

![](https://latex.codecogs.com/gif.latex?\vec{E}&space;=&space;-\vec{\nabla}V&space;-&space;\frac{\partial&space;\vec{A}}{\partial&space;t})

![](https://latex.codecogs.com/gif.latex?\nabla^2V&space;&plus;&space;\frac{\partial}{\partial&space;t}(\vec{\nabla}&space;\cdot&space;\vec{A})&space;=&space;-\frac{1}{\epsilon_0}\rho)

![](https://latex.codecogs.com/gif.latex?(\nabla^2\vec{A}&space;-&space;\mu_0&space;\epsilon_0&space;\frac{\partial^2&space;\vec{A}}{\partial&space;t^2})&space;-&space;\vec{\nabla}&space;(\vec{\nabla}&space;\cdot&space;\vec{A}&space;&plus;&space;\mu_0&space;\epsilon_0&space;\frac{\partial&space;V}{\partial&space;t})&space;=&space;-\mu_0&space;\vec{J})

### Inhomogenous wave equations
Lorentz gauge:
$$
\vec{\nabla} \cdot \vec{A} = -\mu_0 \epsilon_0 \frac{\partial V}{\partial t}
$$
Inomogenous wave equations:
$$
\Box^2 V = -\frac{1}{\epsilon_0} \rho
$$
$$
\Box^2 \vec{A} = -\mu_0 \vec{J}
$$
D'Alambertian
$$
\Box^2 = \nabla^2 - \mu_0 \epsilon_0 \frac{\partial^2}{\partial t^2}
$$

### Retarded potentials
$$
V(\vec{r}, t) = \frac{1}{4\pi\epsilon_0} \int \frac{\rho(\vec{r'}, t_r)}{r} d\tau'
$$
$$
\vec{A}(\vec{r}, t) = \frac{\mu_0}{4\pi} \int \frac{\vec{J}(\vec{r'},t_r)}{r} d\tau'
$$
with $t_r = t - \frac{r}{c}$

### Jefimenko's Equations
$$
\vec{E}(\vec{r}, t) = \frac{1}{4\pi\epsilon_0}\int[\frac{\rho(\vec{r'}, t_r)}{r^2}\vec{\hat{r}} + \frac{\dot{\rho}(\vec{r'}, t_r)}{cr}\vec{\hat{r}} - \frac{\vec{\dot{J}}(\vec{r'}, t_r)}{c^2r}]d\tau'
$$
$$
\vec{B}(\vec{r}, t) = \frac{\mu_0}{4\pi} \int [\frac{\vec{J}(\vec{r'}, t_r)}{r^2} + \frac{\vec{\dot{J}}(\vec{r', t_r})}{cr}] \times \vec{\hat{r}} d\tau'
$$

In the thesis, I provide a description of the particle production mechanism via the S-matrix formalism used in quantum field theory in Minkowski spacetime.
In this framework, the mechanism is interpreted as a vacuum decay induced by an external classical source, namely the gravitational inhomogeneeities $h_{\mu \nu}$. 
By expanding perturbatively the action in the linearized gravity approach and in background field method, where the first requires expanding at linear order in the gravitational perturbation whereas the latter at second order in the field fluctuations, the vacuum decay process is described by an interaction term as $L_{int} \sim h_{\mu \nu} T^{\mu \nu}$.

One of the core results of the formalism is to state the equivalence between the transition matrix element of the process, namely $\mathcal{M}(0 \to k \omega)$, and the Bogoliubov coefficient $\beta$

$$ \mathcal{M}(0 \to k \omega) = \beta_{\vec{k} \vec{\omega}}$$

with $k$ and $\omega$ the four-momenta of the out-going particles.

The symmetries in the field theory naturally provide selection rules, highlighting the independent Bogoliubov coefficients. Therefore, the whole picture establishes a direct and elegant formulation to compute exclusively the indipendent Bogoliubov coefficients: this generalizes to massive arbitrary spin filed the previous treatment in literature, focused primarly on conformal field theory via the effective action method.

Furthermore, the mean number of particles produced by the gravitational perturbations is derived by computing the total amplitude of the process, namely $P(0 \to k\omega$. The resulting expression is

$$ \langle N \rangle = \frac{1}{4\pi} \int \frac{d^4 q}{(2\pi)^4} \int_{-1}^1 d\cos\theta \ h_{\mu \nu}(q_0,\vec{q}) F^{\mu \nu \rho \sigma}(q_0,q,\theta,M) h^*_{\rho \sigma}(q_0,\vec{q}) $$

where

$$ F^{\mu \nu \rho \sigma}(M,q_0,q,\theta) \equiv \frac{\tilde{k}^2}{\sqrt{M^2 + \tilde{k}^2} \sqrt{M^2 + q^2  + \tilde{k}^2 -2q\tilde{k}\cos\theta}} \frac{M^{\mu \nu} M^{\rho \sigma *}}{|f'(\tilde{k})|} $$
$$ f(k) = \sqrt{M^2 + k^2} + \sqrt{M^2 + k^2 + q^2 - 2kq\cos\theta} - q_0 $$
$$ \tilde{k} = \frac{q \qty(q_0^2 - q^2) \cos\theta + q_0 \sqrt{2 M^2 \qty(q^2 - 2 q_0^2) + \qty(q_0^2 - q^2)^2 + 2 M^2 q^2 \cos(2 \theta)}}{2 \qty(q_0^2 - q^2 \cos^2\theta)}$$.

In conclusion, the universal formula of the number of produced particle is specialized for stochastic gravitational backgrounds, where it becomes

$$ \langle N \rangle = \frac{1}{8\pi^2} \int_{2M}^\infty dq_0 \int_0^{\sqrt{q_0^2 - 4M^2}} d\log q \ \Delta_S(\vec{q},q_0,-q_0) f_S(q_0,q,M)$$

with $S$ the Fourier transform of a generic stochastic source and $\Delta_S(\vec{q},q_0,-q_0)$ the double Fourier transform of its dimensionless power spectrum, and $f_S$ the kernel function.

The kernel functions for the gravitational source in the Newtonian gauge are computed as:

$$f_\Theta(q_0,q,M) &= \int_{-1}^1 d \cos\theta \, \delta_{\mu \nu} F^{\mu \nu\rho \sigma}(q_0,q,\theta,M) \delta_{\rho \sigma}$$
  
$$f_\Sigma(q_0,q,M) &= \int_{-1}^1 d \cos\theta \, \eta_{\mu \nu} F^{\mu \nu\rho \sigma}(q_0,q,\theta,M) \eta_{\rho \sigma}$$

$$ f_W(q_0,q,M) = \int_{-1}^1 d \cos\theta \, 4q_i q_j \hat{\Lambda}_{lm}(\hat{q}) F^{ijlm}(q_0,q,\theta,M).$$

$$f_h(q_0,q,M) = \int_{-1}^1 d\cos\theta \ \hat{\Lambda}_{ijlm}(\hat{q}) F^{ijlm}(q_0,q,\theta,M)$$

with $\hat{\Lambda}_{ijlm}(\hat{q})$ the transverse and traceless projector, constructed with the transverse 2$D$ projector $\hat{\Lambda}_{lm}(\hat{q})$.

In this folder, the computation of the indipendent Bogoliubov coefficients and kernel functions is done for several spin field both massless and massive.

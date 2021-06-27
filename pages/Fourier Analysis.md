- #book #math #analysis #calculus

- Chapter 1: Introduction to Fourier Series
  heading:: true
	- 1.1 Periodic Functions, Fourier Series on $(-\pi, \pi)$
	  collapsed:: true
		- **Definition** : A function $f$ is periodic with a period $p$ if $f(x) = f(x+p), \forall x$
		- **Theorem** : If a function $f$ has a period $p$ , then any integer multiple of $p$ is also a period of $f$
		- **Corollary** : The graph of a periodic function, shifted by the period $p$ will be identical to the original graph.
		- **Definition** : The trigonometric system , period $2\pi$ , is the set of functions:
		  $$1, \sin x, \cos x, \sin 2x, \cos 2x, ..., \sin nx, \cos nx, ...$$
		- **Theorem** : Orthogonality of the Trigonometric System
		  collapsed:: true
			-
			  $$\int^{\pi}_{-\pi} \cos nx \; dx = 0$$ $$\int^{\pi}_{-\pi} \sin nx \; dx = 0$$
			-
			  $$\int^{\pi}_{-\pi} \sin mx \cos nx \; dx = 0$$
			-
			  $$\int^{\pi}_{-\pi} \cos mx \cos nx = \begin{cases} 0, & \text{if }n \neq m \\ \pi, & \text{if }n = m \end{cases}$$
			-
			  $$\int^{\pi}_{-\pi} \sin mx \sin nx = \begin{cases} 0, & \text{if }n \neq m \\ \pi, & \text{if }n = m \end{cases}$$
		- **Definition** : Fourier Series & Coefficients (period $2\pi$ )
		  collapsed:: true
			- Fourier Series:
			  $$f(x) = \frac{1}{2}A_0 + \sum^\infty_{n=1} [A_n \cos nx + B_n \sin nx]$$
			-
			  $$A_n = \frac{1}{\pi} \int^{\pi}_{-\pi} f(x) \cos nx \; dx$$
			-
			  $$B_n = \frac{1}{\pi} \int^{\pi}_{-\pi} f(x) \sin nx \; dx$$
	- 1.2 Arbitrary Periods, Periodic Extensions
		- **Theorem** : The trigonometric system , period $2a$ , is the set of functions:
		  collapsed:: true
		  $$1, \sin \frac{\pi x}{a}, \cos \frac{\pi x}{a}, \sin \frac{2\pi x}{a}, \cos \frac{2\pi x}{a}, ..., \sin \frac{n\pi x}{a}, \cos \frac{n\pi x}{a}, ...$$ These have the following orthogonality relations:
			-
			  $$\int^{\pi}_{-\pi} \cos \frac{n\pi x}{a} \; dx = 0$$
			-
			  $$\int^{\pi}_{-\pi} \sin \frac{n\pi x}{a} \; dx = 0$$
			-
			  $$\int^{\pi}_{-\pi} \sin \frac{m\pi x}{a} \cos \frac{n\pi x}{a} \; dx = 0$$
			-
			  $$\int^{\pi}_{-\pi} \cos \frac{m\pi x}{a} \cos \frac{n\pi x}{a} = \begin{cases} 0, & \text{if }n \neq m \\ a, & \text{if }n = m \end{cases}$$
			-
			  $$\int^{\pi}_{-\pi} \sin \frac{m\pi x}{a} \sin \frac{n\pi x}{a} = \begin{cases} 0, & \text{if }n \neq m \\ a, & \text{if }n = m \end{cases}$$
		- **Definition** : Fourier Series and Coefficients for $f$ (period $2a$ )
		  id:: 60c38811-917b-40ed-b07e-c79c33055133
		  collapsed:: true
			-
			  $$f(x) = \frac{1}{2}A_0 + \sum^\infty_{n=1} \left[A_n \cos\frac{n\pi x}{a} + B_n \sin\frac{n\pi x}{a}\right]$$
			-
			  $$A_n = \frac{1}{a} \int^a_{-a} f(x)\cos\frac{n\pi x}{a} \; dx$$
			-
			  $$B_n = \frac{1}{a} \int^a_{-a} f(x)\sin\frac{n\pi x}{a} \; dx$$
		- **Definition**: Let $f$ be a function defined on some interval of length $2a$. The _periodic extension_ of $f$ is the function $f_P$ which satisfies for $p=2a$
		  $$f_P(x+kp) = f(x)$$
			- _Note_: The [Fourier series](((60c38811-917b-40ed-b07e-c79c33055133))) of $f$ and $f_P$ are identical
	- 1.3 Cosine and Sine Series
		- **Definition**: The _cosine series_ of an even function is defined as:
			-
			  $$f = \frac{1}{2}A_0 + \sum^{\infty}_{n=1} A_n \cos \frac{n\pi x}{a}$$
			-
			  $$A_n = \frac{2}{a}\int^a_0 f(x) \cos \frac{n\pi x}{a} \; dx$$
		- **Definition**: The _sine series_ of an odd function is defined as:
			-
			  $$f = \sum^{\infty}_{n=1} B_n \sin \frac{n\pi x}{a}$$
			-
			  $$B_n = \frac{2}{a}\int^a_0 f(x) \sin \frac{n\pi x}{a} \; dx$$
	- 1.4 Convergence of Fourier Series
	- 1.5 Uniform Convergence
	- 1.6 Abel's Test
	- 1.7 Complex Form of Fourier Series
- Chapter 2: Convergence of Fourier Series
  heading:: true
- Chapter 3: Applications of Fourier Series
  heading:: true
- Chapter 4: Some Harmonic Function Theory
  heading:: true
- Chapter 5: Multiple Fourier Series
  heading:: true
- Chapter 6: Basic Theory of the Fourier Transform
  heading:: true
- Chapter 7: Applications of Fourier Transforms
  heading:: true
- Chapter 8: Legendre Polynomials and Spherical Harmonics
  heading:: true
- Chapter 9: Some Other Transforms
  heading:: true
- Chapter 10: A Brief Introduction to Bessel Functions
  heading:: true
- Appendix A: Divergence of Fourier Series
  heading:: true
- Appendix B: Brief Tables of Fourier Series and Fourier Transforms
  heading:: true
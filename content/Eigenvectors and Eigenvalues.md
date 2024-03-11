## Definition

An eigenvector of $A\in n\times n$ matrix is a vector $\vec{v}\in\mathbb{R}^n$ such that $A\vec{v}=\lambda\vec{v},\:\lambda\in\mathbb{R}^n$. Where $\lambda$ is the eigenvalues.

An eigenvector cannot be the [[Zero Vector]].

The eigenvectors corresponding to an eigenvalue $\lambda$ form a [[Subspace]] called the eigenspace for $\lambda$.

In general,
$$A\vec{x}=\lambda\vec{x}$$
$$A\vec{x}-\lambda\vec{x}=0\Rightarrow(A-\lambda I)\vec{x}=0$$
Multiplying $\lambda$ by the [[Identity Matrix]] allows for subtracting with the matrix $A$.

### Example

$$A=\begin{bmatrix}1 & 6 \\ 5 & 2\end{bmatrix},\:\vec{x}=\begin{bmatrix}x_1 \\ x_2\end{bmatrix},\:A\vec{x}=7\vec{x}$$

Is 7 an eigenvalue of $A$? Or: is there a vector $\vec{x}$ such that the equation is satisfied?

$$\begin{bmatrix}1 & 6 \\ 5 & 2\end{bmatrix}\begin{bmatrix}x_1 \\ x_2\end{bmatrix}=\begin{bmatrix}7x_1 \\ 7x_2\end{bmatrix}$$

$$
\begin{cases}
x_1+6x_2=7x_1 \\
5x_1+2x_2=7x_2
\end{cases}\Rightarrow\begin{cases}
-6x_1+6x_2=0 \\
5x_1-5x_2=0
\end{cases}
$$

constructing an [[Linear Algebra#Augmented Matrix of Coefficients|augmented matrix]]: $$\begin{bmatrix}-6 & 6 & 0 \\ 5 & -5 & 0\end{bmatrix}\rightarrow\begin{bmatrix}1 & -1 & 0 \\ 0 & 0 & 0\end{bmatrix}$$ let $x_2=s$, then: $x_1=s$ and: $$\vec{x}=\begin{bmatrix}s \\ s\end{bmatrix}=s\cdot\begin{bmatrix}1 \\ 1\end{bmatrix},\:s\in\mathbb{R}$$
Therefore, any scalar multiple of $\begin{bmatrix}1 \\ 1\end{bmatrix}$ is an eigenvector for the eigenvalue $\lambda=7$.

### Example

Let:

$$
\begin{bmatrix}
3 & -2 \\
1 & 0
\end{bmatrix},\:\vec{v}=\begin{bmatrix}2 \\ 1\end{bmatrix}
$$

$$
A\cdot\vec{v}=\begin{bmatrix}4 \\ 2\end{bmatrix}=2\cdot\vec{v}
$$

This result is specific to this vector.

let: $$\vec{u}=\begin{bmatrix}-1 \\ 1\end{bmatrix}\Rightarrow A\cdot\vec{u}=\begin{bmatrix}-5 \\ -1\end{bmatrix}$$ which is not a multiple of $\vec{u}$

$$
$$

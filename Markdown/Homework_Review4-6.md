## Homework 4
### Question 1: Quantum Fourier Transformation
Suppose that we have a 3-qubit quantum Fourier Transformation circuit. Write the matrix form of the Fourier matrix and prove that it is unitary.

<div STYLE="page-break-after: always;"></div>

### Question 2: Shor’s algorithm

Given \( x = 2 \), \( N = 7 \);
(a): How many qubits are needed for the oracle?
(b): Write the matrix form of \( U \) and prove that it is unitary.

<div STYLE="page-break-after: always;"></div>

## Homework 5
### Question 1

Prove that **an arbitrary density matrix for a mixed state qubit can be written as**:
\[
\rho = \frac{I + \vec{r} \cdot \vec{\sigma}}{2}
\]
where \(\vec{r} = \{r_1, r_2, r_3\}\) is a real three-dimensional vector with \(r_1^2 + r_2^2 + r_3^2 \leq 1\), and \(\vec{\sigma}\) denotes the vector of Pauli matrices \(\{X, Y, Z\}\). This vector \(\vec{r}\) is called the Bloch vector for the state \(\rho\).

<div STYLE="page-break-after: always;"></div>

### Question 2
Show that, for the Shor’s nine-qubit encoding state, recovery from a phase flip on any of the first three qubits may be accomplished by applying the operator $Z_1Z_2Z_3$.

<div STYLE="page-break-after: always;"></div>

## Homework 6
### Question 1 
Prove that the following circuit is a CNOT gate, given that the matrix form of the beam splitter is  
\[
\begin{bmatrix}
r & it \\
it & r
\end{bmatrix}
\]

<div STYLE="page-break-after: always;"></div>

## Question 2

Consider a \(4 \times 4\) unitary matrix
\[
\frac{1}{2}
\begin{bmatrix}
1 & 1 & i & i \\
1 & -1 & i & -i \\
i & i & 1 & 1 \\
i & -i & 1 & -1
\end{bmatrix}
\]

with 4 input and 4 output ports. If we inject two photons into input ports 1 and 2, calculate the probability of detecting two photons at the output ports \(\{1,2\}, \{1,3\}, \{1,4\}, \{2,3\}, \{2,4\}, \{3,4\}\) individually.K
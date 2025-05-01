## Homework 1
### Question 1: Understanding of qubit states on Bloch sphere
 
Prove that the two single qubit states \( |\psi_1\rangle \) and \( |\psi_2\rangle \) in Figure 1 on the Bloch sphere, which are connected by a diameter, are orthogonal to each other.

<div STYLE="page-break-after: always;"></div>

### Quesion 2: The single qubit gate

Proving that a single qubit gate can be represented as the following unitary matrix:

$$
U = \begin{bmatrix} a & b^* \\ b & -a^* \end{bmatrix}
$$

Where $|a|^2 + |b|^2 = 1$, and $a$, $b$ are complex numbers.

<div STYLE="page-break-after: always;"></div>

### Question 3: The Measurement Basis

Find the eigenvalues and corresponding eigenvectors of the matrix:  \( A = \begin{bmatrix} 0 & i \\ -i & 0 \end{bmatrix} \)  
If the measurement operator is the Pauli \( Y \) matrix in the standard basis, determine the measurement basis and calculate the average value of the measurement when the quantum state is:  \( |\varphi\rangle = \frac{1}{\sqrt{3}}|0\rangle + \frac{\sqrt{2}}{\sqrt{3}}|1\rangle. \)

<div STYLE="page-break-after: always;"></div>

### Question 4

Proving that the entangled state **\( \frac{1}{\sqrt{2}}(|01\rangle + |10\rangle) \)** cannot be expressed as a tensor product of two single-qubit states.

The hint: starting with the general tensor product of two single-qubit states, which is: \(
(|\psi\rangle \otimes |\phi\rangle) = (\alpha|0\rangle + \beta|1\rangle)(\gamma|0\rangle + \delta|1\rangle)
\) Then expand and compare.

<div STYLE="page-break-after: always;"></div>

### Question 6: More circuit identities
 
Let subscripts denote which qubit an operator acts on, and let \( C \) be a CNOT with qubit 1 as the control qubit and qubit 2 as the target qubit.  

Prove the following identities and draw the quantum circuits for the equations:

\(
C X_1 C = X_1 X_2
\) (1)  

\(
C Y_1 C = Y_1 X_2
\) (2)  

\(
C Z_1 C = Z_1
\) (3)  

\(
C X_2 C = X_2
\) (4)  

\(
C Y_2 C = Z_1 Y_2
\) (5)  

\(
C Z_2 C = Z_1 Z_2
\) (6)  

\(
R_{z,1}(\theta) C = C R_{z,1}(\theta)
\) (7)  

\(
R_{x,2}(\theta) C = C R_{x,2}(\theta)
\) (8)  

<div STYLE="page-break-after: always;"></div>

### Question 7

Calculate the output state of the following quantum circuit and determine the probability of obtaining the state **∣000⟩** upon measurement.

<div STYLE="page-break-after: always;"></div>

## Homework 2

### Question 1: Simon's Algorithm

(a) Give the starting state of Simon’s algorithm.

(b) Give the state after the first Hadamard transforms on the first 3 qubits.

(c) Give the state after applying the oracle.

(d) Give the state after measuring the second register (suppose the measurement gave \(|001\rangle\)).

(e) Using \( H^{\otimes n} |i\rangle = \frac{1}{\sqrt{2^n}} \sum_{j \in \{0,1\}^n} (-1)^{i \cdot j} |j\rangle \), give the state after the final Hadamards.

(f) Why does a measurement of the first 3 qubits of the final state give information about \( s \)?

(g) Suppose the first run of the algorithm gives \( j = 011 \) and a second run gives \( j = 101 \). Show that, assuming \( s \neq 000 \), these two runs already determine \( s \).

<div STYLE="page-break-after: always;"></div>

### Question 2: Grover
(Grover’s algorithm) Suppose we apply Grover’s algorithm to a 3-qubit register, in which only the state \( |010\rangle \) is marked.  
What is the probability of measuring the marked state \( |010\rangle \) after applying the Grover iterate 0,1,2,3 times? And draw the quantum circuit of Oracle \( V \). 

<div STYLE="page-break-after: always;"></div>

## Homework 3
### Question 1: Measurement basis
 
To perform a quantum state measurement using a quarter-wave plate (QWP), a half-wave plate (HWP), and a polarizing beam splitter (PBS) as shown in Figure 1(a) and (b), what angles should the QWP and HWP be set to in order to measure in the Pauli X, Y, and Z basis? (Finding one set of angles is sufficient.)

<div STYLE="page-break-after: always;"></div>

### Question 2: Mach-Zehnder Interferometer
Considering the circuit as shown in Figure 2, where \( \varphi \) means that we add a phase \( e^{i\varphi} \) in the path. The mirror only changes the direction of light. Calculate the probability for detecting in the output port.

<div STYLE="page-break-after: always;"></div>

### Question 3: CNOT Gate

If we design a circuit as shown in Figure 3, prove that it can realize a CNOT gate with a postselection process. Here, PPBS B adjusts the amplitudes of local horizontal (H) and vertical (V) components of photonic qubits by transmitting (reflecting) 1/3 (2/3) of vertically polarized light and transmitting horizontally polarized light perfectly. PPBS A adjusts the amplitudes by reflecting (transmitting) 1/3 (2/3) of horizontally polarized light and reflecting vertically polarized light perfectly.
# 아다마르 게이트(H)Hadamard gate중첩상태로 만들어줌

https://economiceco.tistory.com/14012

<hr>

# 고전 컴퓨터에서 덧셈 로직으로 표현

![Screenshot 2023-11-08 at 8 49 32 PM](https://github.com/YoungHaKim7/Cpp_Training/assets/67513038/64ed157a-b4bd-433c-8869-9a93d42fa70f)

<hr>

# 양자 컴퓨터 로직 게이트 예시 

![quantum](https://github.com/YoungHaKim7/Cpp_Training/assets/67513038/59d6a894-e21d-4b3a-8d3f-05d2deb9ff89)

- Hadamard gate 아다마르게이트(H) 
  - 중첩상태로 만들어주는 하다마다 게이트 0과 1을 중첩상태로 만들어줌 .

- Hadamard 게이트와 CNOT게이트를 붙이면 중첩상태로 가능 

![quantum_superposition](https://github.com/YoungHaKim7/Cpp_Training/assets/67513038/fe4b79e9-f2e6-4de6-9917-03feee66355a)

```math

\frac{1}{\sqrt{2}} |0⟩(|0⟩) + \frac{1}{\sqrt{2}} |0⟩(|1⟩) CNOT | 0>
```

- ``` \frac{1}{\sqrt{2}} |0⟩(|0⟩) + \frac{1}{\sqrt{2}} |0⟩(|1⟩) CNOT | 0> ```

https://en.wikipedia.org/wiki/List_of_mathematical_symbols_by_subject

https://quantumcomputing.meta.stackexchange.com/questions/49/tutorial-how-to-use-tex-mathjax-to-render-math-notation

https://math.stackexchange.com/questions/20412/element-wise-or-pointwise-operations-notation

<hr>

- 그림으로 양자 이해하기 

![pic01](https://github.com/YoungHaKim7/Cpp_Training/assets/67513038/1b30816a-838e-4785-8a43-eedc2e430516)


![qauntum](https://github.com/YoungHaKim7/Cpp_Training/assets/67513038/058f56ed-9203-4c68-8788-53d040c4687e)

```math
Pauli-X(X)=
 \begin{bmatrix}
  0 & 1 \
  1 & 0 \
 \end{bmatrix}
```
```math
Pauli-Y(Y)=
 \begin{bmatrix}
  0 & -\imath \
  \imath & 0 \
 \end{bmatrix}
```
```math
Pauli-Z(Z)=
 \begin{bmatrix}
  1 & 0 \
  0 & -1 \
 \end{bmatrix}
```
```math
Hadamard(H)=
 \frac{1}{\sqrt{2}}\begin{bmatrix}
  1 & 1 \
  1 & -1 \
 \end{bmatrix}
```
```math
Phase(S,P)=
 \begin{bmatrix}
  1 & 0 \
  0 & \imath \
 \end{bmatrix}
```
```math
\frac{\pi}{8}(T)=
 \begin{bmatrix}
  1 & 0 \
  0 & e^\frac{\imath\pi}{4} \
 \end{bmatrix}
```
```math
Controlled Not(CNOT,CX)=
 \begin{bmatrix}
  1 & 0 & 0 & 0 \
  0 & 1 & 0 & 0 \
  0 & 0 & 0 & 1 \
  0 & 0 & 1 & 0 \
 \end{bmatrix}
```

```math
Controlled Z(CZ)=
 \begin{bmatrix}
  1 & 0 & 0 & 0 \
  0 & 1 & 0 & 0 \
  0 & 0 & 1 & 0 \
  0 & 0 & 0 & -1 \
 \end{bmatrix}
```

```math
SWAP=
 \begin{bmatrix}
  1 & 0 & 0 & 0 \
  0 & 0 & 1 & 0 \
  0 & 1 & 0 & 0 \
  0 & 0 & 0 & 1 \
 \end{bmatrix}
```

- 8차원??
```math
Toffoli(CCNOT,CCX,TOFF=
 \begin{bmatrix}
  1 & 0 & 0 & 0 & 0 & 0 & 0 & 0 \
  0 & 1 & 0 & 0 & 0 & 0 & 0 & 0 \
  0 & 0 & 1 & 0 & 0 & 0 & 0 & 0 \
  0 & 0 & 0 & 1 & 0 & 0 & 0 & 0 \
  0 & 0 & 0 & 0 & 1 & 0 & 0 & 0 \
  0 & 0 & 0 & 0 & 0 & 1 & 0 & 0 \
  0 & 0 & 0 & 0 & 0 & 0 & 0 & 1 \
  0 & 0 & 0 & 0 & 0 & 0 & 1 & 0 \
 \end{bmatrix}
```

<img src="https://upload.wikimedia.org/wikipedia/commons/thumb/e/e0/Quantum_Logic_Gates.png/440px-Quantum_Logic_Gates.png" />

https://en.wikibooks.org/wiki/LaTeX/Mathematics

swift로 매트릭스 구현 https://github.com/hollance/Matrix/blob/master/README.markdown


<img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*3coG-0hl3foXn3ZCU4KnBw.jpeg" />

<img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*2Hkbm7QIyBQfc8vKX7S9vw.jpeg" />

https://en.wikipedia.org/wiki/Quantum_logic_gate

https://medium.com/quantum-untangled/visualizing-quantum-logic-gates-part-1-515bb7b58916

<hr>


- Quantum Computing
  - https://en.wikipedia.org/wiki/Quantum_computing

- Pauli_matrices
  - https://en.wikipedia.org/wiki/Pauli_matrices

- Entanglement Entropy in XYZ model
  - https://www.ggi.infn.it/talkfiles/slides/talk681.pdf

<hr>

- 표준연이 만든 초전도체 기반 초대형 양자컴퓨터의 정체?! (한국표준과학연구원 최재혁 박사) | 안될과학 Unrealscience

https://youtu.be/WDFS6g7F8Rk?si=7RA3LXqiH4-0SkH2

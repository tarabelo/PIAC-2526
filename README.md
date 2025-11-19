# PIAC Parte 2. Algoritmos para optimización cuántica
Apuntes de Programación e implementación de algoritmos cuánticos, Máster Universitario en Ciencia e Tecnoloxías de Información Cuántica, USC. Curso 2025/26.

Tomás Fernández Pena
tf.pena@usc.es
CiTIUS Despacho 113

## Temario

1. <a href="https://colab.research.google.com/github/tarabelo/PIAC-2526/blob/main/01%20-%20Problemas%20QUBO%20y%20modelo%20Ising.ipynb" target="_blank">Problemas QUBO y modelo Ising</a>
    - <a href="https://colab.research.google.com/github/tarabelo/PIAC-2526/blob/main/01%20-%20Problemas%20QUBO%20y%20modelo%20Ising.ipynb#intro" target="_blank">Introducción a los problemas de optimización</a>
    - <a href="https://colab.research.google.com/github/tarabelo/PIAC-2526/blob/main/01%20-%20Problemas%20QUBO%20y%20modelo%20Ising.ipynb#qubo" target="_blank">Problemas de optimización binaria cuadrática sin restricciones (QUBO)</a>
    - <a href="https://colab.research.google.com/github/tarabelo/PIAC-2526/blob/main/01%20-%20Problemas%20QUBO%20y%20modelo%20Ising.ipynb#ising" target="_blank">Modelo Ising</a>
    - <a href="https://colab.research.google.com/github/tarabelo/PIAC-2526/blob/main/01%20-%20Problemas%20QUBO%20y%20modelo%20Ising.ipynb#equivalencia" target="_blank">Equivalencia QUBO/Ising</a>
    - <a href="https://colab.research.google.com/github/tarabelo/PIAC-2526/blob/main/01%20-%20Problemas%20QUBO%20y%20modelo%20Ising.ipynb#restricciones" target="_blank">Problemas de optimización binaria con restricciones</a>
    - <a href="https://colab.research.google.com/github/tarabelo/PIAC-2526/blob/main/01%20-%20Problemas%20QUBO%20y%20modelo%20Ising.ipynb#otros" target="_blank">Otros problemas de optimización</a>
2. <a href="https://colab.research.google.com/github/tarabelo/PIAC-2526/blob/main/02%20-%20Computaci%C3%B3n%20cu%C3%A1ntica%20adiab%C3%A1tica%20y%20Quantum%20Annealing.ipynb" target="_blank">Computación cuántica adiabática y Quantum Annealing</a>
    - <a href="https://colab.research.google.com/github/tarabelo/PIAC-2526/blob/main/02%20-%20Computaci%C3%B3n%20cu%C3%A1ntica%20adiab%C3%A1tica%20y%20Quantum%20Annealing.ipynb" target="_blank">Computación cuántica adiabática</a>
    - <a href="https://colab.research.google.com/github/tarabelo/PIAC-2526/blob/main/02%20-%20Computaci%C3%B3n%20cu%C3%A1ntica%20adiab%C3%A1tica%20y%20Quantum%20Annealing.ipynb#annealing" target="_blank">Quantum annealing</a>
    - <a href="https://colab.research.google.com/github/tarabelo/PIAC-2526/blob/main/02%20-%20Computaci%C3%B3n%20cu%C3%A1ntica%20adiab%C3%A1tica%20y%20Quantum%20Annealing.ipynb#annealers" target="_blank">Quantum annealers</a>
    - <a href="https://colab.research.google.com/github/tarabelo/PIAC-2526/blob/main/02%20-%20Computaci%C3%B3n%20cu%C3%A1ntica%20adiab%C3%A1tica%20y%20Quantum%20Annealing.ipynb#CQM" target="_blank">Problemas binarios cuadráticos con restricciones (CQM)</a>
    - <a href="https://colab.research.google.com/github/tarabelo/PIAC-2526/blob/main/02%20-%20Computaci%C3%B3n%20cu%C3%A1ntica%20adiab%C3%A1tica%20y%20Quantum%20Annealing.ipynb#Embedding" target="_blank">Embedding</a>
3. <a href="https://colab.research.google.com/github/tarabelo/PIAC-2526/blob/main/03%20-%20Circuitos%20parametrizados%20y%20algoritmos%20variacionales.ipynb" target="_blank">Circuitos parametrizados y algoritmos variacionales</a>
    - <a href="https://colab.research.google.com/github/tarabelo/PIAC-2526/blob/main/03%20-%20Circuitos%20parametrizados%20y%20algoritmos%20variacionales.ipynb#variacionales" target="_blank">Algoritmos cuánticos variacionales</a>
    - <a href="https://colab.research.google.com/github/tarabelo/PIAC-2526/blob/main/03%20-%20Circuitos%20parametrizados%20y%20algoritmos%20variacionales.ipynb#parametros" target="_blank">Circuitos parametrizados en Qiskit</a>
4. <a href="https://colab.research.google.com/github/tarabelo/PIAC-2526/blob/main/04%20-%20Algoritmo%20cu%C3%A1ntico%20de%20optimizaci%C3%B3n%20aproximada%20(QAOA).ipynb" target="_blank">Algoritmo cuántico de optimización aproximada (QAOA)</a>
    - <a href="https://colab.research.google.com/github/tarabelo/PIAC-2526/blob/main/04%20-%20Algoritmo%20cu%C3%A1ntico%20de%20optimizaci%C3%B3n%20aproximada%20(QAOA)#trotter.ipynb" target="_blank">Discretización de la evolución adiabática (*Trotterization*)</a>
    - <a href="https://colab.research.google.com/github/tarabelo/PIAC-2526/blob/main/04%20-%20Algoritmo%20cu%C3%A1ntico%20de%20optimizaci%C3%B3n%20aproximada%20(QAOA).ipynb#qaoa" target="_blank">Quantum Approximate Optimization Algorithm (QAOA)</a>
    - <a href="https://colab.research.google.com/github/tarabelo/PIAC-2526/blob/main/04%20-%20Algoritmo%20cu%C3%A1ntico%20de%20optimizaci%C3%B3n%20aproximada%20(QAOA).ipynb#cuadraticos" target="_blank">Programas cuadráticos con restricciones cuadráticas</a>
    - <a href="https://colab.research.google.com/github/tarabelo/PIAC-2526/blob/main/04%20-%20Algoritmo%20cu%C3%A1ntico%20de%20optimizaci%C3%B3n%20aproximada%20(QAOA)#variantes.ipynb" target="_blank">Variantes de QAOA</a>
5. Algoritmo cuántico variacional para el cálculo de autovalores (VQE)
6. Busqueda adaptativa de Grover (GAS)

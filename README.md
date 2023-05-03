
# Blazor Rubik's Cube Solver

This Blazor Project has the main goal of helping the user to solve a Rubik's cube (initially 3x3x3 and 2x2x2).

With intuitive visuals and a very simplistic approach, the software can aid in learning how to solve the puzzle or even just solving it while blindly following the instructions given. As a group, all of our members had never messed with Blazor before (only had some background experience in C#), so it's proven to be kind of a challenge to us!

The application has easy to select modes of operation, checks for input errors in the user side, and solves the cube with relative ease using the common layer method for the 3x3 and the Ortega method for the 2x2.
## Autores

- [@andrevpc](https://github.com/andrevpc)
- [@emanuelly-b-s](https://github.com/emanuelly-b-s)
- [@PeterMontez](https://github.com/PeterMontez)
## Referência

This project solves the cube using a raw c# solver, mantained by one of us
 - [CubeSolver by PeterMontez](https://github.com/PeterMontez/CubeSolver)


## Funcionalidades

- Cubos 2x2 e 3x3
- Algoritmo de resolução simples
- Check de erros de input
- Multiplataforma


## FAQ

#### Isn't it better to use a more efficient algorithm, like the kociemba?

Yes, it would lead to more move-efficient solves, but at the cost of a long installation time, considering all the tables that need to be generated.
Also, our goal is to help the user to see what is actually going on, what the algorithm is currently doing, facilitating for those already learning the beginners method.

#### Why Blazor?

Great question. We intended to use MAUI, but being such a new framework, we opted for Blazor instead, considering all of us had very little multiplatform experience, and (at least me) are not very keen to front-end developing.

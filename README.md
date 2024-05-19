# WolfSheepCabbageSolver

## Overview

**WolfSheepCabbageSolver** is a Java application that solves the classic river-crossing puzzle known as the "Sheep, Wolf, and Cabbage" problem. In this puzzle, a farmer must transport a wolf, a sheep, and a cabbage across a river using a boat that can only carry one item at a time, without leaving the wolf alone with the sheep or the sheep alone with the cabbage.

## Problem Description

The rules of the puzzle are as follows:
1. The wolf cannot be left alone with the sheep (the wolf will eat the sheep).
2. The sheep cannot be left alone with the cabbage (the sheep will eat the cabbage).
3. The farmer can only carry one item (the wolf, the sheep, or the cabbage) at a time in the boat.

The goal is to get all three items across the river safely.

## Solution

The solution to the puzzle involves a series of steps where the farmer carefully transports the items across the river. The steps are as follows:
1. Take the sheep across the river.
2. Return alone to the original side.
3. Take the wolf across the river.
4. Bring the sheep back to the original side.
5. Take the cabbage across the river.
6. Return alone to the original side.
7. Take the sheep across the river again.

## Implementation

The application is implemented in Java and includes a main class, `Main.java`, which contains the logic for solving the puzzle.

### Files
- `Main.java`: The main class containing the puzzle-solving logic.

### Usage

1. Clone the repository:
    ```sh
    git clone https://github.com/ba6tati/WolfSheepCabbageSolver.git
    ```
2. Navigate to the project directory:
    ```sh
    cd WolfSheepCabbageSolver/src
    ```
3. Compile the Java file:
    ```sh
    javac Main.java
    ```
4. Run the application:
    ```sh
    java Main
    ```

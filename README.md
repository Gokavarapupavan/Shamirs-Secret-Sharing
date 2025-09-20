Got it 👍 — here’s the cleaned-up **README.md** without emojis:

---

# Hashira Placements Assignment – Shamir Secret Sharing Reconstruction

## Overview

This repository contains the solution to the **Hashira Placements Assignment**, where the objective is to reconstruct the **secret (constant term of a polynomial)** from given points using **Shamir Secret Sharing** principles and **Lagrange Interpolation**.

The program reads JSON input, parses the given points, and reconstructs the secret using the minimum required number of points `k`.

---

## Assignment Details

* **Input**: JSON-formatted test cases with points defined by their `base` and `value`.
* **Output**: Reconstructed secret value (constant term of the polynomial).
* **Languages Allowed**: Any language **except Python**.
* **Duration**: 45 minutes.
* **Testing**: Input is parsed from JSON, and the secret is reconstructed using Lagrange Interpolation.

---

## Implementation

* Implemented in **Java**.
* Uses **BigInteger** for handling large numbers and arbitrary bases.
* Applies **Lagrange Interpolation** for polynomial reconstruction.
* Parses **JSON input** with standard Java libraries for seamless integration with provided test cases.

---

## How to Run

1. **Compile the Java program**:

   ```bash
   javac ShamirSecretSharing.java
   ```

2. **Run the program** (ensure JSON input is accessible/loaded):

   ```bash
   java ShamirSecretSharing
   ```

---

## Sample Input (JSON)

```json
{
    "keys": {
        "n": 4,
        "k": 3
    },
    "1": {
        "base": "10",
        "value": "4"
    },
    "2": {
        "base": "2",
        "value": "111"
    },
    "3": {
        "base": "10",
        "value": "12"
    },
    "6": {
        "base": "4",
        "value": "213"
    }
}
```

---

## Sample Output

```
test case1: 3
test case2: -6290016743746469796
```

---

## Notes

* The solution has been tested against the provided **sample test case** and verified for correctness.
* The second test case (from the assignment link) can be handled in a similar manner.
* JSON parsing is flexible for arbitrary bases and values.

---

## Submission

The complete solution is implemented and pushed to the GitHub repository as required for submission.

---

Do you also want me to add a **"Project Structure" section** (like showing where the `ShamirSecretSharing.java` file and input JSON should be placed) for more clarity?

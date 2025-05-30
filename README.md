# Computational Experiments for *Dual-Driven Path Elimination for Vehicle Routing with Idle Times and Arrival-Time Consistency*

This repository contains the input and output files associated with the computational experiments described in the article *Dual-Driven Path Elimination for Vehicle Routing with Idle Times and Arrival-Time Consistency*.

## Repository Structure

### `input/`
This folder contains two subdirectories:

- **`Initial feasible solutions/`**: Includes the feasible solutions generated by the initial heuristic proposed in this work.
- **`Subramanyan & Gounaris/`**: Contains ConTSP input files obtained from [http://gounaris.cheme.cmu.edu/datasets/contsp/](http://gounaris.cheme.cmu.edu/datasets/contsp/).

### `output/`
This folder also contains two subdirectories:

- **`compact + connect/`**: Output from the algorithm based on the compact formulation with connectivity cuts.
- **`ipec/`**: Output from the algorithm based on the proposed path elimination model with infeasibility-driven cuts.

Each of these folders includes a `.csv` file summarizing detailed results for all tested instances. Additionally, for each instance family:

- The **`log/`** subfolder contains CPLEX log files generated during the solution process.
- The **`sol/`** subfolder contains the corresponding solution files.

---

For any questions or clarifications, feel free to contact jriera@ull.es.

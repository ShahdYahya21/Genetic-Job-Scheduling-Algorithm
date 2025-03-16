## Genetic-Job-Scheduling-Algorithm 

### Project Focus:
- Optimizing job shop scheduling in a manufacturing plant using a genetic algorithm to minimize overall completion time (makespan).

---

### Genetic Algorithm Process:

1. **Initialization**: Creates an initial population of chromosomes, each representing a permutation of job indices.
2. **Fitness Evaluation**: The fitness of each chromosome is evaluated by calculating the total completion time for the schedule.
3. **Selection**: Parents are selected based on their fitness using tournament selection.
4. **Crossover**: Parents undergo crossover to produce new offspring.
5. **Mutation**: The offspring are mutated with a certain probability.
6. **New Population**: The new population is formed by replacing the old population with the children. The process repeats for several generations.

---

### Scheduling Function:

The scheduling function takes a chromosome (permutation of jobs) and a list of jobs as input and returns the total time to complete all jobs based on the order specified by the chromosome. It assigns tasks to machines based on availability and order, and calculates the waiting time for each task.

---

### Chromosome Representation:

A **chromosome** represents a permutation of job indices. Each integer in the list represents a job, and the order in the list defines the processing sequence. For example, a chromosome `[2, 3, 1]` means job 2 is processed first, followed by job 3, and then job 1.

The genetic algorithm uses these chromosomes to explore different possible schedules and find the one that minimizes the total completion time.

---


<img width="1088" alt="image" src="https://github.com/user-attachments/assets/0df797a9-8c85-453d-b7bb-fc91d23d9dfe" />

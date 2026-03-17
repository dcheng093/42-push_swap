*This project has been created as part of the 42 curriculum by dcheng.*

<p align="center">
  <img src="https://media3.giphy.com/media/v1.Y2lkPTc5MGI3NjExcW1kdjZwM2h2YXQzZHQ2NGZ1ZDl5aDRncms4d2Rla2UzdHF1dGFrZyZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/O8dCwBMsKWwtfrcgQs/giphy.gif" alt="cute gif" width="300"/>
</p>

---

Table of contents
- [Description](#description)
- [Instructions](#instructions)
- [Execution](#execution)
- [Resources](#resources)


## Description
Push_swap is a project where the goal is to write a program that calculates and prints the most efficient sequence of instructions to sort a list of integers. The program uses only a limited set of stack operations (push, swap, rotate, reverse rotate) to achieve this. This is by far my least favorite project, as most of my time was spent fixing bugs rather than the actual implementation of the algorithm. This resulted in the time taken to finish push_swap to go from 4 days to nearly 3 weeks, I will go into more depth regarding the fixes I've done in the evaluation itself. A benchmark for how efficient the program is sorting x amount of numbers under y amount of operations, as shown below:

* For maximum project validation (100%) and eligibility for bonuses, you must:
  - Sort 100 random numbers in fewer than 700 operations.
  - Sort 500 random numbers in no more than 5500 operations.
* For minimal project validation (which implies a minimum grade of 80%), you can succeed with different averages:
  - 100 numbers in under 1100 operations and 500 numbers in under 8500 operations
  - 100 numbers in under 700 operations and 500 numbers in under 11500 operations
  - 100 numbers in under 1300 operations and 500 numbers in under 5500 operations

---

## Instructions

### Compilation

Compile the project using `make`:

```bash
make
```

This will generate the executable:

```bash
./push_swap
```

### Execution

Run the program with a list of integers as arguments to get the list of operations needed to sort it:

```bash
./push_swap 3 2 1
```

Run the program with the checker from the resources of the Push_swap project page.

```bash
./push_swap 3 2 1 | ./checker_linux 3 2 1
```

---

## Allowed Operations

* `pa`, `pb` — push the top element from one stack to the other
* `ra`, `rb`, `rr` — rotate a stack upward
* `rra`, `rrb`, `rrr` — rotate a stack downward

## Resources

- Turk Sort Algorithm: https://pure-forest.medium.com/push-swap-turk-algorithm-explained-in-6-steps-4c6650a458c0pedeepeppepeppepepeppepeppepepepep
- Gitbook: https://42-cursus.gitbook.io/guide/2-rank-02/push_swap
- Visualizer: https://github.com/dcheng093/push_swap_visualizer
- Referring to other people's implementations of push_swap on github

### Use of AI

AI was used to help debug my code and adjust it to comply with norminette's style as well as helping me find extra edge cases that resulted in my program seg-faulting.

<img width="1054" height="1864" alt="image" src="https://github.com/user-attachments/assets/1e6bd903-24bc-4cd9-aa46-8a34c96d5403" />
<img width="3125" height="990" alt="image" src="https://github.com/user-attachments/assets/0827e524-bc5f-4d86-b930-e2017623b801" />
<img width="3125" height="1830" alt="image" src="https://github.com/user-attachments/assets/69905d36-1757-4aba-8cc2-269748d713a4" />
<img width="3125" height="1852" alt="image" src="https://github.com/user-attachments/assets/d6c7b1af-0172-4b36-b2a8-3c2bfcfd7e65" />
<img width="3125" height="1720" alt="image" src="https://github.com/user-attachments/assets/fa99a01e-2803-4ab2-bda5-ce148ccce2db" />


<img width="2575" height="1792" alt="image" src="https://github.com/user-attachments/assets/1cd4f750-4cb3-40a5-b6f9-26b4410b36f2" />
<img width="2575" height="1832" alt="image" src="https://github.com/user-attachments/assets/c48eff65-d398-43d5-8632-039f39c30d35" />
<img width="2575" height="1362" alt="image" src="https://github.com/user-attachments/assets/ebefa882-398d-4b9e-aa35-0de8a0ea41ca" />
<img width="2575" height="1820" alt="image" src="https://github.com/user-attachments/assets/53ee5460-a720-4be9-97df-ca8dece12dcd" />


<img width="1497" height="816" alt="image" src="https://github.com/user-attachments/assets/0b848542-9729-414c-94a4-d2d98824b35f" />
<img width="1498" height="529" alt="image" src="https://github.com/user-attachments/assets/b059f91c-d463-4256-bb15-108d8ceafa6b" />


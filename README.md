# Commonsense Validation and Explanation (ComVE)

## Introduction

The task is to directly test whether a system can differentiate natural language statements that make sense from those that do not make sense. We designed three subtasks. The first task is to choose from two natural language statements with similar wordings which one makes sense and which one does not make sense; The second task is to find the key reason from three options why a given statement does not make sense;

The detailed description of the task can be found in [Task Proposal](./TaskProposal.pdf).

### Example

#### Task A: Commonsense Validation

Which statement of the two is against common sense?

- Statement 1: He put a turkey into the fridge. *(correct)*
- Statement 2: He put an elephant into the fridge.

#### Task B: Commonsense Explanation (Multi-Choice)

Select the most corresponding reason why this statement is against common sense.

- Statement: He put an elephant into the fridge.

- Reasons:

  - **A**: An elephant is much bigger than a fridge. *(correct)*
  - **B**: Elephants are usually white while fridges are usually white.



## Evaluation

Subtask A and B will be evaluated using **accuracy**


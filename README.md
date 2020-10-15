# Commonsense Validation and Explanation (ComVE)

## Introduction

The task is to directly test whether a system can differentiate natural language statements that make sense from those that do not make sense. Two subtasks based on SemEval 2020 are designed. The first task is to choose from two natural language statements with similar wordings which one makes sense and which one does not make sense; The second task is to find the key reason from three options why a given statement does not make sense. In this project we will implement subtask 1.


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

## Data format

The file format for all two subtasks are csv.

For subtask A, each row of the csv file contains 3 fields: `id`, `sent0`, `sent1`, which are the ID of the instance, and two input sentences. The output file contains no header, and each row contains the id and the index of the sentence which makes sense.

For subtask B, each row of the csv file contains 5 fields: `id`, `FalseSent`, `OptionA`, `OptionB` , `OptionC`, which are the ID of the instance, the nonsensical sentence, and three reasons why the sentence does not make sense. The output contains no header, and each row contains the id and label of the correct reason.


# Commonsense Validation and Explanation

## Introduction

The research project is to directly test whether a system can differentiate natural language statements that make sense from those that do not make sense. This project is designed based on SemEval2020 task 4 subtaskA. The task is to choose from two natural language statements with similar wordings which one makes sense and which one does not make sense.


### Example

#### Task A: Commonsense Validation

Which statement of the two is against common sense?

- Statement 1: He put a turkey into the fridge. *(correct)*
- Statement 2: He put an elephant into the fridge.




## Evaluation

Subtask A will be evaluated using **accuracy**

## Data format

The file format is csv.

Each row of the csv file contains 3 fields: `id`, `sent0`, `sent1`, which are the ID of the instance, and two input sentences. The output file contains no header, and each row contains the id and the index of the sentence which makes sense.


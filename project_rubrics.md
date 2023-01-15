# Rubrics of a data science project

## Report

- Exploratory data analysis: what are the features of the dataset
- Your solution:
- Why did you choose this approach?
- Your implementation (code)
- Discussions
- How does your solution perform?
- How can you further improve the model?

1. Introduction
    - Problem: what is the definition of the problem?
    - Scope of the problem that you choose to solve in this report (Sometimes it's not possilbe to solve the original problem)

2. Describe your solution
    - What is your algorithm for solving this problem?

2. Model analysis
    - Why did you choose this metric to assess your model? What is the relation between the metrics and the problem that you would like to solve?

3. Discussions
    - How does your solution perform?
        - Does the performance of your model achieve state-of-the-art?
    - How can you further improve the model?
        - What makes you think that the results can be further improved?


## Code

1. Fix the random seed so that the readers can reprodue your results.
2. Export the python (`pip` or `conda`) dependencies
3. The code should comply with [PEP 8 style guide](https://peps.python.org/pep-0008/)
    - Use [pylint](https://pylint.pycqa.org/en/latest/) or [black](https://github.com/psf/black) to help correct your code.

4. You are encourage to use type hints and docstrings when possible



# References

- Chapter 7, Model Analysis and Validation, Machine Learning Pipeline, O'Reilly [link](https://learning.oreilly.com/library/view/building-machine-learning/9781492053187/ch07.html#:-:text=Chapter%207.%20Model%20Analysis%20and%20Validation)
- 彭明輝, 論文寫作完全求生手冊, 台灣聯經 (Perng, A survival guide to thesis writing, Chinese version only)
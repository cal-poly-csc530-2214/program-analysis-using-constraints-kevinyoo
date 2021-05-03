# program-analysis-using-constraints-kevinyoo
program-analysis-using-constraints-kevinyoo created by GitHub Classroom

## First update
The idea of SAT/SMT is very new to me. I am picking up bits and pieces of the material during lecture regarding the negations, DeMorgan's, etc.. but am definitely struggling to understand the overarching idea from a high level. I first skimmed the paper and then read over it carefully another time and understood the big picture. Wikipedia helped a lot.

* An SAT solver, when given a boolean expression determines whether or not there exists a combination of values for each variable such that the expression is true.
* An SMT solver is an SAT solver in which variables are replaced by expressions which contain computations

## Second update
Watched [this video lecture](https://www.youtube.com/watch?v=9kKA4uBRqVo) on Youtube which was incredibly helpful in understanding the pipeline of an SMT solver. It was particularly helpful in showing how we go from a first order logic statement(is this the correct word?) to a series of boolean expressions which can be reduced to an expression that is easy to find a solution for.

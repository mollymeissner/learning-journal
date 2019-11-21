# Operators:

* ===  : Strict equal to
* !==  : Strict not equal to

### Operands are values or variables placed outside the operator
* ie: (score >= pass)
* (operand, comparison operator, operand)

### Comparison Operators: can be an expression - returning single values of true or false
* ie: ((score1 + score2) > (highScore1 + highScore2))

### Local Operators: allows you to compare the results of more than one comparison operator
((5 < 2) && (2 >+ 3))
&&: Local And (the operator tests more than 1 condition)
||: Logical Or: the operator tests at least 1 condition
!: Logical Not: the operator takes a single boolean value and inverts it

### Short-circuit evaluation: 
* If the first condition can provide enough info to get the answer, then there is no need to evaluate the 2nd condition.

* pgs 170-173, 176
### Loops
Loops check a condition. If it returns true, a code block will run. Then the condition will be checked again and if it still returns true, the code block will run again. It repeats until the condition returns false.

#### 3 common Loop types:
* for: a for loop uses a counter as a condition. This instructs the code to run a specified number of times. When the condition is no longer true, the loop ends.
ie: for (var i = 0; i < 10; i++) {
        document.write(i);
    }
  * If the variable i is less than 10, the code inside the curly braces is executed. Then the counter is incremented.
* while: use if you don't know how many times the loop will run (or how many times the user will try an input).
* do...while: it will always run the stmts inside the curly braces at least once, even if the condition evaluates to false.


# exception


## AIM :
To perform programs using exception handling 

## Software used
VS Code

## THEORY:
Exception handling is a programming construct that allows developers to manage errors or unexpected events that occur during the execution of a program. Instead of allowing the program to crash or produce incorrect results, exception handling provides a way to catch these errors. It uses `try`, `catch`, and `throw` constructs to handle exceptions, ensuring that a program can continue running or terminate safely when encountering errors.

Basic syntax involves wrapping potentially error-prone code in a `try` block and using `catch` blocks to handle exceptions:
try {
    // Code that may throw
} catch (const std::exception& e) {
    // Handle exception
}

## Key Concepts

1. **Exceptions**: Events that disrupt the normal flow of a program due to errors.

2. **Try Block**: A block of code that may throw an exception.

3. **Catch Block**: Defines how to handle specific types of exceptions.

4. **Throw Statement**: Used to signal that an error has occurred.

5. **Standard Exception Classes**: Built-in exception types provided by C++, such as `std::runtime_error` and `std::invalid_argument`.


## Algorithms
#### Age Validation Algorithm

1. **Start**.
2. **Initialize** a variable `age` to store the user's input.
3. **Prompt** the user to "Enter your age:".
4. **Read** the user's input into the variable `age`.
5. **Try** the following:
   1. **Check** if `age` is less than 0:
      - If true, **throw** an exception indicating an invalid age.
   2. **Check** if `age` is less than 18:
      - If true, **throw** an exception indicating that the user is below 18.
   3. If both checks are false, **print** "Accepted".
6. **Catch** any exceptions:
   - If the exception indicates an invalid age (less than 0), **print** "Invalid age".
   - If the exception indicates age below 18, **print** "You are below 18".
7. **End**.

#### Zerodvision Error Algorithm 

1. **Start**.
2. **Declare** variables `n1`, `n2`, and `ans` to store the two numbers and the result.
3. **Prompt** the user to "Enter the values of numbers 1 and 2:".
4. **Read** the user's input into the variables `n1` and `n2`.
5. **Try** the following:
   1. **Check** if `n2` is equal to 0:
      - If true, **throw** an exception with the value of `n2`.
   2. If the check is false, calculate `ans` as `n1 / n2`.
   3. **Print** the result as "The answer is [result]".
6. **Catch** any exceptions:
   - If an exception occurs, **print** "ERROR: Division by [number]".
7. **End**.

8. ## Conclusion
9. In this experiment we learnt how to use exception handling

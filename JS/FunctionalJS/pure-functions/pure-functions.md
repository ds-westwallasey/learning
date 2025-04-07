## Pure Functions

- only input in
- only output out

- The difference between a regular function and a **pure function** is that it only takes in it's input arguments.
- All that it does, it perform it's computation and return it's output.
- In essence it is a transformation from **input** to **output**
- there are some built in function that can be used in **pure functions**. We just need to be sure that the built in functions behaviour is deterministic

### Defining Characteristics:

- **it has no side effects**: logging to console, writing a file, posting to an endpoint
- **it is deterministic**: Given the same input values, it will always return the same out. We should want our pure function to be deterministic

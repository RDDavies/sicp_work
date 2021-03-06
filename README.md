# sicp_work
Working through SICP

1.1.3
- Tree Accumulation is the process through which the results percolate upwards. Thinking about this, it is each subprocess combining to create an independent result. For example, if you were to attempt to calculate the wheel rate of a corner of a car, the branches are the square of the motion ratio, and the spring rate on the car, and the trunk is the wheel rate. The end branch will be primitives (direct numbers, names)

1.1.4
- Compound procedures allow us to create tree accumulation via the result of functions.

1.1.5
- The substitution model allows us to trace down how a procedure works, by substituting the sequence of branches below, for the branch above.
- Applicative order (how Scheme works) processes all the operands and operators to create a procedure. This is in contrast to the "fully expand then reduce" described above, which is "normal order". 

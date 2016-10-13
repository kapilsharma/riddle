# Solution

> Please read [README.md]() to understand functional and technical requirements.

## Flow diagram

Yes, we can find one light ball among 9 identical balls using a balance just twice.

- Make 3 set of 3 balls, say A, B, & C.
- Measure weight of A & B (Using balance first time)
    - If A = B, C contains light ball
    - If A < B, A contains light ball
    - If A > B, B contains light ball
- Now we have 3 balls (say X, Y, Z), out of which 1 is slightly light in weight.
- Measure weight of X & Y (Using balance second and last time)
    - If X < Y, X is lightest
    - If X > Y, Y is lightest
    - If X = Y, Z is lightest.
    
This process can be visualized in following flow chart.

![Flow diagram](/docs/9-balls-scale.png?raw=true "Flow diagram")
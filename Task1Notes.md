In order to convert our CFG to a PDA, we first made three nodes, Q0, Q1, and Q2 where Q0 was the initial state and Q2 was the accept state. We added a looping arrow on q1 for the following rules:
λ, S -> 0S0
λ, S -> 1S1
λ, S -> λ
λ, S -> 0
λ, S -> 1
1, 1 -> λ
0, 0 -> λ

From Q0 to Q1, there is one transition arrow
λ, Z -> SZ

From Q1 to Q2, there is one transition arrow
λ, Z -> λ

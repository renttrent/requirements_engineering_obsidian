Goal: Binary Operator that describes relations between two properties followed by each other

Notation: $P \mho Q$ 
Interpretation: P has to hold at least until Q becomes true

![[Screenshot 2024-07-12 at 18.11.19.png]]

Example: If a user fails to authenticate, he is in the state logged-out until he correctly inputs his password and gets into the state logged-in
$$
\equiv \text{logged-out } \mho \text{ logged-in}
$$

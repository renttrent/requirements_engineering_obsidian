# State Machines (SM) with Inputs and Outputs

**Definition State Machine (SM)**:
A nondeterministic finite SM ($\Delta,\sum$) with input alphabet $I$ and output alphabet $O$ consists of a set of states $\sum$ , initial states $\sum_0 \subseteq \sum$  (or one initial state $\sigma_0 \in \sum$) and a state transition function
$$
\Delta: \sum \times I \rightarrow \wp (\sum \times O)
$$
- Such SMs are also called Mealy Machines
	- Output depends on input and state
- Special case Moore Machine
	- Output depends only on the state
- Notation for transitions in diagrams

![[Screenshot 2024-07-12 at 16.13.23.png]]

## From Requirements to State Machines (SM)

**Functional Requirement**:
A user needs to log into the App. After successfully logging in they can reserve a Scooter or directly start a rent. The reservation is limited to 15 min and the user would need to reserve again after that time. If the user has an active reservation, they can also start the rent for that Scooter.

Example of an FSM that formalises the mentioned requirement:
![[Screenshot 2024-07-12 at 16.16.20.png]]

[[Mathematical Logic]]
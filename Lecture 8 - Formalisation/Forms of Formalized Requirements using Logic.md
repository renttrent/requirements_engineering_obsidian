- General predicate logic without reference to general system modeling concepts:
	- Example: Crash => Airbag
- Rudimentary system terms (time, space, sequence)
	- Example of temporal logic: $\square (\text{Crash} \Rightarrow \Diamond \text{Airbag} )$
	- *The following always applies: A crash leads to the airbag being triggered (at some point in the future).*
- Formulated system model (system boundary, interface behavior)
	- Example:
	- Be crash_sensor_out and airbag_activation_in channels and be the statement m:c@t+-s the statement message m on channel c at time t (if s not in interval t-s, t+s) measured in msec.

-> [[Specification Templates]] (According to set Patterns)
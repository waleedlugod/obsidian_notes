Term | Definition
-- | --
experiment | the process by which an observation is obtained<br/>either controlled or uncontrolled
simple event | a possible outcome observed on a single repetition of an experiment<br/>denoted by E with a subscript
event | a cluster of simple events based on a condition
mutually exclusive | two events that cannot occur at the same time<br/>don't share any simple events
sample space | set of all simple events/possible outcomes<br/>denoted by S<br/>can be visualized with a tree diagram or table of events if the experiments consists of multiple stages

### Exercise 1

```mermaid
graph TD;
	roll --> heads1
	roll --> tails1
	
	heads1 --> heads2
	heads1 --> tails2
	
	tails1 --> heads3
	tails1 --> tails3
	
	heads2 --> heads4
	heads2 --> tails4
	
	tails2 --> heads5
	tails2 --> tails5
	
	heads3 --> heads6
	heads3 --> tails6
	
	tails3 --> heads7
	tails3 --> tails7
```

Event | Outcome | Is Majority
-- | -- | --
E1 | HHH | yes
E2 | HHT | yes
E3 | HTH | yes
E4 | HTT | no
E5 | THH | yes
E6 | THT | no
E7 | TTH | no
E8 | TTT | no

### Exercise 2
E = {J4, Q4, K4, A3, 22, 3A, 4J, 4Q, 4K}
22 = 12 because cannot have the same suit
outcomes = 16 * 8  +12 = 140
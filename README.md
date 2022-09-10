Code from David Lafreniere...
https://www.linkedin.com/in/lafrenieredavid

License
This article, along with any associated source code and files, is licensed under The Code Project Open License (CPOL)

https://www.codeproject.com/Articles/1087619/State-Machine-Design-in-Cplusplus-2


Creating a new state machine requires a few basic high-level steps:

1. Inherit from the StateMachine base class
2. Create a States enumeration with one entry per state function
3. Create state functions using the STATE macros
4. Optionally create guard/entry/exit functions for each state using the GUARD, ENTRY and EXIT macros
5. Create one state map lookup table using the STATE_MAP macros
6. Create one transition map lookup table for each external event using the TRANSITION_MAP macros
# Embedded System Design - Course topics

##  Lecture 1: An overview of embedded systems design
- What are embedded systems?
- Motivations and challenges
- Main reference: Marwedel

##  Lecture 2: System description with requirements and  
- System design processes overview. V-Cycle overview.
- Describing systems with requirements and use-cases
- Reference: Marwedel

##  Lecture 3: Finite state machines
- System modeling with finite state machines: states, conditions, actions, state actions, hierarchy/super-states, default state / history, time, parallel states, actions
- Reference: Marwedel, our examples

##  Lecture 4: Finite State machines (cont'd) and dataflow networks
- Other topics in finite state machines (Mealy/Moore, variables, simultaneity)
- Data flow networks (i.e. Simulink-like)

##  Lecture 5: Model-Based Design
- to fill

##  Lecture 6: Model-Based Design
 - to fill

##  Lecture 7: Embedded Systems Hardware
- Typical hardware used: processors, NvRam, sensors (input), actuators (motors)
- Design choices and tradeoffs:
   - custom processing units vs standard MCUs
   - fixed-point vs floating-point (include review of fixed-point arithmetic)
   - sensors and sampling issues (aliasing)

##  Lecture 8: Embedded System Software
- Real-Time Operating Systems: why needed, what they do
- Controlling access to shared resources: mutex / critical sections, blocking, priority inversion strategy

##  Lecture 9: Architecture
- SW architecture: approaches, decompositions, multiple ECUs, 
- what else?

##  Lecture 10: Application mapping
- Platform and application components
- Task scheduling strategy
- other stuff

##  Lecture 11: Autosar overview?

##  Lecture 12:

##  Lecture 13: Testing of Embedded Systems
- testing strategies: 

##  Lecture 14
- Review 
- we may lose 1 week during semester



- Based on the two references:
   - Introduction to Embedded Systems - A Cyber-Physical Systems Approach, Second Edition, E. A. Lee and S. A. Seshia, MIT Press, 2017, freely available ![here](http://leeseshia.org/)
   - Embedded System Design - Embedded Systems Foundations of Cyber-Physical Systems, 2nd Edition, Peter Marwedel, Springer, 2011  
      - Lecture slides available at http://ls12-www.cs.tu-dortmund.de/daes/daes/mitarbeiter/prof-dr-peter-marwedel/embedded-system-text-book/slides/slides-2013.html
      - Videos on youtube: https://www.youtube.com/user/cyphysystems/

- Relevant topics based on Marwedel:
   
I. Introduction
 - challenges, motivations etc
 - examples   
 
II. Modeling approaches
 - Starting point: Requirements, Use Cases
 - Finite states machines:
    - states, hierarchy, super-states, default state / history, time, parallel states, actions, outputs, determinate, simultaneity, Mealy / Moore - basically everything available in StateFlow
	- long part of the class, based on StateFlow, lots of examples
 - Data flow (Simulink), Petri nets?
 
III. Embedded System Hardware	
- not the focus in this class, only the bare necessities
- sensors, acquisition, sampling & aliasing, A/D and D/A conversion
- processing: fixed-point vs floating-point capability
- memory: hierarchy, fast & small --> larger but slower
- communication: buses (CAN, LIN): in short, mostly examples

IV. Embedded System Software
- Real Time Operating Systems: necessity, requirements, layered software overview (e.g. like Autosar picture)
- Access to shared resources: critical section, mutex, preemptive tasks and blockings, priority inversion for handling blocking
- Maybe an example of existing RTOS, with description of features that it provides (types of tasks etc)
- "Middleware"?

V. Evaluation and Validation
- not the focus in this class, only the bare necessities, maybe skip completely
- Worst Case Execution Time / Best Case execution time, WatchDog, static code analysis, metrics? 
- examples from Conti?

VI. Application mapping
- challenges
- Scheduling strategies (lots of them present in book, need to select just a few)

VII. Optimization
- Using fixed-point (to present here or in HW section?)
- Loop transformations? (optional)

VIII. Test strategies 
- not the focus in this class, only the bare necessities
- to check if a dedicated testing course is part of the curriculum



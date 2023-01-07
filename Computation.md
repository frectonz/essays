# What is Computation? And How do we do it?

Computation can be simply defined as the act of systematically applying rules to obtain some result. The systematic sequence of rules followed by a computer is called an **algorithm**. Following this definition of computation, a computer is anything that is able to perform those systematic sequences of rules. For much of human history, this computers were humans, although we did have analog computers that were used for specific problems. For Example, **The Antikythera mechanism** considered the oldest example of an analog computer, is a computer used to predict astronomical positions and eclipses decades in advance. These ancient examples of analog computers work by as there name implies _analogy_, they often perform the same sequence of actions that happen in the entities they are modeling, but at a smaller and more manageable scale.

The idea of **Algorithms** is so simple and so broad that any problem to be solved will inevitably follow some kind of algorithm. The first algorithms humans created were algorithms for cooking, rituals or agriculture. The idea of algorithms was later continued by the creation of multiplication algorithms in egypt, factorization and square root algorithms in babylon, Euclid's Algorithm and many more after that. Like their predecessors the mathematical algorithms listed, were written and communicated as long forms of textual instruction that describe each step that leads to the solution. Ideas that were of repeated many times in these textual instruction of mathematical algorithms slowly started being replaced by symbols that represent the operation that were to be perform and from that we get our current plethora of symbols and notations in mathematics.

See <https://en.wikipedia.org/wiki/Timeline_of_algorithms>

A question that is often posed when talking about algorithms is `What is the difference between an algorithm and a mathematical formula?`. For Example, the **Pythagorean theorem** is thought of as a mathematical formula while Euclid's way for finding the greatest common divisor of two positive integers is considered an algorithms.

The difference between algorithms and formulae lay at there purpose. A formula is expressing information about a specific relation that lays among some clearly defined quantities in the case of Pythagorean theorem (`a**2 + b**2 = c**2`) shows a fundamental relation that exists among the three sides of a right angled triangle. On the other hand an algorithm is describing computation, a computation that follows a certain set of tasks and finally produces an output. An algorithm is not used for description, and doesn't need a concise representation of the information that it contains. In the case of Euclid's Algorithm its purpose is computing the greatest common divisor of two integers `a` and `b` not describing a fundamental truth about the GCD of any two positive integers.When you apply a formula to get a particular result you are using the algorithm contained within the formula. A formula can be used as an algorithm to get a result but an algorithm can't by it self be considered a mathematical formula.

The other things that you must think of as separate are Mathematics and Computation.

Computation is following a well defined model of steps to arrive at a solution. Mathematics however, is the process by which how and why an algorithm works or doesn't work and prove it for all cases where it applies. Mathematics does this by finding provable truths from a set of assumed postulates (axioms) through logical reasoning. An example would conjecture you can't prove a conjecture by brute forcing through all the numbers because even you theorem works for the first billion numbers doesn't mean it is true for all numbers, to do that you need a formal structure for proof and that is math. Arithmetic operations (+, -, x, /) and number sorting algorithms are some examples of computation.

For much of human history we did not have formal models of computation. A formal model was needed because computations and algorithms were not all seen as a elements of a higher class, because addition was done by the addition machine, square roots were done using the square root machine and so on. What a formal model of computation does is allow any algorithm to be described in a finite number steps and give rules on how to follow those finite number of steps. This models of computation allow us to explores the computation landscape to know what we can compute and more importantly what we can't.

At the beginning of the 20th century three different models of computation were discovered within a year of time.

1. Alonzo Church: Lambda Calculus
2. Kurt Godel: Recursive Functions
3. Alan Turing: Turing Machine

At the dawn of the 20th century there was growing movement in Mathematics called formalism, David Hilbert was a proponent of this idea. What the formalists wanted was a system of proof that defines all of mathematics in other words they wanted an algorithm that could tell if a given a formal statement was true or false. (which consequently the job of any mathematician) this idea was called the decision problem (Entscheidungsproblem). The existence of this kind of algorithm statement has an assumption that mathematical logic is complete, consistent and decidable.

Complete means that every through statement has a proof except for the assumed axioms.
Consistent means that logic is free from contradiction, you can't simultaneously prove A is true and false.
Decidable means that there is an algorithm the given a formal statement show that the statement is true or false.

Formalists thought that all of the properties listed before are true.

Let's look at one of the first models of computation, The Turing Machine. A turing machine consists of a infinitely long tape, and head that can read and write to the tape on cell at a time. A basic turing machine will have three options of what can be written on cell 1, 0 or empty cell. Turing machine created a model of computation called a finite state machine. A finite state machine an abstract machine that can only be in one of a finite number of steps at time and can change from one state to another in response to some input. Action are perform when a transition from one state to another and are called transitions.

- turing machine example
- turing machine counting example
- finite state machine example
- finite state machines are at the core of every computer in modern world
- turing machines led to the von neuman architecture
- Although most mainstream programming languages use other logical primitives for creating programs all of them can be transpiled to a turing machine.

Alonzo Church's model of computation wa based on functions.
Cellular Automata are also models of computation.

Church-Turing Thesis or the principal of computational equivalence

# Approaches to Artificial Intelligences

- Top Down Approach: Humans approach where we reason about a problem to solve it. It is symbolic approach involving extracting knowledge and representing it in symbolic form, and develop a model to reason about it. also known as "Good Old-Fashioned Artificial Intelligence" (GOFAI)
- Bottom-up Approach: where we build model that replicates how brain works (huge interconnection of neurons) by building Neural Networks and train them with training data.
- Alternaitive Approaches
  - Evolutionary Approach: Algorithms based on evolutionary principles such as Genetic Algorithms
  - Emergent Complex system Approach: Build complex system with large number of simple agents that interacts with each other and environment with certain emergent behaviors.

## Rational and Human Behavior and Thinking

- making computers think
- the automation of activities we associate with human thiking, like decision making, learning
- art of creating machines that perform functions that require intelligence when performed by people
- study of mental faculties through the use of computational models.

|      |  Human | Rational|
|------|--------|---------|
|Though|Systems that think like humans|Systems that think rationally|
|Behaviour|Systems that act like humans | Systems that act rationally|

### Systems that act like humans: Turing Test Approach

- “The art of creating machines that perform functions that require intelligence when performed by people.” (Kurzweil)
- “The study of how to make computers do things at which, atthe moment, people are better.” (Rich and Knight)

Turing Test:

You enter a room which has a computer terminal. You
have a fixed period of time to type what you want into
the terminal, and study the replies. At the other end of
the line is either a human being or a computer system.

If it is a computer system, and at the end of the period
you cannot reliably determine whether it is a system or
a human, then the system is deemed to be intelligent.

a human questioner cannot tell if there is a computer or a human answering his question, via teletype
(remote communication).

The computer must behave intelligently to achieve human-level performance in all cognitive tasks such as

- Natural language processing for communication with human
- Knowledge representation to store information effectively & efficiently
- Automated reasoning to retrieve & answer questions using the stored information
- Machine learning to adapt to new circumstances
- Computer vision to perceive objects (seeing)
- Robotics to move objects (acting)

### Systems that think like humans: Cognitive Modeling (Science) Approach

Humans as observed from "inside"

- How do we know how humans think?
- Introspection vs. psychological experiments

- “The exciting new effort to make computers think ...
machines with minds in the full and literal sense”
(Haugeland)
- “[The automation of] activities that we associate with
human thinking, activities such as decision-making,
problem solving, learning ...” (Bellman)

### Systems that think "rationally": "laws of thought"

"Rationality" refers to the thought process that is based on reasoning from knowledge to logically arrive at a conclusion or decision. Rational thinking is about applying logic to find sound explanations.

However, Humans are not always "rational". Human are social and emotion being with many cognitive biases which can divert us from rationality and lead us to flawed decision making. [Sometimes the desire to novelty, survival and safety is also associated with our irrational behavior.](https://www.discovermagazine.com/mind/the-reasons-why-we-do-irrational-things). Hence Logic can't express everything, and hence the need to account for uncertainty.

- “The study of mental facilities through the use of
computational models” (Charniak and McDermott)
- “The study of the computations that make it possible to
perceive, reason, and act” (Winston)

### Systems that act rationally: “Rational agent”

Rational behavior: doing the right thing
The right thing: that which is expected to maximize goal
achievement, given the available information

- replicates human thought processes
- makes the same decisions as humans
- uses purely logical reasoning

Logic is only part of rational agent, not all of rationality. Sometimes logic cannot reason a correct conclusion. At that time, some specific (in domain) human knowledge or information is used.
Thus, it covers more generally different situations of
problems.

Studing AI as rational agent has few advantages

- It is more general than using logic only (Logic + Domain knowledge)
- It allows extention of the approach with more scientific methods

Rational Agents:
An agent is an entity that perceives and acts. Abstractly, an agent is a function from percept histories to actions: [f: P* --> A]

For any given class of environments and tasks, we seek the agent (or class of agents) with the best performance

- Caveat: computational limitations make perfect rationality unachievable. design best program for given machine resources


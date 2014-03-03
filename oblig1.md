# INF5390 oblig 1
mathiajj and martinvl

## Problem 1
a) __False__

Acting rationally means maximizing performance based on what the agent knows (or should know). If the agant is unable to achieve maximum performance due to insufficient information this is clearly not the case.

So even though the agent's performance might be limited by insufficient information, it might perfectly well be rational.

b) __True__

In a scenario where the agent should output either `true` or `false` every time it receives input. The agent scores points if it outputs `true` when it has received an even amount of inputs, and `false` otherwise. The goal is to score as many points as possible.

No pure reflex agent can act rational in this environment because it has to take into account the _state_ of the environment.

c) __True__

For instance environments with no room for choices to be made, or where all choices yield the same performance.

d) __False__

The input to the agent program is the set of perceptions. The agent program might for instance also contain an environment model, which it will include as input to the agent function.

e) __True__

Define for instance an environment where there are no perceptions and no known goal. Then a random agent acts perfectly rational.

f) __True__

If there is no information and no goal, then performance is by default optimized.

g) __False__

Assuming the agent starts with a finite amount of money there exists an environment such that the agent always gets the worst cards. If the agent plays itself in this environment, it will either lose all it's money on blinds or on lost hands.

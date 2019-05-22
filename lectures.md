# 1. Introduction, Values, Wellbeing; Subjectivism and Relativism


## What is ethics?
 - A discipline in philosophy called "moral philosophy"
 - Morality can be studied in different ways
  - **Descriptively**: Through the eyes of an observer (anthropologist, psychologist). How do people behave? What causes this behavior?
  - **Normatively**: How ought people to behave? What is the standard in society? How to justify their behavior?
  - **Meta-ethically**: What kind of statements are moral statements? It is more about the definition of ethics itself and the reasoning behind it.

### Examples of ethics
Self driving cars, Who is responsible. Who should be killed during an accident?  
Machine learning, inherently racist and discriminates people based on the input data.  
Scientific conduct, what is it and what if someone pushes you to cross certain boundaries?  

## Values

Values are things we think are important. E.g freedom, equality, beauty and love.

### (How) do these values relate?
**Monism**: the different values reduce to one
fundamental intrinsic value. E.g. happiness
or wellbeing; the other values are only
instrumental.

**Pluralism**: the different values are
irreducible; they are all intrinsic.

### The focus on wellbeing and happiness

To answer questions as *"how does social media affect people's lives?"* we need to have a concept of wellbeing/happiness

The theories of wellbeing/happiness:
- **Hedonism**: Wellbing is the sum of pleasure minus the pain
- **Preference satisfaction**: Wellbeing is the satisfaction of preferences
- **Objective list**: Wellbing is a set of items on an Objective list

#### Hedonism

- Hedonism: wellbeing = sum of pleasure – pain -> feeling,
psychological state
- Source of wellbeing is irrelevant

##### Objections

- Wellbeing does not always come down to an inner feeling. For example when you try to master something difficult
- The **experience machine** of Robert Nozick:
  - People want a real life
  - To be a person
  - to do things (instead of just experiencing)
- Wellbeing has distinct forms. You can't generalize wellbeing. wellbeing[be with friends] != wellbeing[write a book]
- The hedonistic threadmill. Being stimulated by the same provides less pleasure overtime. You need to find stronger stimuli all the time.
- The measurement problem: How do we measure one's hedonistic state?
- The comparison problem: How do we compare hedonistic states between people?

#### Preference satisfaction

 **Wellbeing = The satisfaction of personal preferences**. For example, I am happy if i go to church every sunday. When that preference is satisfied it boosts your wellbeing  

DO NOT interpret this as the satisfaction of certain requirements!

##### Criticism and discussion
- Uninformed preferences (E.g you take a medicine with unaware side effects)
- Adaptive preferences
  - Happy slaves
  - Tredmill, as for hedonism

A modification to the theory is possible. For example, only rational and informed preferences count

- Malevolent preferences. Should sadistic preferences count for someones wellbeing?
- Experience matters
- Are all types of preference satisfaction on equal footing?
 - Is the preference statisfaction of dancing equal to the one of collecting bottle caps?
- Measurement problem: How do we compare utility/wellbeing among people

#### Objective List

Basically, an objective list of basic needs:
- food
- shelter
- income
- social relations
- education
- culture
- clubs

Alternatives, Like a basic list of capabilities, things people can do:
- Imagination and thought
- Making use of senses
- Express emotions
- Practical reasoning

In general they are easy to use for policy makers, like the UN for example. Not interpersonal, thus no interpersonal measurement problem.

##### Objections
- Are the items on the list the correct items, do they represent wellbeing good enough?
- How to justify the items one the list?
 - By saying people want them? *That's preference satisfaction!*
- The items do not constitute to wellbeing, they are sources of wellbeing
- People have authority over their Wellbeing
- It isn't sensitive to differences between people

## Subjectivism

Moral statements are mere expressions of personal opinions or taste. They are no facts by any means. Also, they don't have truth values. So we can't reason about them in a general way as moral statements differ from person to person and between mood swings.

In Meta-Ethics, the theory that moral statements do not have truth values is called **non-cognitivism**

Early version: **Emotivism**

### Emotivism
 - Moral statements are solely expressions of emotions
 - Moral disagreement is a conflict of attitudes
 - Explains why some disagreements run deep, hard to reconcile
 - According to emotivists, morality motivates

#### Objections
1. Moral reasoning between people is an exchange of arguments, not attitudes. There is no logical structure behind moral reasoning from a emotivist perspective.
2. How to distinguish moral statements from other evaluative
statements, e.g. esthetic ones? In a non circular way?

## Relativism
- **Cultural relativism**: different cultures vary in systems of moral norms
- Does it follow there is no universal, culturally independent morality?
- No, not necessarily
  - Perhaps there actually is, but no culture has identified these norms yet
  - Or varying cultures and their systems of norms are rooted in a system of universal norms  

### Moral Relativism
  - Variant of cognitivism, moral statements have truth values
  - They are true or false according to a specific culture
#### Objections
-  Certain values are common to all cultures
- No objective standpoint to criticize the morality of a specific culture
- The idea of moral progress still possible?

### Normative Relativism
- "Each culture should have its own morality"
- "One should be tolerant of different cultures"

These are universal claims, they do not follow from moral relativism. A moral relativist can also say that one should NOT be tolerant.


# 2. Decision theory & Game theory

- Individual decision theory: studies decision making when actors
are confronted with various ‘states of nature’.
(sometimes ‘decion theory’ in a narrower sense)
- Game theory: studies decision making when actors interact with
each other.
-  Social choice theory: studies how to derive a collective decision
from individual preferences. (not addressed in this course)

## The (Rational) Actor
Mental states, two basic categories:

- Beliefs: mind-to-world direction of fit
  -  Mental content must mirror the world
- Desires: world-to-mind direction of fit
  -  World must mirror the mental content (You have to grab it in the world to get it)

We assume in game theory are rational, this isn't necessarily the case.

### Actors have
- desires
- beliefs
-  \+ rationality

Formalised in decision theory:
- preferences over outcomes
- assign probabilities to outcomes
- \+ these satisfy consistency requirements (axioms of the theory)


## Descriptive vs normative
We will approach it normatively, how should an agent behave if it is rational? We're not going to survey people or something.

**Concept of rationality**: Given the goals of a person, what to do next,
in a rational way?

## Formalize the decision problem

1. Acts/stategies
2. States (situations the world will be in)
3. Outcomes

Action: function(state) = outcome

## Individual decision making

### Example

|  |Recession | No recession|
|---|------|----|
|Dance academy | poor | exciting |
|Medicine |reasonably good |good|

### Decision making under ignorance
The actor knows about the different states of the world, but doesn't know the probabilities of each of them

 - Dominance
 - **Maximin**
 - Insufficient reason
 - etc.

#### maximin
Avoid the worst case outcome. And **maximize** the lowest possible value

### Decision making under risk
The actor **does** know about the probabilities of the states of the world.

**standard rule**: maximize expected utility = max. {prob . utility}

Can also be done with money or time, iff: **utility is a linear function in this factor**

#### Utility scales and axioms

##### Ordinal
The preferences must statisfy just 3 axioms
- asymemtry
- completeness
- transitivity

##### Interval utility function
The preferences must statisfy 5 axioms
- asymemtry
- completeness
- transitivity
- indepenence
- continuity

if intervals between 2 different items/objects are equal, then the intervals are comparable. Ordinal numbers cannot be used in calculations, they're just used for ranking as in higher or lower.

##### Von neumann & Morgenstern interval scale

Construct a scale by taking two extremes – say, a top item and
a lousy item – and compare the choice alternatives with
lotteries over these extremes.

**example**

firstly rank the alternatives:
1. Porsche
2. Volkswagen
3. Skoda

Now choose a top item & a lousy item to construct the scale,
e.g. Ferrari & Honda


Ask the actor what lottery over the Ferrari (F) and the Honda (H) would leave him/her
indifferent to a Porsche / Volkswagen / Skoda for certain.

A says:

| Car | Ferrari | Honda |
|-----|-----|------|
|Porsche   |  0,8 F | 0,2 H |  
|Volkswagen  | 0,5 F | 0,5 H |
|Skoda       | 0,2 F | 0,8 H |


Assume U(Ferrari) = 100, U(Honda) = 0, then

|||
--------|-------
U (Porsche) |       0,8.100 + 0,2.0 = 80  
U (Volkswagen) |    0,5.100 + 0,5.0 = 50  
U (Skoda) |         0,2.100 + 0,8.0 = 20

So when preferences over a set of alternatives of an actor satisfy:
- asymemtry
- completeness
- transitivity
- indepenence
- continuity

Then one can derive a cardinal (interval) VNM utility function: then one can assign interval numbers to the alternatives.

**Application VNM**

Policy makers in health care need a measure for the quality of health
states from the perspective of patients.

For example: *Quality Adjusted Life Year = life expectancy x quality*
remaining years

Practically they draw a line and put the ordinal scale of diseases on there. Downside: People tend to have biases. They tend to spread the diseases over the scale and to have extremes


## Game Theory

Analyses interaction-structure between **individuals** and
**solution concepts**

Different versions
- Sequential, first one actor chooses then the other
- Iteratively


### Iterative games

One shot PD leads to mutual defection and a collectively suboptimal
equililibrium.
Iterative Prisoners Delimma offers cooperative possibilities
(when indefinitively repeated, otherwise induction possible that will lead to dominant strategy)

### Tit for that-like strategies


1. Start with cooperation.
2.  In each next round mirror what the other player did in the previous round.

Axelrod (1984): Tit for Tat most successful strategy in computer tournament.

Also:

- Reputation plays a role
- Information can also come from third parties (indirect reciprocity)

Other variants:

- Defect
- Win, shift, lose stay (also in animal kingdom)
- 50% cooperate, 50% defect


### Stag Hunt
||Stag |Hare|
|--|--|--|
|**Stag** |3, 3| 0, 2|
|**Hare** |2, 0 |1, 1|

Stag: Higher pay-off, with risk  
Hare: lower pay-off, but guarenteed profit

Different strategies: Maximize pay-off vs risk-avoidance

Cooperation requires trust - Stag hunt game a.k.a. Assurance Game  
In evolutionary simulations with random pairing: hare hunters take over the population,
stag hunters go extinct.

### Nash equilibrium
A combination of strategies is a Nash Equilibrium (NE) if neither party
has a reason to unilaterally change its strategy.

Stag Hunt: [Stag, Stag] & [Hare, Hare] are both Nash Equilibria.

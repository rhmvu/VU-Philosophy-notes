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

Stag Hunt: *[Stag, Stag]* & *[Hare, Hare]* are both Nash Equilibria.

### Evolutionary game theory

Pay off isn't utility but it is the number of reproduction.

Agents follow fixed strategies. After each round there is reproduction, older generations die.

**Evolutionary stable strategy (ESS)**: population with species that follow this strategy cannot be invaded by another species that follow another strategy.

ESS is also a Nash Equalibrium. However, not every NE is an ESS






# 3. Consequentialism and Utilitarianism

## Normative ethical theories
1. Consequentialism, Utilitarianism *(Moral quality found in the consequences of the action)*
2. Deontology *(Moral quality found in the motive, the intention or the action itself)*
3. Social contract theory *(Moral quality depends on the interdependency of the consequences)*
4. Virtue ethics


## Consequentialism

 **Moral worth is in the consequences of an action.**

 - That is, the values that are realized in this action (e.g. freedom, wellbeing, knowledge)
 - An action is morally good if it has good consequences, given the possible actions.
 - This can be interpreted monistic or pluralistic


 ### Utilitarianism
 
 Subset of consequentialism
 - Monistic: only utility counts
 - Maximizes / promotes utility
 - What is utility or wellbeing?
   - Hedonism 
   - Preference statisfaction
   - Objective list

#### Procedure
1. Define the concept of utility/wellbeing
  - Hedonism / preference statisfaction / objective list
2. What are the possible alternative actions?
3. Determine for each alternative action its total expected utility
  - Expected utility = probability x utility
  - Total = Aggegrate of all those who are involved
4. The action with the max total utility = morally good action = one's obligation to perform.

#### characteristics

- Impartiality: no one is privileged. Anyone who can suffer belong to the moral community.
- Traditional moral rules are not absolute. Those rules can be interpreted as flexible, as long as we are happier ever after.
- Forward looking: consequences are ahead, in the future. The past is irrelevant. We punish someone so he could not  harm others in the future, not because he deserves punishment
- Insatiable: any further increase of utility is better, and morally required.



#### Case: Big data for growth and wellbeing

##### How can this data be used?

reduces the reliance on expensive large surveys. 

governments and companies can target the low mood / life satisfaction areas with specific policies.


##### Philsophical issues

-  Which concept of well-being? For which use?
-  How to interpret low correlation mood/sentiment measures with life satisfaction?
-  Target the low mood / life satisfaction areas with specific policies seems to
presuppose utilitarian calculus: justified?
-  Most data are retrieved without consent.
- Ability to measure some proxies well may (unwillingly) move other important things to the background.
- How to measure other important things?

##### General criticism and discussion

1. Is utility all that matters? Aren't there other intrensic values? Friendship e.g.?
2. Rules like "thou shalt not steal" are inflexible. They concern fundamental rights that cannot be traded against considerations of utility
3. Heavy information processing: for each situation calculate expected utility
4. Integrity (and seperateness) of persons: Individuals are more than carriers of utility. It is possible that ones good is traded for the good of a larger group of people.
5. Backward looking reasons are important. e.g. one deserves punishment for what one has done. Punish to punish and to scare people: don't do these things.
6. Special relations are important: We like to prioritize people around us like family and friends. For a utilitarian this isn't possible because everyone is inherently equal.

##### Responses utilitarianism

- Bite the bullet: Most criticism is an irrational product of our evolutionary and cultural past.
- Modifications: Rule-utilitarianism

##### Rule utilitarianism

- Problem for rule utilitarianism: rule fetishism: must a rule always be followed? no matter the circumstances? Even if it is obvious that it does not yield max utility?
- What to do in an actual situation is derived from a hypothetical situation?
  - e.g. Can't steal medicine because of a rule... One dies in civil war because of a hypothetical rule
- Does it provide the appropriate moral justification?
  - I just saved you instead of 2 others because of a rule utilitarian rule...





# 4. Deontology and Social Contract Theory

## Trolly problem
  Consequentialist: Save the lives of the 5 and kill 1


## Deontology

  Founding father: Immanuel Kant
  
  "Duty ethics"
  
  Kant: *"moral worth is not to be found in the consequences of an action."*  
  E.g. lying or stealing is not bad because of the consequences that these actions may happen to have, but because they are bad actions, period.

  If you act solely because of duty and out of obligation it is a moral action, not if you do something for self gain or out of friendship.

  Doing the right thing looks pretty formal now.   
  Principle udnerlying the right intention = lawlike, like a natural law.  
  Only this law is a law that humans impose on ourselves.


  ### Differences between humans and animals

  Kant: the rational nature of human creatures

  Animals are driven by inclinations and impulses -> subject to natural laws

  But humans can also impose laws on themselves, and follow them.

### Kant and Newton
- Newton: Everything in the universe is subject to natural laws  
- Kant: morality has universal scope and necessity, just like Newton's laws.  
  - Only: humans impose the laws on themselves.

### Categorical Imperative (1)

Universal law formulation

*Act only according to that maxim by which you can at the same time
will that it should become a universal law*

AKA "What if everybody behaved like that?"

Categorical: not contingent on one’s own desires (such imperatives
Kant calls ‘hypothetical’) and not on the circumstances. It can't be dependent on the specific context.

Kant’s idea: moral reasons are universally binding, irrespective of
time, place, person.

#### Example: lying, breaking a promise

Can this be action guiding for you and can you at the same time want that everybody acts like this?

Would be self defeating...

### Categorical imperative (2)

Humanity formulation

*Act so that you treat humanity, whether in your own person or that in
of another, always as an end and never as a means.*

AKA: "You must treat people in the same way as yourself, as autonomous beings who set their own goals.", don't use people solely as an instrument to reach your own goals. So no slaves or supression.

Humans are fundamentally unlike commodities: they do not have a
price. They have dignity, which is the central value for kantians.  

This formulation also prohibits lying, breaking promises / contracts.
Because then you treat another person only as an instrument for your
own purposes.

### How are (1) and (2) related?

Kant argued that various versions of the categorical imperative are equivalent.

One argument: a rational creature must respect this distinguishing feature of himself, must respect his rational nature.

### Criticism and discussion

1. Absoluteness of moral rules. Aren't some lies sometimes permitted, e.g to diver a murderer? If Nazi's come and you have Jews hidden, you must tell the truth because of the universal rule that one should not Lie. The intention is good in general, but this outcome isn't good....
2. Wellbeing/happiness does not have a moral status.
  - Response: striving towards wellbeing is allowed, as long as it is not disallowed by the categorical imperative.
3. Creatures who are less rational (children, animals, impaired) are not part of the moral community.
4. What if rules conflict?


Deontology: autonomy -> side constraint on -> individual rights

Kantian ethics: philosophical foundation of universal human rights

## Practical examples

### Machine learning

Useful to predict human behavior; prevent terrorist attacks; hire the best workers; diagnose illnesses etc.

However, amplifies biases against minorities.

Values to be protected or promoted: human lives, well-being, privacy

How to weigh these?
- Utilitarians: tradeoffs (if high enough benefit fuck privacy for example)
- Kantian: Constraints (Human rights, privacy rights, certain personal boundaries may not be crossed for example)

### Self driving cars

- What if a fatal accident happens because the car makes a mistake? Who is then responsible? The car owner, the manufacturer, the designer?

- Possibly a “Problem of Many Hands” (lecture 5)

### Lessons from trolleyology?

- What if an accident happens, and the only options are: steer to the left and kill a pedestrian or steer to the right and crash, thereby killing the two passengers?

- Consequentialist and deontologist engineers will come up with different design specifications

### May we hack a car?

- With terrorists in it? -> lock the doors, slow the car down, stop it / drive it to the police station
- For the benefit of us all, however, it is a violation of autonomy according to others
- What if this capacity falls into bad hands? Utilitarians will may not allow this because of this reason.

### Self organize in platoons

By means of communications between cars

- Reduces emissions and traffic jams
- Loss of autonomy for the "driver"

## Social Contract Theory

Morality is social -> moral reasons of people are interdependent

Morality= system of mutual expectations and preferences by which people can solve cooperation problems. as in n-person Prisoner's Dilemma problems

most notably: provision of collective goods in society

### Collective goods

- Goods that can only be produced by cooperation
- Once produced, everyone can benefit
- Vulnerable to free riding
- Examples: infrastructure, national defense, health care, dykes
- Martin Tisne argues that data should be conceptualized as a collective good, and data ownership is a wrong idea.

In a Prisoners Dilemma - e.g in material outcomes:
 
- Individual rational to defect: Don't pay and still recieve
- While Mutual cooperations among society is Paretor Superior.
- All players have interest to get in mutual cooperation.
- Problem: Mutual cooperation is not stable, not an equilibruim.
- At the same time, players would have a collective reason to Cooperate.
- Dervive from all this: *individual reason* to cooperate = moral reason

Concludingly:

- Social contract theorists: **Individual moral reason to cooperate is dependent on the expectation that others also cooperate.**
- Kantists: Always cooperate, even if they expect others too exploit them


### Thomas Hobbes

founding father social contract theory

His central question during Englands civil war: people must reach a mutual agreement to stop / avoid war of all against all. What set of rules and how to ensure that they are followed?

War against all = state of nature = D,D

### Central question in general

- people must reach a mutual agreement to avoid suboptimal outcomes. What set of rules and how to ensure they are followed?
- As multiple Nash Equilibriums exist: multiple solutions are possible
- Law is a system of rules that reduce the various Nash equilibria
  
Martin Tisne:

- Unrestricted use of data by everybody, would be bad for everybody
  - Restricted use by everybody = cooperative outcome
- Necessary: bill of data rights

#### Tisne's proposal - bill of data rights

- The right of the people to be secure against unreasonable surveillance shall not be violated
 - No person shall have his or her behavior surreptitiously manipulated
 - No person shall be unfairly discriminated against the basis of data
  
  PD situtations often have a repeated nature. In which case even egoistic people would cooperate. Why do we need social contract theory then??

  well, still:
  - often enough one shot (jackpot) situations
  - often enough imperfect monitoring, registering, memorizing
  - Moral motivation to cooperate enhances cooperation

### Criticism and discussion

  - Social contract is not real. We never sat down and signed a real contract right?
    - Response: understand the social contract as hypotethical, see it as a convention.
  - People / creatures who do not participate in cooperative project can also have moral status: future generations, cognitively impaired or animals.
    - Response: other part of morality 

### Hobbesian social contract theory

- Derive moral rules from rational self interest (people are rational egoists)
- Since cooperation problems are often negotiable and negatiations are sensitive to starting positions in real life:
  - Wealth, goods, skills, everything you can bring to the bargaining table

- Moral rules must therefore be **sensitive to various starting positions**

### Non-Hobbesian: Hume, Rousseau

- Morality is combination of utilitarian or Kantian motives & interdependency, not perse self-interest

John Rawls: modern Kantian social contract theorist
- *The resources and talents you bring to the bargaining table should not make a difference. They are morally arbitrary: should not play a role in designining just society.* 
- *Therefore hypothesize contract situations as if everybody reasons behind a veil of ignorance: you don't have information about your resources.*

Decision making under ignorance: Rawls: maximin

Rawl's two principles of justice
1. **Principle of Equal Liberty**: Each person has an equal right to the most extensive liberties compatible with similar liberties for all. 
2. **Difference Principle**: Social and economic inequalities should be arranged so they are both (a) to the greatest benefit of the least advantaged persons, and (b) attached to offices and positions open to all under conditions of equality of oppurtunity.

Basically how modern social democracies work.


### Once more, self driving cars

The social dillema of autonomous vehicles
- Most people express moral preference for utilitarian AV's, that minimize casualties
- Also preference for self protection vehicle for themselves
- Prisoner's Dilemma: reason for government regulation
- However, most people do not want the government to regulate this....


# 5. Applications: Cost Benefit Analysis, Many Hands Problem

## Social cost benefit analysis

- Government must compare policy alternatives, e.g build a bridge or dig a tunnel
- Compare in terms of future advantages and disadvantages
- Use a metric to compare, most often money
- Monitize all benefits and costs 
- Recalculate to the same year (with interest rate)

### Benefits and costs that do not have a market price

- Casualties, wounded
- CO2 emissions
- Noise

- Different methods!
  - What are the costs if we reduce it? (How much would you pay each month for a forest?)
  - Willingness to pay
  - Willingness to accept

### CBA of CBA....

Pro's
- Rationalizes public decision making
- Less subjective
- Forces one to include alll relevant considerations
- Provides common ground

Con's
- Never complete
- Some estimates are very uncertain


### Determination: 130 km/h speedlimit increase

|Benefit|Costs|
|----|-----|
|Travel time: average salary x time| Fuel costs
|| Emissions: Plant trees
|| Nature
|| Deaths: 2 million per person
|| Wounded: hospital costs
|| Noise: costs of building noise barrier


#### Weighing 

#### The Actual 2011 report


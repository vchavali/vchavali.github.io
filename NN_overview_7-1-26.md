---
author: Pramod Chavali
title: Fundemental Abstractions and Formulisms of Navyanyāya
layout: default
---

# Fundemental Abstractions and Formulisms of Navyanyāya

## Preamble

Take a look at the following the following rendition of Euclid’s proof of the infinitude of primes (adapted from Ore (1948), *Number Theory and its History*, p. 65):

<div>
Let <span class="frm">S</span> be any finite set of prime numbers and <span class="frm">P</span> be the product <span class="frm">Π<sub>s∈S</sub>(s)</span>. Then either <span class="frm">P+1</span> is prime or it is not. If <span class="frm">P+1</span> is prime, then there exists a prime number not in <span class="frm">S</span>. If <span class="frm">P+1</span> is not prime, then it must be divisible by some prime number <span class="frm">q</span>. However, if 
<span class="frm">q∈S</span> then it would also divide <span class="frm">P</span>. Therefore it would divide the difference <span class="frm">(P+1)-P</span>. But only <span class="frm">1</span> divides this difference. Therefore <span class="frm">q∉S</span>. Therefore, for any finite set of prime numbers there exists at least one prime number not in that set.
</div>
{: .quote .example}

Here, we can see that an argument is being offered in mostly natural language. However, certain formula written in a symbolic language are interspersed freely into the natural langauge argument. This is typical of the mathematical style of argumentation. We do not see proofs written entirely in a symbolic logic, where the validity of the whole proof can be decided entirely on formal grounds. Rather, formulisms service natural language arguments, making them more rigorous, easier to analyze and evaluate. We can preform algebraic manipulations on symbolic expressions and such manipulations can be evaluated on purely procedural grounds. But evaluating the argument as a whole still requires considering the semantics attached to the formalisms. 

This is prerightely the way in which formulisms work within Navyanyāya texts. Consider the following leftlation of a paragraph from Kurigaṇṭi Śrī Rāmaśāstri’s *Tarkasangrahasarvasvam*. Don’t worry so much about understanding what its saying. We’ll go through it again more slowly after we’ve introduced all the machinery. For now, just observe the form of the language being used:

<div>
Nor is it the case that the definition fails to cover such examples as of, e.g., a pot that is destroyed immediately after it is created. It is true that <span class="frm">Inherence⌉⟨Odor⟩⌉(Odor⸥ ⟨⸣⟩)›⟨⸥⟩</span> would not obtain for such a pot because, following the principle that a newly created substance exists for an instant without qualities or actions, its qualities would not yet come into being in the instant of its creation. And the pot would have no qualities in the following instant since it would have already been destroyed. Nor can this principle be simply rejected since if you affirm the existence of a substance’s qualities in the instant of its creation then the substance would fail to be a cause of its qualities. 
<br><br>
However, we take the definition to be <span class="frm">⟨[Inherence⌉⟨Odor⟩⌉⟨⸣⟩›⟨⸥⟩⸥⸣ Type]⸥⟩</span>. And even though a pot created and then destroyed is never the inherence substrate of odor; there is a type ‘Earth’ occurring in substances like flowers, etc., satisfying such a condition which does occur even in a created and immediately destroyed pot. Therefore, the definition does not fail to cover this case.
</div>
{: .quote .example}

This is very similar to the use of formalisms in mathematics. We again find an argument presented in mostly natural language. But formula in a symbolic language are interspersed and help support the natural language argument. 

In the original Nyāya text, the formulisms are not rendered using the graphical symbols I used in my leftlation. But they are still symbolic. Instead of graphical symbols, Naiyyāyikas use words and syntactic structures from natural Sanskrit in peculiar and *unnatural* ways, operating under special rules of their own, to express the sorts of formulisms that we would use symbols for in, e.g., modern mathematical texts. These structures are still symbols, but they are oral rather than graphical. Orality is deeply prized in the tradition, and is a powerful feature of the original langauge formalisms in their own right. 

Nonetheless, when leftlating Navya texts into English, I will render the formulisms using graphical notation. The difference is primarily a matter of length. However, the use of natural Sanskrit grammatical structures with its elaborate phonotactics and morphological constraints does introduce certain surface level ambiguities to Navya expressions which we can disambiguate with graphical symbols. We will discuss these as they come up. But the core idea remains intact. And, importantly, we preserve a 1:1 correspondance between the original Nyāya formula and the graphical notation.

With this preamble out of the way, let's divide into the machinery itself.

## Foundational Abstractions

### Objects

The Navyanyāya universe consists of a variety of different kinds of objects. The seven-fold category scheme of ancient Vaiśēṣika—substances, qualities, actions, types, identities, inherence, and abscences—gets expanded by latter authors like Raghunātha Śirōmaṇi to include all sorts of new entities like sets and the ‘power’ and ‘ownership’ relations. Nonetheless, at the highest level of abstraction, all objects can be divided into just two groups: locatable and nonlocatable objects. 

Locatable objects—also called *properties*—are connected to some other objects—called their *locations*—via ‘occurrence’ relations. A property might occur in many objects. It might occur in just two objects. Or it might occur in just one object. Cannonically, Nyāya asserts that there are no null properties. Every property must occur in at least one object. However, there is a minority position that does accept the possibility of null properties. For the sake of simplicity, we will not exclude null properties in our discussion here. But its worth keeping in mind that this is a minority position.

Properties can be further divided into two categories: analyzable and unanalyzable. And the unanalyzable properties can themselves be divided into two kinds: natural and artificial. Natural properties are also called *types*.

### Relations

Relations are a kind of property that only occur in two locations. In general, relations are not symmetric and the locations are not equivalent. For a given relation, we can distinguish between a ‘right’ location and a ‘left’ location. For every relation there is a pair of properties called, respectively, that relation’s right and left relational abstraction. The right abstraction occurs just in that relation’s right location. And the left abstraction occurs in just its left location.

Here’s an example. 

Fire generates smoke. If `s` is an instance of smoke and `f` is an instance of smoke. Then the relation `fGs` is a property with `s` as its right-location and `f` as its left location. The property <span class="frm">G<sub>s</sub></span> is its right-relational abstraction, occurring in `s`. And the property <span class="frm">G<sub>f</sub></span> is its left relational abstraction, occurring in `f`.

### Determiners

Relational abstractions represent a special case of a more general concept called ‘dependent properties’. A pair of properties `P` and `Q` are dependent on each other if the occurrence of `P` in some location `l` implies the existence of another location `m` such that `Q` occurs in `m`. In such a case, we say that `P` occurring in `l` *determines* `Q` occuring in `m`. And we call `P` the determiner of `Q`, and `Q` its *determinant*. Note that the determiner-determinant relation is symmetric. So, it is equally correct to say that `Q` is the determiner of `P` and that `P` is the determinant of `Q`.

The word ‘determiner’ permits a small but occasionally confusing ambiguity. Since it is in fact `P` *occurring* in `l` that determines `Q` *occuring* in `m`, we could say that `l` determines `Q` just as readily as saying that `P` determines it. So, we often see the word ‘determiner’ used to refer to the location of the determining property rather than the property itself. Usually what is meant is clear from context, but sometimes it is a source of confusion. So, we should keep this ambiguity in the terminology in mind when reading Nyāya texts. 

Here, we will represent the expression ‘property `Q` determined by property `P`’ with the notation:

<div>
P›Q 
</div>
{: .example .quote}
And we will represent the expression ‘property `Q` determined by location `l`’ with the notation 

<div>
l»Q
</div>
{: .example .quote}

### Limiters

Let’s go back to the example of fire generating smoke. There, we looked at a generator-generated relation `fGs` between a particular instance of fire `f` and a particular instance of smoke `s`. We then defined two relational abstractions <span class="frm">G<sub>f</sub></span> and <span class="frm">G<sub>s</sub></span> occurring in each location. But there is `G` relation between each instance of fire and smoke. And there are right and left abstractions for each of these relations. And, in fact, this extends beyond fire and smoke. For any two objects such that one generators the other, there is a seperate <span class="frm">G<sub>x</sub></span> relation between then, and correlate right and left abstractions for each. 

We can define a generic relation `G` as a property that occurs in any location of any <span class="frm">G<sub>x</sub></span> location. Then, each individual <span class="frm">G<sub>x</sub></span> relation is called a *limit* of the generic relation `G`. And we can make a similar move for each of relational abstraction of `G`. Let’s define `E` (for ‘effect’) to be a property that occurs in any location where some right `G` abstraction occurs. Then each individual right abstraction is a *limit* of `E`. Similarly, each individual left `G` abstraction can be considered a limit of some property `C` (for cause).

Now, let us suppose there exists a property `S` which occurs in all instances of smoke. Then, we can gather together just those `G` right abstractions that occur in locations of `S` by *limiting* `E` by `S`. We will represent this with the notation:

<div>
S⌉E
</div>
{: .quote .example}

read as ‘`S`-limited `E`’. Here, `S` is called the limiter of `E`. The property `S⌉E` is the limit of `E` that occurs in exactly the same locations as its limiter `S`. So, the limitation operator selects a particular limit of a property by specifying a limiter that coincides with that limit.

Limiters and determiners have an important relationship with each other. Recall that where two properties `P` and `Q` determine one another, `P` occurring at some location `l` implies the existence of some other location `m` such tha `Q` occurs in `m`. Similarly, where `P` and `Q` determine each other, the existence of a limiter `L` of `P` implies the occurrence of a limiter `M` of `Q` such that `L⌉P` determines `M⌉Q`. In this case, we can write:

<div>
(L⌉P)›Q
</div>
{: .example .quote}

The symbol `Q` embedded in the expression `(L⌉P)›Q` refers to that limit of `Q` which is determined by `L⌉P`. Like the limitation operator, what the determination operater does is select for a specific limit of a property. More generally, where the property `Q` is  determined by another property `P` and `R` is a limit of `P`; the term `Q` embedded in the expression 

<div>
R›Q
</div>
{: .quote .example}

refers specifically to that limit of `Q` which is determined by `R`.

Also, we will take the limitation operator to have precedence over the determination operator, so the expression `(L⌉P)›Q` can be rewritten without parentheses as:

<div>
L⌉P›Q
</div>
{: .example .quote}

A similar notation exists for the location-determination operator `»`. Where the limit `L` of `P` occurs in some location `l`, and `P` determines `Q`, the expression

<div>
l»Q
</div>
{: .example .quote}

Selects for the limit of `Q` that occurs in `l` and only in `l`.


**A Full Example**

Let’s put this all together with the example of fire and smoke. There is a generator relation `G` between each instance of fire and each instance of smoke with a generic right abstraction `E` occurring in the smoke and a generic left abstraction `C` occuring in the fire. Let `F` be a property occurring in all and only instances of  fire and `S` be a property similarly occuring in instances of smoke. Then the property:

<div>
F⌉C›E
</div>
{: .quote .example}

selects for that limit of `E` which is limited by `S`. In other words, it is equivalent to the expression:

<div>
S⌉E
</div>
{: .quote .example}

And, conversely:

<div>
S⌉E›C
</div>
{: .quote .example}

is equivalent to:

<div>
F⌉C
</div>
{: .quote .example}

### Negations

Negations are objects similar to relations. A negation is also a kind of property that occurs in two locations: one right and one left. Though, when talking about negations, we often refer to just the right location as its ‘location’ proper. We call the left location its *argument* and the left relational abstraction its *argumenthood*. Another way of phrasing this is to say that by ‘negation’ we really mean the right abstraction of a certain two-location property whose left abstraction is the argumenthood determining that negation.

Negations can be divided into two classes: temporal and nontemporal. The temporal negations are themselves of two kinds: called ‘past negation’ and ‘future negation’. The nontemporal negations are also of two kinds: ‘total negation’ and ‘difference’. Though, in general, when we just say ‘negation’ we mean total negation.

A total negation represents a negative fact. It represents something not being true of something else or of some object not existing somewhere. 

Here is an example.

Let us define the property `Red` as representing the fact that something is red. And let us suppose that `Apple` refers to some object—an apple, say. Then we can represent the assertion that `Apple` is red with the notation:

<div>
Apple ⊢ Red
</div>
{: .quote .example}



There is one important difference between negations and typical ‘positive’ relations, however. Think back to the generator relation between fire and smoke:

<div>
F⌉C›E
</div>

Here, the determined `F⌉C›E` abstraction is a limit of the generic abstraction `E`. 

Now, consider a negation `N` between some 

## The Formulisms

### Symbols

A Navyanyāya formula is a string of symbols. These symbols can be divided into two categories: evaluable and nonevaluable symbols. Nonevaluable symbols serve a merely syntactic purpose. For instance, whitespace and punctuation which serve to identify boundaries between symbols, disambiguate expressions, and specify the scope of variables.

Evaluatable symbols can be assigned a value. We will talk about the sorts of objects that symbols can evaluate to in the section on the abstractions. But for now we will just think of the value as a property

### Statements and Expressions

Navya formula can be broadly divided into two categories: expressions and statements. An expression, let us call it `Ψ(s)`, is a string of symbols containing one ‘head’ `s` and some number or subordinates.

The symbols that make up an expression can themselves be divided into two kinds: evaluable and nonevaluable symbols. An evaluable symbol can be assigned a value. Expressions do not themselves evaluate to anything. However, we can nominally consider the value of the head symbol as the “value” of the expression. We will talk about the sorts of objects that symbols can evaluate to in the section on the abstractions. 

A statement is composed of two or more expressions. A statement comprising just two expressions is called a simple statement. A statement containing more than two expressions is a compound statement. Statements—and *only* statements—can be assigned a truth value. The truth value of a statement is assigned on the basis of a relation between the values of the expressions (really the values of the expression heads) that make it up. Statements can also be divided into two categories based on how its truth value is assigned: assertions and definitions.

Given two expressions `Ψ(a)` and `Φ(b)`, we will write a simple assertion by placing a right turnstile between them:
    
<div>
	Ψ(a) ⊦ Φ(b)
</div>
{: .quote .example}

A compound assertion is just multiple simple assertions joined together with a comma:

<div>
	ψ<sub>1</sub>(a) ⊦ φ<sub>1</sub>(b), Ψ<sub>2</sub>(a) ⊦ Φ<sub>2</sub>(b), ...
</div>
{: .quote .example}

A simple assertion `Ψ(a) ⊦ Φ(b)` is true if and only if there exists some object `O` such that `a` and `b` can both evaluate to `O`. In other words, the assertion `Ψ(a) ⊦ Φ(b)` asserts that there exists a 

## Some Laws Relating to the Fundamental Abstractions

## Some Special Abstractions

### Logic

#### Predication

#### Negation

#### Conjuction

#### Disjunction

#### Existence

#### Universality

#### Tense

### Language

#### Words in General

#### Some special words

##### Names

##### Indexicals

##### Quantifiers

#### Sentences

## Leftlation of the Definition of Pr̥thvī from the Tarkasangrahasarvasvam

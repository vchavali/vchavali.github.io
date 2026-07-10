---
author: Pramod Chavali
title: Fundamental Abstractions and Formulisms of Navyanyāya
layout: default
---

# Fundamental Abstractions and Formulisms of Navyanyāya

## Preamble

Take a look at the following the following rendition of Euclid’s proof of the infinitude of primes (adapted from Ore (1948), *Number Theory and its History*, p. 65):

<div>
Let <span class="frm">S</span> be any finite set of prime numbers and <span class="frm">P</span> be the product <span class="frm">Π<sub>s∈S</sub>(s)</span>. Then either <span class="frm">P+1</span> is prime or it is not. If <span class="frm">P+1</span> is prime, then there exists a prime number not in <span class="frm">S</span>. If <span class="frm">P+1</span> is not prime, then it must be divisible by some prime number <span class="frm">q</span>. However, if 
<span class="frm">q∈S</span> then it would also divide <span class="frm">P</span>. Therefore it would divide the difference <span class="frm">(P+1)-P</span>. But only <span class="frm">1</span> divides this difference. Therefore <span class="frm">q∉S</span>. Therefore, for any finite set of prime numbers there exists at least one prime number not in that set.
</div>
{: .quote}

Here, we can see that an argument is being offered in mostly natural language. However, certain formula written in a symbolic language are interspersed freely into the natural langauge argument. This is typical of the mathematical style of argumentation. We do not see proofs written entirely in a symbolic logic, where the validity of the whole proof can be decided entirely on formal grounds. Rather, formulisms service natural language arguments, making them more rigorous, easier to analyze and evaluate. We can preform algebraic manipulations on symbolic expressions and such manipulations can be evaluated on purely procedural grounds. But evaluating the argument as a whole still requires considering the semantics attached to the formalisms. 

This is precisely the way in which formulisms work within Navyanyāya texts. Consider the following translation of a paragraph from Kurigaṇṭi Śrī Rāmaśāstri’s *Tarkasangrahasarvasvam*. Don’t worry so much about understanding what its saying. We’ll go through it again more slowly after we’ve introduced all the machinery. For now, just observe the form of the language being used:

<div>
Nor is it the case that the definition fails to cover such examples as of, e.g., a pot that is destroyed immediately after it is created. It is true that <span class="frm">Inherence⌉⟨Odor⟩⌉(Odor⸥ ⟨⸣⟩)›⟨⸥⟩</span> would not obtain for such a pot because, following the principle that a newly created substance exists for an instant without qualities or actions, its qualities would not yet come into being in the instant of its creation. And the pot would have no qualities in the following instant since it would have already been destroyed. Nor can this principle be simply rejected since if you affirm the existence of a substance’s qualities in the instant of its creation then the substance would fail to be a cause of its qualities. 
<br><br>
However, we take the definition to be <span class="frm">⟨[Inherence⌉⟨Odor⟩⌉⟨⸣⟩›⟨⸥⟩⸥⸣ Type]⸥⟩</span>. And even though a pot created and then destroyed is never the inherence substrate of odor; there is a type ‘Earth’ occurring in substances like flowers, etc., which do satisfy this condition. And this type occurs even in a created and immediately destroyed pot. Therefore, the definition does not fail to cover this case.
</div>
{: .quote}

This is very similar to the use of formalisms in mathematics. We again find an argument presented in mostly natural language. But formula in a symbolic language are interspersed and help support the natural language argument. 

In the original Nyāya text, the formulisms are not rendered using the graphical symbols I used in my translation. But they are still symbolic. Instead of graphical symbols, Naiyyāyikas use words and syntactic structures from natural Sanskrit in peculiar and *unnatural* ways, operating under special rules of their own, to express the sorts of formulisms that we would use symbols for in, e.g., modern mathematical texts. These structures are still symbols, but they are oral rather than graphical. Orality is deeply prized in the tradition and is a powerful feature of the original langauge formalisms in their own right. 

Nonetheless, when translating Navya texts into English, I will render the formulisms using graphical notation. The difference is in part a matter of length. Additionally, the use of natural Sanskrit grammatical structures with their elaborate phonotactics and morphological constraints introduces certain surface level ambiguities to Navya expressions which we can disambiguate with graphical symbols. We will discuss these as they come up. But the core idea remains intact. And, importantly, we preserve a 1:1 correspondance between the original Nyāya formula and the graphical notation.

With this preamble out of the way, let's divide into the machinery itself.

## The Abstractions

### Objects

The Navyanyāya universe consists of a variety of different kinds of objects. The seven-fold category scheme of ancient Vaiśēṣika—substances, qualities, actions, types, identities, inherence, and absences—gets expanded by latter authors like Raghunātha Śirōmaṇi to include all sorts of new entities like sets and the ‘power’ and ‘ownership’ relations. Nonetheless, at the highest level of abstraction, all objects can be divided into just two groups: locatable and nonlocatable objects. 

Locatable objects, also called *properties*, are connected to some other objects, called their *locations*, via ‘occurrence’ relations. A property might occur in many objects. It might occur in just two objects. Or it might occur in just one object. Cannonically, Nyāya asserts that there are no null properties—properties with zero locations. Every property must occur in at least one object. However, there is a minority position that does accept the possibility of null properties. For the sake of simplicity, we will not exclude null properties in our discussion here. But its worth keeping in mind that this is a minority position.

Properties can be further divided into two categories: analyzable and unanalyzable. And the unanalyzable properties can themselves be divided into two kinds: natural and artificial. Natural properties are also called *types*.

### Relations

Relations are a kind of property that only occur in two locations. In general, relations are not symmetric and the locations are not interchangeable. For a given relation, we can distinguish between a ‘right’ location and a ‘left’ location. For every relation there is a pair of properties called, respectively, that relation’s right and left relational abstraction. The right abstraction occurs just in that relation’s right location. And the left abstraction occurs in just its left location.

Here’s an example. 

Fire generates smoke. If `s` is an instance of smoke and `f` is an instance of fire, then there is a relation `fGs` which is a property with `s` as its right location and `f` as its left location. There is also a property <span class="frm">G<sub>s</sub></span> which is its right relational abstraction, occurring in `s`. And there is a property <span class="frm">G<sub>f</sub></span> which is its left relational abstraction, occurring in `f`.

### Determinants

Relational abstractions represent a special case of a more general concept called ‘dependent properties’. A pair of properties `P` and `Q` are dependent on each other if the occurrence of `P` in some location `l` implies the existence of another location `m` such that `Q` occurs in `m`. In such a case, we say that `P` occurring in `l` determines `Q` occuring in `m`. And we call `P` the determinant of `Q`, and `Q` its dependent. Note that the determinant-dependent relation is symmetric. So, it is equally correct to say that `Q` is the determinant of `P` and that `P` is the dependent of `Q`.

The word ‘determinant’ permits a small but occasionally confusing ambiguity. Since it is in fact `P` *occurring* in `l` that determines `Q` *occuring* in `m`, we could say that `l` determines `Q` just as readily as saying that `P` determines it. So, we often see the word ‘determinant’ used to refer to the location of the determining property rather than the property itself. Usually what is meant is clear from context, but sometimes it is a source of confusion. So, we should keep this ambiguity in the terminology in mind when reading Nyāya texts. 

Here, we will represent the expression ‘property `Q` determined by property `P`’ with the notation:

<div>
P›Q 
</div>
{: .example}
read as ‘P determined Q’.

And we will represent the expression ‘property `Q` determined by location `l`’ with the notation 

<div>
l»Q
</div>
{: .example .quote}
read as ‘l determined Q’.

### Limiters

Let’s go back to the example of fire generating smoke. There, we looked at a generator-generated relation `fGs` between a particular instance of fire `f` and a particular instance of smoke `s`. We then defined two relational abstractions <span class="frm">G<sub>f</sub></span> and <span class="frm">G<sub>s</sub></span> occurring in each location. But there is a generator relation between each instance of fire and smoke. And there are right and left abstractions for each of these relations. And, in fact, this extends beyond fire and smoke to any two objects where one generates another. 

Now, suppose there exists a property `E` (for effect) which occurs in each location of a right abstraction of some generator relation. Then each of these individual right abstractions is called a *limit* of `E`. We then call `E` the generic right abstraction of the generator relation. Similarly, each individual left abstraction of a generator relation can be considered a limit of a generic left abstraction `C` (for cause).

Let us suppose, further, that there exists a property `S` which occurs in all instances of smoke. Then we can gather together just those limits of `E` that occur in locations of `S` by *limiting* `E` by `S`. We will represent this with the notation:

<div>
S⌉E
</div>
{:.example}

read as ‘`S` limited `E`’. Here, `S` is called the limiter of `E`. The property `S⌉E` is the limit of `E` that occurs in exactly the same locations as its limiter `S`. So, the limitation operator selects a particular limit of a property by specifying a limiter that coincides with that limit.

Limiters and determinants have an important relationship with each other. Recall that where two properties `P` and `Q` determine one another, `P` occurring at some location `l` implies the existence of some other location `m` such tha `Q` occurs in `m`. Similarly, where `P` and `Q` determine each other, the existence of a limiter `L` of `P` implies the occurrence of a limiter `M` of `Q` such that `L⌉P` determines `M⌉Q`. In this case, we can write:

<div>
(L⌉P)›Q
</div>
{: .example .quote}

read as ‘l limited P determined Q’

The symbol `Q` embedded in the expression `(L⌉P)›Q` refers to that limit of `Q` which is determined by `L⌉P`. Like the limitation operator, the determination operater selects for a specific limit of a property. More generally, where the property `Q` is  determined by another property `P` and `R` is a limit of `P`; the term `Q` embedded in the expression 

<div>
R›Q
</div>
{: .example}

refers specifically to that limit of `Q` which is determined by `R`.

Also, we will take the limitation operator to have precedence over the determination operator, so the expression `(L⌉P)›Q` can be rewritten without parentheses as:

<div>
L⌉P›Q
</div>
{: .example}

A similar notation exists for the location-determination operator `»`. Where the limit `L` of `P` occurs in some location `l`, and `P` determines `Q`, the expression

<div>
l»Q
</div>
{: .example}

Selects for the limit of `Q` that occurs in `l` and only in `l`.


### Combining limiters and determinants

Let’s put this all together with the example of fire and smoke. There is a generator relation between each instance of fire and each instance of smoke with a generic right abstraction `E` occurring in the smoke and a generic left abstraction `C` occuring in the fire. Let `F` be a property occurring in all and only instances of  fire and `S` be a property similarly occuring in instances of smoke. Now, let us further suppose that all smokes are generated by fires.

Then the property:

<div>
(S⌉E›C)⌉F
</div>
{: .example}

selects for that limit of `F` which is limited by the limit of `C` which is determined by the limit `E` which is limited by `S`. In plain english, this is the property of being a smoking fire. i.e. a fire that generates smoke.

### Negations

Negations are objects similar to relations. A negation is also a kind of property that occurs in two locations: one right and one left. Though, when talking about negations, we often refer to just the right location as its ‘location’ proper. We call the left location its *argument* and the left relational abstraction its *argumenthood*. 

Another way of phrasing this is to say that by ‘negation’ we really mean the right abstraction of a certain two-location property whose left abstraction is the argumenthood determining that negation.

Negations can be divided into two classes: tensed and untensed. The tensed negations are themselves of two kinds: called ‘past negation’ and ‘future negation’. The untensed negations are also of two kinds: ‘total negation’ and ‘difference’. In general, when we just say ‘negation’ we mean total negation.

A total negation represents a negative fact. It represents something not being true of something else or of some object not existing somewhere. A difference represents the fact that two objects are not identical to one another. Past and future negations represent past and future negative facts. 

This may all seem fairly abstract at the moment. And it may not be so clear why concepts like identity and tense (past/future) should be expressed in the negative at all. These are fair questions! Part of the answer is this: Negations have a rich logic of composition. For example, an occurrence relation can be expressed as the negation of a negation. Universality can be expressed as the negation of existence. Disjunction can be expressed as the negation of a conjuction of negations. Different tensed concepts (‘now’, ‘later’, ‘until’, ‘unless’, ‘never’, ‘always’, etc.) can be elegantly expressed with combinations of tensed and nontensed negations. And so on. As a result, treating the negations themselves as the primitives and constructing other logical structures out of them can yield a particularly elegant analysis.

A last point about negations. There is one important difference between negations and typical ‘positive’ relations.

Let us represent total negation with the expression `⟨⊥⟩`. The angle brackets `⟨` and `⟩` mean ‘property of’ and the up tack `⊥` represents the negation operator. We’ll look more closely at the notation itself in a bit. But for now, let’s just understand the expression `⟨⊥⟩` to refer to the total negation right abstraction. Similarly, let us represent the argumenthood determining `⟨⊥⟩` with the symbol `⟨⊐⟩`. Then, we can construct a more specific negation by limiting the argumenthood and selecting for its determinant:

<div>
F⌉⟨⊐⟩›⟨⊥⟩
</div>
{: .quote .example}

The important difference pertains to the limiting relation between the generic negation `⟨⊥⟩` and the specific negation 
`F⌉⟨⊐⟩›⟨⊥⟩`. 

In the case of positive relations, e.g. the generator relation, the specific is a limit of the generic. So, the specific right generator abstraction `F⌉C›E` is a limit of the generic right abstraction `E`. However, in the case of negations, the generic is a limit of the specific! So, the generic negation `⟨⊥⟩` is a limit of the specific negation `F⌉⟨⊐⟩›⟨⊥⟩`.

Can you see why this might be? 

## The Formalisms

### Operators

Individual symbols represent objects. When symbols are embedded in larger expressions, then their reference is modulated by the other symbols in the expression. So, if you recall: If the symbol `F` refers to the property of being a fire, then the symbol `F` embedded in the expression `(S⌉E›C)⌉F` refers specifically to the property of being a smoking fire.

Note that for traditional Navyanaiyyāyikas, expressions do not refer. Only symbols do. This is a point of some contention and there is a whole debate about the reference values of expressions and sentences. But, we won’t get into that so much here. However, we will occasionally say of some expression that it represents a certain object. For Naiyyāyikas, this is to be understand not as the expression as a whole having some value. Rather, it is that a certain symbol within that expression—let’s call it the head symbol—has that value.

Now, regardless of our position on this question, one thing is clear. We have only been talking about referring to *objects*. But, we also need a way to talk about facts. 

From a certain way of thinking, a fact is just another kind of object. Specifically, it is a relation: The fact that, e.g., the sky is blue is just the relation of property possession between sky and blue. And we’ve already seen how to represent relations. In fact, we can represent this relation as just the occurrence relation. 

The expression `⟨⸥⟩` represents the location abstraction; i.e. the generic right abstraction of the property-location relation. The expression `⟨⸣⟩` represents the property abstraction. If `S` refers to the property of being sky and `B` to the property of being the color blue, then the expression:

<div>
B⌉⟨⸣⟩›S⌉⟨⸥⟩
</div>
{: .example}

represents the occurence of a blue property in a sky object. 

Now, expressions like this are somewhat combursome. To make it shorter and easier to scan, the language of Navyanyāya includes a class of symbols we will call *operators*. We have already seen a few operators, including the deterimination and limitation operators as well as the location, property, and negation operators. Though we’ve only seen the last three inside angle brackets. The angle brackets we will call the ‘abstraction’ operator, though it’s associated with a special syntax of its own.

Broadly, we can consider Nyāya symbols to be of two kinds: parameters and operators. Parameters can be assigned values and are either variable or constant. The rule for parameters is that two parameters within the same scope must be assigned the same value.

A parameter in a given expression can take on a set of values which we will call its domain. When a parameter is bound to an operator, the operator modifies the domain of the bound parameter. In the case of the limitation and determination operators, they select for limits of the value of the bound parameter, as we saw earlier.

Operators, as we said, bind parameters and modify their domains. In general, an operator can bind to two parameters, which we will call the left and right parameters, respectively. When an operator binds a parameter on the right side, we call it the *applicand*. When it binds to a parameter on the left, we call it the *argument*.

To use a familiar example, in the expression:

<div>
F⌉C
</div>
{: .example}

the limitation operator `⌉` is applied to `C` and takes `F` as its argument. The applicand `C` which previously referred to the generic cause abstraction now refers to the the limit of `C` which is limitted by `F`. 

Now, the simplest kind of operator is what we’ll call a typing operator. A typing operator is defined in terms of a property called its type. When applied to a parameter, the typing operator constraints the domain of its applicand such that only those objects which locate its type can be assigned as values to its applicand. 

For example, let us define the typing operator `Fire` as having the type `F`. Then in the expression:

<div>
Fire f
</div>
{: .example}

the value of `f` is constrained such that it locates the property `F`. Since `F` refers to the property of being fire, this means that `f` must refer to an instance of fire. Note the space between the operater and its applicand, this is to help resolve a possible ambiguity in the syntax that we will look at shortly. 

First, however, we will consider the case where the type of a typing operator is a dependent property. In this case, the argument specifies its determining location. Let’s define the operator `Effect` with type `E`. Then, in the following expressions:

<div>
(Fire f)Effect s
</div>
{: .example}

the parameter `s` can only refer to an object if it locates the limit of `E` which is determined by the value of `f`. The value of `f` is constrained by the operator `Fire` such that `f` must evaluate to a location of `F`. This means that the value of `s` must be locate the property:

<div>
F⌉C›E
</div>
{: .example}

The expression `(Fire f)Effect s` can be further simplified by taking advantage of a rule regarding typing operater syntax. Namely, a typing operator applied to a parameter that does not recur in the same lexical scope can be omitted from the expression. In such a case, there is an implicit anonymous parameter understood to occur as its applicand. Using this rule, we can rewrite `(Fire f)Effect s` as:

<div>
(Fire)Effect
</div>
{: .example}



### The Location and Property Operators

Blue⸥ Sky

### The Negation Operators

### The Abstraction Operator

### Assertions

### Definitions

## High level overview of the syntax

### Symbols

A Navyanyāya formula is a string of symbols. These symbols can be divided into two categories: evaluable and nonevaluable symbols. Nonevaluable symbols serve a merely syntactic purpose. For instance, whitespace and punctuation which serve to identify boundaries between symbols, disambiguate expressions, and specify the scope of variables.

Evaluatable symbols can be assigned a value. 

### Expressions

Navya formula can be broadly divided into two categories: expressions and statements. An expression, let us call it `Ψ(s)`, is a string of symbols containing one ‘head’ `s` and some number or subordinates.

The symbols that make up an expression can themselves be divided into two kinds: evaluable and nonevaluable symbols. An evaluable symbol can be assigned a value. Expressions do not themselves evaluate to anything. However, we can nominally consider the value of the head symbol as the “value” of the expression. We will talk about the sorts of objects that symbols can evaluate to in the section on the abstractions. 


### Statements

A statement is composed of two or more expressions. A statement comprising just two expressions is called a simple statement. A statement containing more than two expressions is a compound statement. Statements—and *only* statements—can be assigned a truth value. The truth value of a statement is assigned on the basis of a relation between the values of the expressions (really the values of the expression heads) that make it up. Statements can also be divided into two categories based on how its truth value is assigned: assertions and definitions.

Given two expressions `Ψ(a)` and `Φ(b)`, we will write a simple assertion by placing a right turnstile before them:
    
<div>
	⊦ Ψ(a) Φ(b)
</div>
{: .quote .example}

A compound assertion is just multiple simple assertions joined together with a comma:

<div>
	⊦ ψ<sub>1</sub>(a) φ<sub>1</sub>(b), Ψ<sub>2</sub>(a) Φ<sub>2</sub>(b), ...
</div>
{: .quote .example}

A simple assertion `⊦ Ψ(a) Φ(b)` is true if and only if there exists some object `O` such that `a` and `b` can both evaluate to `O`. In other words, the assertion `⊦ Ψ(a) Φ(b)` asserts that there exists a some object to which both `a` and `b` can bind to in their respective expressions.




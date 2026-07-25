---
author: Pramod Chavali
title: Some More Abstractions of Navyanyāya and their Associated Notations
layout: default
---

# Some more abstractions of Navyanyāya and their associated notations

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


# High level overview of the syntax

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




---
layout: post
title:  "Think Again II: How to Reason Deductively"
---

# Module 2
## 2.1 Deductive Logic
### 2.1.1 Introduction to Deductive Logic

**Deductive Argument**: An argument that is *presented* as valid. (Remember: Valid arguments have no possible way for the conclusion to be false when the premises are true.)

**Inductive Argument**: Arguments that are not presented as being valid but strong. These are successful only to the extent that they *are* strong.

### 2.1.2 Propositions and Propositional Connectives

**Proposition**: Something that can be either true or false, and that can be premise or conclusion of an argument.

Not a proposition:
* Binoculars
* A hand

Is a proposition:
* The binoculars are in my hand. (This is something that can be **true** or **false**.)

**Propositional Connective**: Something that takes propositions and makes **new** propositions out of them.

Example: "and"
1. I am holding the binoculars.
2. I am looking through the binoculars.
* I am holding the binoculars **and** looking through them.

### 2.1.3 "And" and the Truth-Functional Connectives

**"and"** can mean a lot of things.

Consider: *"I took a shower and got dressed."*    \
There is a sort of **temporal** order to this. You take the shower first THEN get dressed. It wouldn't make sense the other way around.

Now consider: *"I am holding the binoculars and looking through them."*   \
Here, there is no sense of temporal order. This time, "and" is a **truth-functional connective**.

**Truth-Functional Connective**: A propositional connective that makes a new proposition whose truth or falsity depends solely on the truth or falsity of its propositional ingredients.

![](https://i.postimg.cc/VLq1qHVK/Screenshot-2025-07-17-at-12-44-24-AM.png)
_The truth or falsity of "Jack and Jill talked" depends on nothing other than the truth or falsity of the two connected propositions._f

### 2.1.4 Using Truth Tables to Show Validity

#### Conjunction Introduction Argument (AND)

![](https://i.postimg.cc/W113659c/Screenshot-2025-07-17-at-8-47-45-PM.png)

#### Conjunction Elimination Argument 

![](https://i.postimg.cc/ZR84hNfL/Screenshot-2025-07-17-at-8-49-16-PM.png)
_Can still refer to the AND truth table for this^_

### 2.1.5 Rules Variables and Generality

Rules are **general**.

"Stop hitting your brother right now!" &rarr; NOT a rule, but a command. "Right now" applies to a particular situation.

"You should never hit another person." &rarr; A rule! So is: "You should never hit your brother." &rarr; This rule applies to a multitude of possible situations.

#### Expressing Even More Generality

![](https://i.postimg.cc/Dyk6mRSW/Screenshot-2025-07-18-at-11-32-17-AM.png)

#### Notation for Truth-Functions

**Conjunction**: &

**Disjunction**: V

**Negation**: ~ or ¬

### 2.1.6 Disjunction

**Inclusive OR**  \
"He is a math major or physics major" &rarr; It is possible to be both.

**Exclusive OR** \
"Either Manchester won or Barcelona won." &rarr; They cannot BOTH win.

#### Disjunction Truth Table
![](https://i.postimg.cc/TY58vzZp/Screenshot-2025-07-18-at-11-41-11-AM.png)
![](https://i.postimg.cc/ZKSQXWFD/Screenshot-2025-07-18-at-11-46-11-AM.png)

## 2.2 Conjunctions and Disjunctions
### 2.2.1 Negation and Truth Functional Operators

**Propositional Operator**: Converts one proposotion into another proposition. (e.g. "I believe that...")

**Truth-Functional Operator**: A *propositional operator* that creates propositions whose truth depends solely on the truth of the proposition to which the operator is applied.

#### Negation
You know this lol

### 2.2.2 Commutativity and Associativity

**Commutativity**: A function of two things that delivers the same results no matter what order it operates on those things.    \
E.g. Addition, multiplication. Subtraction is NOT commutative.

![](https://i.postimg.cc/2SNHcLNx/Screenshot-2025-07-20-at-12-12-25-AM.png)

**Associativity**: A function of three or more things that delivers the same result no matter what order it operates on those things.
E.g. Addition, multiplication. Subtraction is NOT commutative.

![](https://i.postimg.cc/c40hfyRD/Screenshot-2025-07-20-at-12-14-09-AM.png)

## 2.3 Conditionals
### 2.3.1 The Conditional

"If...., then...." &rarr; is a **Propositional Connective**, but it is also a **truth-functional connective**!

![](https://i.postimg.cc/Fz979G4F/Screenshot-2025-07-20-at-1-50-27-PM.png)

#### Modus Ponens

* From the premises
* P &rarr; "P is true"
* If P, then Q &rarr; "It is true that P, then Q"
* Infer
* Q &rarr; "Q MUST be true"

#### Modus Tollens

* From the premises
* ~Q
* If P, then Q
* Infer
* ~P

### 2.3.2 Biconditionals

"If and only if..."

![](https://i.postimg.cc/0562Rq42/Screenshot-2025-07-21-at-11-46-21-AM.png)

![](https://i.postimg.cc/N0fBNhTt/Screenshot-2025-07-21-at-11-47-34-AM.png)

# Module 3
## 3.1 Categorical Logic
### 3.1.1 Categorical Logic

Consider this argument. Is it valid?:

![](https://i.postimg.cc/mD5W1npS/Screenshot-2025-07-21-at-8-26-43-PM.png)

It's a bit tricky to find out just by looking at it, but we can use a truth table (using the biconditional method from earlier) to prove that it is VALID!

![](https://i.postimg.cc/dVY307yV/Screenshot-2025-07-21-at-8-27-09-PM.png)
_Hint: There are no rows with true premises and a false conclusion. Take a look at Row 1 to see that the conclusion MUST be true given that the premises are true._

### 3.1.2 Categories and Quantifiers

#### Categories

**Categories**: Just sets of things in an argument.

(1) Brazilians speak Portuguese.    \
(2) Portuguese speakers understand Spanish. \
∴ (3) Brazilians understand Spanish.

*The categories here are: Brazilians, Portuguese speakers, and people who understand Spanish.*

#### Quantifiers

(1) **Some** Brazilians speak Portuguese.    \
(2) **Some** Portuguese speakers understand Spanish. \
∴ (3) **Some** Brazilians understand Spanish.

But... the argument is still not valid.

Or maybe the right way to understand the argument is like this:

(1) **Most** Brazilians speak Portuguese.    \
(2) **Most** Portuguese speakers understand Spanish. \
∴ (3) **Most** Brazilians understand Spanish.

Again, the argument is still not valid.

Now, how about this:

(1) **All** Brazilians speak Portuguese.    \
(2) **All** Portuguese speakers understand Spanish. \
∴ (3) **All** Brazilians understand Spanish.
 
Now, this argument is **VALID**.

### 3.1.3 How Quantifiers Modify Categories

**Proposition Forms:**

**A**: All Fs are Gs.   \
**E**: No Fs are Gs.    \
**I**: Some Fs are Gs.  \
**O**: Some Fs are not Gs.

*Where F and G are any possible category.*

### 3.1.4 Immediate Categorical Inferences

**Immediate Categorical Inference**: An inference with just one premise, in which **both** the premise and the conclusion are in the form A/E/I/O.

In each proposition of the form A/E/I/O, there is a subject term and a predicate term.

**Subject Term** &rarr; The one modified by the quantifier. (I.e. The "F" term) \
**Predicate Term** &rarr; The other term ("G")

#### Conversion

The most common type of Immediate Categorical Inference.

**Conversion**: An inference in which the conclusion switches the subject and predicate term that occur in the premise.

(1) No Fs are Gs.   \
∴ (2) No Gs are Fs

(1) All Fs are Gs.   \
∴ (2) All Gs are Fs

#### Which Conversion Inferences are Valid?

Look at the venn diagrams for this &darr;

**A**: All Fs are Gs, All Gs are Fs &rarr; **NOT VALID**    \
**E**: No Fs are Gs, No Gs are Fs &rarr; **VALID**  \
**I**: Some Fs are Gs, Some Gs are Fs &rarr; **VALID**  \
**O**: Some Fs are not Gs, Some Gs are not Fs &rarr; **NOT VALID**

## 3.2 Syllogisms
### 3.2.1 Syllogisms

**Syllogism**: An argument that has **two premises and a conclusion**, where all three propositions are of the A/E/I/O form.

The conclusion has two categories/terms:

**Subject Term of the Syllogism** &rarr; The one modified by the quantifier. (I.e. The "F" term) \
**Predicate Term of the Syllogism** &rarr; The other term ("G")

Every syllogism has a premise that includes the **subject term (minor premise of the syl)** and a premise that includes the **predicate term (major premise of the syl)**.

### 3.2.2 Categories, Individuals, and Language

A lot of our statements in life are about individuals not about categories. This is an example of how ordinary language can mislead us. Sometimes what we're saying in ordinary statement that appears to be about individuals are actually about categories. We just aren't aware of this sometimes.

#### How Language can Mislead
![](https://i.postimg.cc/bYTr0mYy/Screenshot-2025-07-23-at-12-15-41-PM.png)

These two statements amount to the same thing. The statement "Mary owns a Ferrari." is true if and only if "Some of Mary's possessions are Ferrari cars.". The information carried by both statements are the SAME. These statements are EQUIVALENT.

This means, that we actually CAN use venn diagrams here because statement 2 is in a proposition form (specifically I, from the A/E/I/O thing), unlike statement 1 which seems like it's not possible to use venn diagrams. Keep this in mind because this happens in a lot of our language.

### 3.2.3 Other Ways of Expressing A, E, I, or O Propositions

#### Not all Fs are Gs (= Some Fs are not Gs)
![](https://i.postimg.cc/rFbDr1x6/Screenshot-2025-07-25-at-11-46-10-AM.png)
![](https://i.postimg.cc/DZBZyLnM/Screenshot-2025-07-25-at-11-47-47-AM.png)

#### All Fs are not Gs (= No Fs are Gs)
![](https://i.postimg.cc/QxWXvR9P/Screenshot-2025-07-25-at-11-49-35-AM.png)
![](https://i.postimg.cc/fW74XDdM/Screenshot-2025-07-25-at-11-54-18-AM.png)

#### Some Fs are both Gs and Hs 
![](https://i.postimg.cc/9Mj8FwJZ/Screenshot-2025-07-25-at-11-57-35-AM.png)
![](https://i.postimg.cc/qMt8SMGT/Screenshot-2025-07-25-at-11-59-01-AM.png)
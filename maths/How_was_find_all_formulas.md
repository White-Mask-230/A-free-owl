Title: How was find all formulas of mathemathics

# Index
[1. Introduction](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#1-introduction)

[1.1. Goal of the book](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#11-goal-of-the-book)

[1.2. Problems solve](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#12-problems-solve)

[1.3. Book nomenclature](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#13-book-nomenclature)

[2. Algebra](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#2-algebra)

[2.1. Linear algebra](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#21-linear-algebra)

[2.1.1. Summation](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#211-summation)

[2.2. Elementary Algebra](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#22-elementary-algebra)

[2.2.1. Notable Identities](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#221-notable-identities)

[2.2.2. Property of Fractions](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#222-property-of-fractions)

[2.2.3. Property of multiplications](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#223-property-of-multiplications)

[3. Mathematical analysis](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#3-mathematical-analysis)

[3.1. Calculus](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#31-calculus)

[3.1.1. Limits](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#311-limits)

[3.1.2. Derivative](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#312-derivative)

[3.1.3. Integrals](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#313-integrals)

[4. Reference](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#4-reference)

[5. Make by](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#5-make-by)

# 1. Introduction
## 1.1. Goal of the book
The goal of this book is to compile how all the mathematical formulas have
been discovered.

## 1.2. Problems solve
* To avoid the mathematics becoming a dogma, for that this book proves
and display how all the formulas where discovered, instead of just thinking
that they are correct.

* There is a lot of information relate to the mathematics scattered in differ-
ent websites, journals and books. This make difficult to the people that
want to learn by themselves all the mathematical formulas. To make it
more easy, we are preparing this book which will contain all the original
information that have this sources.

* Verification of information different of the classical peer review.

## 1.3. Book nomenclature

In all equations you will see in any step a link of the property use in that step except is something very obvious 

* The formula is was find in a paper cited in the reference: [”id-reference”]
* The formula is a definition but there is any reference: [x]
* Is a popular formula but it doesn’ t find how was make: (x)
* The formula was wrote less than a month: (*)
* The formula was wrote more than a month: (+)
* The formula is cited in a issue: (-)
* Use a formula that is not demonstrated: (?)

## 1.4 Readme of the project
[here](https://github.com/White-Mask-230/A-free-owl/blob/main/README.md)

# 2. Algebra
## 2.1. Linear algebra
### 2.1.1. Summation
#### Definition summation (id 2.1) (*)
$\sum^n_{i=j} f(i) = f(j) + f(j + 1) + \cdots + f(n - 1) + f(n)$

#### Change limits
##### Index shift (id 2.2) (*)

$\sum^{n - 1}_{i=j - 1} f(i + 1) = f(j - 1 + 1) + f(j - 1 + 2) + \cdots + f(n - 2 + 1) + f(n - 1 + 1)$ [id 2.1](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#21-linear-algebra)

$= f(j) + f(j + 1) + \cdots + f(n - 1) + f(n)$ 

$= \sum^n_{i=j} f(i)$ [id 2.1](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#21-linear-algebra)

#### Arithmetic Operations
##### Summation of the addition or subtraction of two function (id 2.3) (*)

$\sum^n_{i=j} f(i) + g(i) = f(j) + g(j) + f(j + 1) + g(j + 1) + \cdots + f(n - 1) + g(n - 1) + f(n) + g(n)$ [id 2.1](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#21-linear-algebra)

$= f(j) + f(j + 1) + \cdots + f(n - 1) + f(n) + g(j) + g(j + 1) + \cdots + g(n - 1) + g(n)$

$= \sum^n_{i=j} f(i) + \sum^n_{i=j} g(i)$ [id 2.1](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#21-linear-algebra)

#### With Constants

##### Summation of a constant (id 2.4) (*)

Note $C_1 = C_2 = \cdots = C_{n - 1} = C_n$

$\sum^n_{i=1} C = C_1 + C_2 + \cdots + C_{n - 1} + C_n$ [id 2.1](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#21-linear-algebra)

$= C \cdot n$

##### Summation of a constant and a multiplication (id 2.5) (*)

$\sum^n_{i=j} C \cdot f(i) = C \cdot f(j) + C \cdot f(j + 1) + \cdots + C \cdot f(n - 1) + C \cdot f(n)$ [id 2.1](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#21-linear-algebra)

$= C [f(j) + f(j + 1) + \cdots + f(n - 1) + f(n)]$ [id 2.9.](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#distributive-property-id-29-)
                    
$= C \sum^n_{i=j} f(i)$ [id 2.1](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#21-linear-algebra)

## 2.2. Elementary Algebra
### 2.2.1. Notable Identities
##### Square of a summation or difference (id 2.6) (*)

$(a + b)^2 = a + b \cdot a + b$

$= \sum^{a + b}_{i=1} a + b$ [id 2.4](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#summation-of-a-constant-id-24-)

$\sum_{i=1}^{a + b} a + \sum_{i=1}^{a + b} b$ [id 2.3](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#summation-of-the-addition-or-subtraction-of-two-function-id-23-)

$= a(a + b) \pm b(a + b)$ [id 2.4](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#summation-of-a-constant-id-24-)

$= a^2 + a \cdot b + a \cdot b + b^2$ [id 2.9](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#distributive-property-id-29-)

$= a^2 + 2 \cdot a \cdot b + b^2$

##### Sum by difference (id 2.7) (*)

$a + b \cdot a - b = \sum^{a + b}_{i=1} a - b$ [id 2.4](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#summation-of-a-constant-id-24-)

$= \sum_{i=1}^{a + b} a - \sum_{i=1}^{a + b} b$ [id 2.3](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#summation-of-the-addition-or-subtraction-of-two-function-id-23-)

$= a(a + b) - b(a + b)$ [id 2.4](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#summation-of-a-constant-id-24-)

$= a^2 + b \cdot a - b \cdot a - b^2$ [id 2.9](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#distributive-property-id-29-)

$= a^2 - b^2$

### 2.2.2. Property of Fractions
##### Addition of two fractions (id 2.10) (*)
$\frac{a}{b} + \frac{c}{d} = \frac{a \cdot d}{b \cdot d} + \frac{c \cdot b}{b \cdot d}$

$= \frac{a \cdot d + c \cdot b}{b \cdot d}$

##### Multiplication of two fractions (id 2.11) (*)
$\frac{a}{b} \cdot \frac{c}{d} = \frac{a}{b} \cdot \frac{c}{d} \cdot b \cdot d / b \cdot d$

$= a \cdot c / b \cdot d$

$= \frac{a \cdot c}{b \cdot d}$

##### Fraction of a fraction (id 2.12) (*)
$\frac{a}{\frac{b}{\frac{c}{d}}} = \frac{a \cdot d}{\frac{b \cdot c}{\frac{c \cdot d}{d \cdot c}}}$

$= \frac{a \cdot d}{b \cdot c}$

##### Multiplication and division of the same number (id 2.14) (*)
$a \cdot \frac{1}{a} = \sum^a_{i=1} \frac{1}{a}$

$= \frac{1}{a} + \sum^{a - 1}_{i=1} \frac{1}{a}$

$= \frac{2}{a} + \sum^{a - 2}_{i=1} \frac{1}{a}$

$\vdots$

$= \frac{a}{a}$

$= 1$

### 2.2.3. Property of multiplications
##### Distributive property (id 2.9) (*)
                    
$a(b + c) = \sum^a_{i=1} b + c$ [id 2.4](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#summation-of-a-constant-id-24-)

$= \sum^a_{i=1} b + \sum^a_{i=1} c$ [id 2.3](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#arithmetic-operations)

$= a \cdot b + a \cdot c$ [id 2.4](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#summation-of-a-constant-id-24-)

# 3. Mathematical analysis
## 3.1. Calculus
### 3.1.1. Limits
Note: In this subsection I don’ t find information of how was find this formulas

#### Properties
##### If only constant (id 3.1) [1] (x)

$\lim_{x \rightarrow c} k = k$
    
##### If only the term that approximates to (id 3.2) [1] (x)

$\lim_{x \rightarrow c} x = c$

##### If there is a constant and a function (id 3.3) [1] (x)

$\lim_{x \rightarrow c} k \cdot f(x) = k \lim_{x \rightarrow c} f(x)$
    
##### If there are two functions that are $\pm$ (id 3.4) [1] (x)

$\lim_{x \rightarrow c} [f(x) \pm g(x)] = \lim_{x \rightarrow c} f(x) \pm \lim_{x \rightarrow c} g(x)$
    
##### If there are two functions that multiply (id 3.5) [1] (x)

$\lim_{x \rightarrow c} [f(x) \cdot g(x)] = \lim_{x \rightarrow c} f(x) \cdot \lim_{x \rightarrow c} g(x)$
    
##### If there are two functions that divide (id 3.6) [1] (x)

$\lim_{x \rightarrow c} \left[\frac{f(x)}{g(x)}\right] = \frac{\lim_{x \rightarrow c} f(x)}{\lim_{x \rightarrow c} g(x)}$
    
##### If one function composite the other function (id 3.7) [1] (x)

$\lim_{x \rightarrow c} f(g(x)) = f(\lim_{x \rightarrow c} g(x))$

#### Theorem
##### Squeeze Theorem $f(x) \leq g(x) \leq h(x)$ (x) [1] (id 3.8)
$\lim_{x \rightarrow c} f(x) = \lim_{x \rightarrow c} h(x) = L \rightarrow \lim_{x \rightarrow c} g(x) = L$

#### Definition functions or numbers
##### Definition of a derivative (id 3.9) (x)
$\frac{d}{dx} f(x) = \lim_{h \rightarrow 0} \frac{f(x + h) - f(x)}{h}$

##### Definition of a integral (id 3.10) (x)
$\int^b_a f(x) dx = \lim_{n \rightarrow \infty} \frac{b - a}{n} \sum^n_{i=1} f\left(a + i \frac{b - a}{n}\right)$

### 3.1.2. Derivative
#### With Constants
##### Derivative of constant multiply and function (id 3.11) (*)

$\frac{d}{dx} [C f(x)] = \lim_{h \rightarrow 0} \frac{C \cdot f(x + h) - C \cdot f(x)}{h}$ [id 3.9](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#definition-of-a-derivative-id-39-x)

$= C \lim_{h \rightarrow 0} \frac{f(x + h) - f(x)}{h}$ [id 2.5](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#summation-of-a-constant-and-a-multiplication-id-25-) [id 3.3](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#if-there-is-a-constant-and-a-function-id-33-1-x)

$= C \frac{d}{dx} f(x)$ [id 3.9](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#definition-of-a-derivative-id-39-x)

##### Derivative of a constant (id 3.12) (*)

$\frac{d}{dx} [C] = \lim_{h \rightarrow 0} \frac{C - C}{h}$ [id 3.9](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#definition-of-a-derivative-id-39-x)

$= 0$

#### Arithmetic Operations
##### Derivative of the addition or subtraction of two functions (id 3.13) (*)

$\frac{d}{dx} [f(x) \pm g(x)] = \lim_{h \rightarrow 0} \frac{f(x + h) \pm g(x + h) - f(x) -g(x)}{h}$ [id 3.9](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#definition-of-a-derivative-id-39-x)

$= \lim_{h \rightarrow 0} \frac{f(x + h) - f(x)}{h} \pm \lim_{h \rightarrow 0} \frac{g(x + h) - g(x)}{h}$ [id 3.4](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#if-there-are-two-functions-that-are-pm-id-34-1-x)

$= \frac{d}{dx} f(x) \pm \frac{d}{dx} g(x)$ [id 3.9](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#definition-of-a-derivative-id-39-x)

##### Derivative of a multiply of two functions (id 3.14) (*)

$\frac{d}{dx} [f(x) \cdot g(x)] = \lim_{h \rightarrow 0} \frac{f(x + h) \cdot g(x + h) - f(x) \cdot g(x)}{h}$ [id 3.9](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#definition-of-a-derivative-id-39-x)

Note: addition and subtraction of $f(x) \cdot g(x + h)$

$= \lim_{h \rightarrow 0} \frac{f(x + h) \cdot g(x + h) - f(x) \cdot g(x) + f(x) \cdot g(x + h) - f(x) g(x + h)}{h}$

$= \lim_{h \rightarrow 0} \frac{[f(x + h) \cdot g(x + h) - f(x) \cdot g(x + h)] + [f(x) \cdot g(x + h) - f(x) \cdot g(x)]}{h}$

$= \lim_{h \rightarrow 0} \frac{f(x + h) \cdot g(x + h) - f(x) \cdot g(x + h)}{h} + \lim_{h \rightarrow 0} \frac{f(x) \cdot g(x + h) - f(x) \cdot g(x)}{h}$ [id 3.4](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#if-there-are-two-functions-that-are-pm-id-34-1-x)

$= \lim_{h \rightarrow 0} \frac{g(x + h) \cdot [f(x + h) - f(x)]}{h} + \lim_{h \rightarrow 0} \frac{f(x) \cdot [g(x + h) - g(x)]}{h}$ [id 2.9](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#distributive-property-id-29-)

$= \lim_{h \rightarrow 0} g(x + h) \cdot \frac{f(x + h) - f(x)}{h} + \lim_{h \rightarrow 0} f(x) \cdot \frac{g(x + h) - g(x)}{h}$

$= g(x) \cdot \lim_{h \rightarrow 0} \frac{f(x + h) - f(x)}{h} + f(x) \cdot \lim_{h \rightarrow 0} \frac{g(x + h) - g(x)}{h}$ [id 3.1](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#if-only-constant-id-31-1-x) [id 3.2](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#if-only-the-term-that-approximates-to-id-32-1-x)

$= g(x) \cdot \frac{d}{dx} [f(x)] + f(x) \cdot \frac{d}{dx} [g(x)]$ [id 3.9](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#definition-of-a-derivative-id-39-x)

##### Derivative of a function elevate by a constant (id 3.15) (?) [Credits](https://www.youtube.com/watch?v=dZnc3PtNaN4&t=304s)

$\frac{d}{dx} f^n(x) = \lim_{h \rightarrow 0} \frac{f^n(x + h) - f^n(x)}{h}$ [id 3.9](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#definition-of-a-derivative-id-39-x)

$= \lim_{h \rightarrow 0} \frac{-f^n(x) + \sum^n_{k=0} \binom{n}{k} f^{n - k}(x + h) \cdot h^k}{h}$ [?]

$= \lim_{h \rightarrow 0} \sum^n_{k=1} \frac{\binom{n}{k} f^{n - k}(x + h) \cdot h^k}{h}$

$= \lim_{h \rightarrow 0} \sum^n_{k=1} \binom{n}{k} f^{n - k}(x + h) \cdot h^{k - 1}$

$= \sum^n_{k=1} \lim_{h \rightarrow 0} \binom{n}{k} f^{n - k} (x + h) \cdot h^{k - 1}$ [id 3.4](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#if-there-are-two-functions-that-are-pm-id-34-1-x)

$= \lim_{h \rightarrow 0} \binom{n}{1} f^{n - 1}(x + h) h^{1 - 1} + \lim_{h \rightarrow 0} \binom{n}{2} f^{n - 2}(x + h) h^{2 - 1} + \cdots + \lim_{h \rightarrow 0}\binom{n}{k} f^{n - k}(x + h) h^{k - 1}$ [id 2.1](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#definition-summation-id-21-)

$= n \cdot f^{n - 1}(x)$ [id 3.2](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#if-only-the-term-that-approximates-to-id-32-1-x)

##### Derivative of a division of two functions (id 3.16) (*)
$\frac{d}{dx} \left[\frac{f(x)}{g(x)}\right] = \frac{d}{dx} [f(x) \cdot g^{-1}(x)]$

$= g^{-1}(x) \cdot \frac{d}{dx}f(x) + f(x) \cdot \frac{d}{dx} g^{-1}(x)$ [id 3.14](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#derivative-of-a-multiply-of-two-functions-id-314-)

$= g^{-1}(x) \frac{d}{dx} f(x) - f(x) \cdot g^{-2}(x) \cdot \frac{d}{dx}g(x)$

$= \frac{g(x) \frac{d}{dx} f(x) - f(x) \cdot \frac{d}{dx} g(x)}{g^2(x)}$

##### Derivative of a natural logarithm (id 3.17) (?)

$\frac{d}{dx} \ln(x) = \lim_{h \rightarrow 0} \frac{\ln(x + h) -\ln(x)}{h}$ [id 3.9](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#definition-of-a-derivative-id-39-x)

$= \lim_{h \rightarrow 0} \frac{\ln\left(\frac{x + h}{x} \right)}{h}$ [?]

$= \lim_{h \rightarrow 0} \frac{\ln \left(1 + \frac{h}{x} \right)}{h}$

$= \lim_{h \rightarrow 0} \frac{x}{x} \frac{\ln \left(1 + \frac{h}{x} \right)}{h}$

$= \lim_{h \rightarrow 0} \frac{1}{x} \frac{\ln(1 + \frac{h}{x})}{\frac{h}{x}}$ [id 2.8](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#222-property-of-fractions)

$= \lim_{u \rightarrow 0} \frac{1}{x} \frac{\ln(1 + u)}{u}$

$= \lim_{u \rightarrow 0} \ln(1 + u) \cdot \lim_{u \rightarrow 0} \frac{1}{u \cdot x}$ [id 3.5](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#if-there-are-two-functions-that-multiply-id-35-1-x)

$= \ln(1) \cdot \lim_{u  \rightarrow 0} \frac{1}{u \cdot x}$ [id 3.2](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#if-only-the-term-that-approximates-to-id-32-1-x)

$= \lim_{u \rightarrow 0} \frac{u}{u \cdot x}$

$= \frac{1}{x}$

#### Relation with other functions
##### Relation with $e^x$ (id 3.18) (*)

$\frac{d}{dx}[e^x] = \lim_{h \rightarrow 0} \frac{e^{x + h} - e^x}{h}$ [id 3.9](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#definition-of-a-derivative-id-39-x)

$= \lim_{h \rightarrow 0} \frac{e^x \cdot e^h - e^x}{h}$ 

$= \lim_{h \rightarrow 0} \frac{e^x (e^h - 1)}{h}$ [id 2.9](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#distributive-property-id-29-)
                    
$= \frac{e^x(1 - 1)}{\lim_{h \rightarrow 0} h}$ [id 3.2](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#if-only-the-term-that-approximates-to-id-32-1-x) [id 3.6](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#if-there-are-two-functions-that-divide-id-36-1-x)
                    
$= e^x \frac{1 - 1}{\lim_{h \rightarrow 0} h}$
                    
$= e^x \lim_{h \rightarrow 0} \frac{h}{h}$

$= e^x$

##### Relation with $\int$ (id 3.19) (*)

$\frac{d}{dx} \left[\int^b_a dx f(x) \right] = \lim_{h \rightarrow 0} \frac{1}{h} \left(\int^b_a dx f(x + h) - \int^b_a dx f(x) \right)$ [id 3.9](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#definition-of-a-derivative-id-39-x)

$= \lim_{h \rightarrow 0} \frac{1}{h} \int^b_a dx f(x + h) - f(x)$ [id 3.23](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#integral-of-a-addition-and-a-subtraction-of-two-functions-id-323-)

$= \lim_{h \rightarrow 0} \int^b_a dx \frac{f(x + h) - f(x)}{h}$ [id 3.22](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#integral-of-the-multiply-of-a-function-and-a-constant-id-322-)
                    
$= \int^b_a dx \frac{d}{dx} f(x)$ [id 3.9](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#definition-of-a-derivative-id-39-x)

Relation with $\sum$ (id 3.20) (*)
                    
$\frac{d}{dx} \left[\sum^n_{i=j} f(i, x) \right] = \frac{d}{dx} [f(j, x) + f(j + 1, x) + \cdots + f(n - 1, x) + f(n, x)]$ [id 3.9](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#definition-of-a-derivative-id-39-x)

$= \frac{d}{dx} f(j, x) + \frac{d}{dx} f(j + 1, x) + \cdots + \frac{d}{dx} f(n - 1, x) + \frac{d}{dx} f(n, x)$ [id 3.13](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#derivative-of-the-addition-or-subtraction-of-two-functions-id-313-)

$= \sum^n_{i=j} \frac{d}{dx} f(i, x)$ [id 2.1](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#definition-summation-id-21-)

##### Definition functions or numbers

Function digamma (id 3.21) (?)
$\psi(x) = \frac{d}{dx} \ln[\Gamma(x)] = \frac{\frac{d}{dx} \Gamma(x)}{\Gamma(x)}$

### 3.1.3. Integrals
#### Constants
##### Integral of the multiply of a function and a constant (id 3.22) (*)
$\int^b_a C \cdot f(x) dx = \lim_{n \rightarrow \infty} \frac{b - a}{n} \sum^n_{i=1} C \cdot f\left(a + i \frac{b - a}{n}\right)$ [id 3.10](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#definition-of-a-integral-id-310-x)

$= C \lim_{n \rightarrow \infty} \frac{b - a}{n} \sum^n_{i=1} f \left(a + i\frac{b - a}{n}\right)$ [id 2.5](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#summation-of-a-constant-and-a-multiplication-id-25-) [id 3.3](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#if-there-is-a-constant-and-a-function-id-33-1-x)

$= C \int^b_a f(x) dx$ [id 3.10](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#definition-of-a-integral-id-310-x)

##### Integral of a addition and a subtraction of two functions (id 3.23) (*)
$\int^b_a f(x) \pm g(x) dx = \lim_{n \rightarrow \infty} \frac{b - a}{n} \left[ \sum^n_{i=1} f\left(a + i \frac{b - a}{n}\right) \pm g\left(a + i \frac{b - a}{n} \right) \right]$ [id 3.10](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#definition-of-a-integral-id-310-x)

$= \lim_{n \rightarrow \infty} \frac{b - a}{n} \left[\sum^n_{i=1} f\left(a + i \frac{b - a}{n} \right) \pm \sum^n_{i=1} g\left(a + i \frac{b - a}{n}\right) \right]$ [id 2.3](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#summation-of-the-addition-or-subtraction-of-two-function-id-23-)

$= \lim_{n \rightarrow \infty} \frac{b - a}{n} \sum^n_{i = 1} f\left(a + i \frac{b - a}{n}\right) \pm \lim_{n \rightarrow \infty} \frac{b - a}{n} \sum^n_{i=1} g\left(a + i \frac{b - a}{n}\right)$ [id 3.4](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#if-there-are-two-functions-that-are-pm-id-34-1-x)

$= \int^b_a f(x) dx \pm \int^b_a g(x) dx$ [id 3.10](https://github.com/White-Mask-230/A-free-owl/blob/main/maths/How_was_find_all_formulas.md#definition-of-a-integral-id-310-x)

# 4. Reference
[1] Alan Stein. Properties of Limits: [https://www2.math.uconn.edu/~stein/math115/Slides/math115-130notes.pdf](https://www2.math.uconn.edu/~stein/math115/Slides/math115-130notes.pdf)

# 5. Make by
[Lucas Varela Correa (White-Mask-230)](https://github.com/White-Mask-230)

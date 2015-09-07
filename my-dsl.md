# Language
_What is the name of the language? Link the name to its webpage 
(if appropriate)._

[Asymptote](http://asymptote.sourceforge.net/)

# Domain
_Describe the language's domain in five words._

Creating numerical vector graphics images.

# Computational model
_What is the underlying computational model of this language? To answer this 
question, provide a high-level description (no more than 100 words) of the 
computation that occurs when someone executes a program in this language._

Evaluation is similar to most imperative languages like C.
However, the final data that is being constructed is a "picture" object,
which is eventually converted into an image.

# DSL-ness
_Fowler writes about a spectrum of languages, from general-purpose languages to 
"purely" domain-specific. Where does the DSL you chose fall on this spectrum, 
and why?_ 

Asymptote is definitely a general-purpose language in power. However, it is used in a very specific way
to create vector graphics images. It is essentially unsuitable for other things that a true
programming language would be used for, although it could technically accomplish them.

# Internal or external?
_Is the language implemented as an internal or external DSL? 
Justify your answer._

Definitely external. It is not contained inside any other language, although it
superficially copies C-like syntax.

# Host language
_What language(s) was (were) used to implement the DSL?_

C.

# Benefits
_Identify one potential benefit of the DSL: how is a programmer's life or a 
company's bottom line made easier by the existence of this language?_

Compared to competitors like TikZ and Metapost, Asymptote is actually a general-purpose
language and therefore is more extensible and programmable. Where you have to rely or even
"trick" the computational models behind the others, you can simply program directly in Asymptote,
using sensible and familiar syntax.

# Drawbacks
_Identify one potential drawback of the DSL: what does a programmer or company 
lose by using this DSL instead of a general-purpose language?_

Asymptote is only a toy language when compared to true programming languages. The datatypes,
classes and datastructures are particularly neutered.

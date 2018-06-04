# SSLang - Semantics Supported Language
I am going to create the Semantics Supported Language (SSLang), which cannot do anything, that current languages cannot. And more importantly, I am going to write about the challenges I encounter, and how I solve them.

## Table of Contents: 
Why
What
How
Collaboration 
Grand Ideas
?

## Why
I come from a background in software engineering, where I have learned how to develop software (duh). However, I have not learned about the semantics underlining the languages that I use on a daily basis. This was left to the computer science students. Additionally, I only had a brief encounter with formal proofs, which is another area I would like to learn more about.

I have tried to read several books and various online resources concerning both semantics and formal proof, but you can only learn so much by reading. Furthermore, it is difficult to use semantics and formal proofs in my daily work, because I simply do not have enough knowledge to apply it.

## What
As mentioned in the very top, I am going to create the Semantics Supported Langauge (SSLang). But I am not actually creating a language (yet), I am just creating the semantics of a language. Once I have defined enough semantics of the language in order for the language to be useful in any sense, I will create the language itself. The language will most likely be interpreted, meaning it will require Java/something else executing it. Programs developed in the language will therefore not be compiled to binaries. Furthermore, I hope to begin a process of code-generation to e.g. C along the way. I have many envisioned ideas, and these are presented in **Grand Ideas**.
So how will I do this? See the next section!

## How
This section describes the first steps, that I believe to make up the first two milestones (MSs). These items are also listed under issues as label enhancement. Once I have implemented these I will decide what to do next.
* Define the type Integer (MS 1)
* Define the type Boolean, which can be True or False (MS 2)
* Define arithmetic operators: + (MS 1), - (MS 1), *, and /.
* Define if/else (MS 2)
* Define variables (MS 1)
* Define state (MS 1)
* Write a simple program (MS 1)
* Define sequencing (MS 1)
* Define recursion (MS 2)
* (Theorem) Prove someting about the program (ALWAYS)

So what are the semantics (i.e. the meaning) of define?
Define in this case means to give the following semantics to the bulletins:
* Declarative Semantics
* Operational Semantics
* Axiomatic Semantics
* Implement these languages in the Isabelle/HOL theorem prover.

So what are declarative, operational, and axiomatic semantics? Well, I am not really sure. Will I use all three types of semantics to each of the bulletins? Well, I am not really sure. I guess I will find an answer to these questions along the way, that is the whole purpose of this!

## Collaboration
I have debated this a lot with myself, and I have come to a conclusion:
This is my project, and I do not want to discuss whether something should be added or not. If someone joins the project, then this will inevitable happen. And as I am on such a low level of understand, these will lead to parts that I do not understand, and I might not think is written sufficiently well for newcomers to understand either. Therefore, I am currently not inviting anyone to the repository.

However, I am never going to complete my mission if I do not get help on the way. So I will reach out to people, they will be mentioned and thanked.
I am also very open to feedback and good ideas, but I do not promise to use it.

In the end, I hope to convert this project or at least the knowledge from it into a course (maybe an online course?) and get students to contribute defining new stuff! That would be absolutely amazing.

## Grand Ideas
These are just some ideas from the top of my head. Maybe some of the ideas will be implemented, maybe none, maybe all. Who knows?
* Code generate to C
* Code generate to Javascript
* Code generate to Objective-C/Swift
* Code generate to LLVM (Will this cover all three of the above?)
* Code generate to CSP such that I can use the FDR Model Checker
* Implement some way of defining external dependencies, that does not have a semantics, such that these can be used for code generation and in a proving context. An example of this could be using a HTTP library to download JSON.
* Implement configurable time cost of expressions and statements.
* Add functions to the language
* Add modules to the language
* Write a book!
* Attend a Formal Methods Conference where I present a paper on my work!
* Learn how to use the Unifying Theories of Programming in my work
* Learn how to use Communicating Sequential Processes in my work

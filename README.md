# Modular Conlang Constructor (MCC)
file `README.md`

> current state: pre-alpha

## Core Goal
Create a system to build conlangs out of modular components.
You should be able to add, remove, or replace modular components to create new or different conlangs.
Every modular component handles one concern.
Modular components should be able to communicate with each other using something very similar to an API.
It is not necessary for every modular component to be compatible with each other.
You should also be able to create programming languages with this system not just human ones.

## Why?
It will make conlanging even more fun! Now you can try out things more freely.
You can try a wacky phonology without fear of wasting time because you can use premade vocab or you can swap the sounds any time.
You can also merge already made modules. This speeds up the creation process because you can reuse things.
I also plan to make useful conlangs with this system, because I can make languages that specialize in specific things.
For example: analyzing a table tennis game, singing, or internal thought rather than communication.

## Rough Idea
> By no means is this a formal definition of anything. Just to give you a gist.

This is a writing technique that reads like pseudocode, and uses strict syntax.
All MCC languages are built from the same underlying structural framework, which helps with compatibility.
There are 2 types of values, data and functions.
Data is just pure information, while functions take data as an input and produce data as an output.
The final language will be just data but you can combine data and functions to produce the final language.

These are all the different interacting systems:

### Data
- Semantic Map
    - Defines words and relations between words, with every word stored as a standalone JS-style object.
- Vocab Tree
    - Organizes a Semantic Map into a JS-style object and gives every word a unique or shared path (depending on what you want).
- Rep Set
    - A set of rules that say how to represent the paths a vocab object gives a word.
- Language Lexicon
    - The actual language: every word with its meaning and usage written out.

### Functions
You can create whatever functions you please, so there is no set list of functions but there are types.
Functions can only output one type of data, so we group functions based on what they output.
A function that outputs a Semantic Map is a Semantic Map Function while one that outputs a Vocab Tree is a Vocab Tree Function.
A function's input can be anything, even other functions. You can also have strings ("fast") and numbers (5).

## Roadmap
This is the larger picture scheme of this project and where we are.

1. [x] Define a goal and why I want that
2. [ ] Create a system to achieve goal
    1. [x] The rough idea of how the system works
    2. [ ] Figure out exactly how the system works <-- We are here. We are nearly done. I am halfway between the last 2 systems but it is written in my book.
    3. [ ] Have it all written down to some extent (does not need to be neat)
3. [ ] Testing phase
    1. [ ] Functional testing
    2. [ ] Use-case testing
4. [ ] Write the formal doc: `master-manual.md`
5. [ ] Celebrate!!! ^-^

# **Modular Conlang Constructor (MCC)**
file `README.md`

## **Core Goal**
Create a system to create conlangs out of modular components.
You should be able to add, remove, or replace modular components to create new or different conlangs.
Every modular component should be handling one concern.
The modular components should be able to communicate with each other using something very similar to an API.
It is not necessary for every modular component to be compatible with eachother.
You should also be able to create programming languages with this system not just human ones.

## **Why?**
It will make conlanging even more fun! Now you can try out things more freely.
You can try a wacky phonology without fear of wasting time because you can use premade vocab or you can swap the sounds any time.
You can also merge already made modules. This speeds up the creation process because you do not need to keep making the same things over and over. 

## **Roadmap**
This is the larger picture scheme of this project and where we are.

1. [x] Define a goal and why I want that
2. [ ] Create a system to achieve goal
    1. [x] The rough idea of how the system works
    2. [ ] Figure out exactly how the system works <-- We are here. We are nearly done. I am halfway between the last 2 systems but it is written in my book.
    3. [ ] Write it all down
3. [ ] Testing phase
    1. [ ] Functional testing
    2. [ ] Use-case testing
4. [ ] Write the formal doc: master-manual.md
5. [ ] Celebrate!!! ^-^

## **Rough Idea of How the System Works and What We Have Left**
- [ ] A raw vocab module that defines vocab and relation between words.
- [ ] An algorithm to merge >= 1 raw vocab modules into a JS-style object.
- [x] An algorithm to turn the JS-style object into words.

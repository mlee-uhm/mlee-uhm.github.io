---
layout: essay
type: essay
title: "Design Patterns"
date: 2024-12-05
published: true
labels:
  - Design Patterns
  - Application
---

<img width="100px" class="rounded float-start pe-4" src="../img/igniting/paintbrushes.jpg">

### WHAT'S THAT?
When I was first asked "What is a design pattern?" I was unable to answer. I have been coding for over three years at this point, but I never in my life have I heard about a 'design pattern". However, after asking ChatGPT what a design pattern was and doing some additional research on my own, I realized that the so called "design pattern" was just a fancy term to somethings I've done in my code before. 

For example, one "design pattern" is an iterator. An iterator is a tool used to iterate (hence the name iterator) across a collection of items. Your items might be stored in an array, but it could also be stored in a different data structure like a tree. As software engineers, we know that there are different ways to iterate through an array and trees. We can use also use different ways to travel through a tree such as depth first search and breadth first search.

So how do iterators solve this problem? An iterator is something we use to go to the next item in a collection. Depending on what type of data structure we are trying to traverse through and how we want to traverse through it, the iterator returns the next item in the collection.

Another example is a factory. A factory is a pattern used to generalize more specific classes. For example, say you created a zoo in your code. Since you just opened your zoo, there is only one animal in your zoo, which is an elephant. But what happens when you want to add more animals in your zoo, since no one wants to go to a zoo with just elephants? You could write the code for another animal like a lion, but as we adding more animals we would have to keep doing the same thing. This leads to two problems. The first being that this is repetative and as software engineers we don't want to be repetative. The second is that this makes the code progressively more messy as we add more animals. 

So how does a factory solve this problem? A factory is like a superclass for more specific classes. Lets take at our zoo example real quick. Instead of creating a class for each of the animals, it is more practical to make a superclass called "Animal", with general functions that can be applied to all animals such as "sleep". Then make a subclass of a the "Animal" class for each of the specific animals with more specific functions that are specific to that animal.

### OKAY? YOU STILL HAVEN"T ANSWERED THE QUESTION


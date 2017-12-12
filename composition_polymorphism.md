# Polymorphism & Composition Homework - Quiz

# Polymorphism

1. What does the ___word___ 'polymorphism' mean?

Poly = many
Morph = forms


2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.

It means an object can act as an instance of multiple classes, depending on the situation.

Given the rigidity in terms of specifying exactly what an ArrayList contains in Java, polymorphism enables us to store different objects within that array, provided each object shares a common interface.


3. What can we use to implement polymorphism in Java?

- instanceof & super/subclasses
- interfaces


4. How many 'forms' can an object take when using polymorphism?

As many as you like if you want to go crazy with interfaces...


5. Give an example of when you could use polymorphism.

Storing various different types (sub-classes) of VEHICLE (super-class) in the same ArrayList.



# Composition

6. What do we mean by 'composition' in reference to object-oriented programming?

Enables us to choose from a set of behaviours.


7. When would you use composition? Provide a simple example in Java.

If we have the same method across multiple classes that behaves slightly differently. We would prefer to be choose from a group of behaviours.


8. What is/are the advantage(s) of using composition?

We can easily interchange between a set of behaviours depending on the requirement.


9. What happens to the behaviours when the object composed of them is destroyed?

They are all destroyed along with the object
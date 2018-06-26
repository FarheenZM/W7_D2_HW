Polymorphism & Composition Homework - Quiz

* Polymorphism

1. What does the word 'polymorphism' mean?
    Polymorphism means multiple forms or many shapes.

2. What does it mean when we apply polymorphism to OO design? Give a simple Java example.
    It means an instance of a class can also be treated as another class at the same time.
    e.g. A Person can be a Student and at the same time can be a Friend or a football Player, so the same thing can be represented as different classes.

3. What can we use to implement polymorphism in Java?
    Polymorphism can be implemented using both abstract classes and interfaces.

4. How many 'forms' can an object take when using polymorphism?
    An object can have many forms, that of the classes it is extending or interfaces it is implementing and itself.

5. Give an example of when you could use polymorphism.
    Suppose you want collections of different shapes & want to call some method - say area() on each one. Instead of making individual arrays of each different shape, you can make one array of the abstract class Shape. Where each different shape like circle, square, rectangle etc extends the abstract class Shape which will have the common method area().

* Composition

6. What do we mean by 'composition' in reference to object-oriented programming?
    Composition means an object is made up of, or composed of other objects.

7. When would you use composition? Provide a simple example in Java.
    Whenever there's a HAS-A relationship between objects.
    e.g. A book has pages so a Book class will be composed of a collection of Pages.

8. What is/are the advantage(s) of using composition?
    When we assign an object as a composition of another object, it's ownership is also passed to that object.
    Also we can get the behaviours/functionality of other object into the composed objects.

9. What happens to the behaviours when the object composed of them is destroyed?
    They also get destroyed.

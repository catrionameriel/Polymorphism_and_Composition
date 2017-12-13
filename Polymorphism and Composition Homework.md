# Polymorphism & Composition Homework - Quiz

# Polymorphism

- What does the ___word___ 'polymorphism' mean?

  It essentially means that something can take on more than one form. Polymorphism allows us to be more scalable with our methods and flexible with which types we pass in.

- What does it mean when we apply polymorphism to OO design? Give a simple Java example.

  We allow our code to take in many types rather than only one. You would do this by referring to the parent class or interface rather than the child class when passing in parameter of creating a new ArrayList. For example you could refer to the parent class Cheese and then pass in a particular instance of a cheese such as Brie. This wouldn't allow you to call the Brie class methods but any method that was created in the Cheese class.

- What can we use to implement polymorphism in Java?

  Interfaces, abstract classes and superclasses.

- How many 'forms' can an object take when using polymorphism?

  It can take an infinite number of forms.

- Give an example of when you could use polymorphism.

  See above.




# Composition

- What do we mean by 'composition' in reference to object-oriented programming?

  Composition allows us to design our program so that you are able to pull in another class and it's properties and use them. In composition, the relationship between the two classes are dependent.

  Compose or design our code using the behaviours of classes.

- When would you use composition? Provide a simple example in Java.

  You would use composition when many different classes contain the same method that may act in a different way. When composing we don't care how those classes enact the method as long as they give back what we want. For example if we had a Shop class, we could pull in a interface of Stock that contain lots of different Clothes classes but which all have the tryOn method. We can then implement that method in our Shop class. The clothes cannot exist without the Shop though.

- What is/are the advantage(s) of using composition?

  It means you can use the methods and properties of another class in the class you are in which means that more methods are available to you and so you can have more functionality.

- What happens to the behaviours when the object composed of them is destroyed?

  Those behaviours are destroyed too.

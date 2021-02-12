# COMP1130 Assignment2
For this assignment we create a collection of fruit. 

# Objectives
* Learn about Classes and Objects 
* Practice creating methods
* Understand the difference between static and non-static vatiables
* Practice using Git and GitHub to collaborate on projects

# Instructions

* Choose a fruit to create a class for. **First check the list of pull requests** to this repository to make sure nobody else has already picked the same fruit. Let's assume you picked apple. In this case you should create the class Apple.java and AppleDriver.java. Ofcourse your fruit will be a different one so name your classes according to this patten: Fruit.java and FruitDriver.java
* In your version of Fruit.java class implement the following:
  * A private variable `color` which is a `String` type, and it's initial value is empty string `""`
  * A static private variable called `count` which is initialized to `0`
  * A private variable `weight` of type `float` which is initialized to `0.0`
  * One constructor that accepts two values: `color` and `weight` and sets the private variables color and weight according to the input values
  * In the constructor increment the value of count by 1
  * A method called `toString()` that returns a statement such as this: "This instance of Apple is red and it is 0.55lb. So far you have created 3 apples"
* Create the driver class with the name of your fruit. For example, if you picked Apple, your driver class should be called AppleDriver.java. In the driver class implement the following:
  * Create an instance of your fruit and print the result of it's `toString()` method
  * Create two more instances of your fruit and print the `toString()` output of the third instance
  
# Submission

* Fork this repository: https://github.com/arasbm/comp1130-assignment2
* Clone your fork of the repository onto you computer (for example you can use GitHub Desktop for this)
* Add your java files to the repository folder and complete them. Make sure to pick a fruit that is not picked by anyone else yet! The fruit names will be first come first serve. So the first pull request that picks a particular fruit is the only one that makes it into the repository
* Make sure your Java files compile. Run and test your driver class
* Commit your changes which should include exactly 2 Java file and no folders
* Push your commits to your fork
* When your changes are complete, go to your fork on GitHub and from there create a Pull Request to send your addition to the main repository here that you
started with
* Submit a link to your pull request on Moodle to complete the submission process

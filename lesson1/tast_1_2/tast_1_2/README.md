Homework Task: Implementing Polymorphism with Animal Hierarchy in OOP

Objective:
This homework will deepen your understanding of polymorphism in Java by implementing an animal hierarchy and using it to tell stories about different animals.
You’ll create an inheritance structure where different animals exhibit unique behaviors, but all share common functionalities.

Task Description:

You are tasked with creating a simple animal simulation system where different types of animals can make sounds, describe their kind, and provide a brief description of themselves.
You will demonstrate polymorphism by having a common superclass or interface that all animals extend or implement. Additionally, you’ll create a class that tells a story about each animal.

implement. Additionally, you’ll create a class that tells a story about each animal.

Requirements:

1.	Define an Animal Abstract Class:
   - The Animal abstract class should declare the following methods:
   - void makeSound()
   - String getKind()
   - String getDescription()
2.	Create at least three concrete animal classes: Dog, Bird, Fish
  - Each class should:
  - Extend the Animal class.
  -	Implement the methods from Animal.
  -	Each animal should have specific behaviors. For example:
  -	Dog: Barks and returns “Dog” as its kind.
  -	Bird: Chirps and returns “Bird” as its kind.
  -	Fish: Gurgles and returns “Fish” as its kind.
  -	The getDescription() method should return a brief description of the animal, including its name, kind, and any unique characteristics.
3.	Create the AnimalStory Class:
  - The AnimalStory class should have a method public void `tellStory(Animal animal)` that takes any animal as an argument.
  - This method should tell a story about the animal by calling its makeSound(), getKind(), and getDescription() methods.
  - The story should include the animal’s sound, kind, and description in a cohesive narrative.
4.	Implement Main Method:
  - In the Main method, create a list or array of Animal objects, including instances of Dog, Bird, Fish, and any other animals you wish to add.
  - For each animal in the list, create an instance of AnimalStory and call the tellStory() method to tell the animal’s story.

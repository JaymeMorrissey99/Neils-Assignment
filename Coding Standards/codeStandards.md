# Coding Standards

## What Are Coding Standards?
Coding Standards are a set of guidelines, best practices, programming styles and conventions that developers adhere to when writing sources code for a project. All bug software companies have them enforced.

A coding standard document tells a developer how they should be writing their code. Instead of every developer writing in their own preferred style, they write all code to the standards outlined in the document.

This makes sure that all large projects are coded in a consistent style and ensures easier readability and avoids confusion between developers.


## Advantages of Implementing Coding Standards
- Offers uniformity to the code
- Enables the create of reusable code
- Makes errors easier to detect.
- Improves readability, makes code easier to maintain
- Improves programmers efficiency, helps generate faster results

## Helps Collaboration
As much as you might like coding by yourself, there comes a time when you will have to share your production with others. There’s also the possibility you will have to look at their code — especially working in a team, where second opinions are vital to a great-working product. This is when you’ll realize that not everyone writes their code the same way, and you’ll start to think everyone but you is doing it wrong.

## Writing Code that’s up to Coding Standards
Coding Standards aren’t a clear-cut thing, as everyone has a different idea about them. These can differ between coding languages. There are a few basics everyone should follow though.

## Formatting
Make sure you make the appropriate indentation, add proper amounts of whitespace and continue on new lines to ensure your code is readable. Take naming conventions into account when creating new files.

## Portability
It’s extremely important that your code is written in a way so it’s easily moved between platforms - no hardcoded values - these would break when used in other platforms.

## Modularity
Try and write code that’s usable by itself and doesn’t rely on anything written by someone else. These dependencies can break easily.

## Style Guide
If you work as part of a team, consider creating a style guide that leans heavily on common code conventions. Consistency is always more important than following the rules.

## Naming Classes
The name of a class should purely be a noun. A class represents an entity in a software application. A class should not consist of more then one word. An example: naming a class “Car” instead of DrivingCar.

## Naming Interfaces
By convention, the first letter of an interface should be capital. Interface names should ideally be adjectives and should generally end with the prefix “able”.
For example, adding onto the “Car” class. A car can be converted into a different vehicle - Motorbike, Truck etc. The “Car” class should implement an interface called Convertible. This interface would contain methods that contain code to convert the Car class instance to another vehicle type instance.

## Naming Methods
Methods refer to some sort of functionality performed by the object of the class that contains that method. Logically, a method name should be a verb. A method should be readable enough that it conveys the functionality that it actually encapsulates.
Method names in Java are written in camel case - the first letter of the first word is in lowercase and the first letter of the remaining word in method name is capital.
For example, a method for the Car class would be called startCar, instead of Start or StartCar.

## Naming Attributes/Member Variables
Attributes and member variables should be named singular nouns. For example, a Car class can have several attributes/variables. These can be called names such as “name”, “model”, “registration” etc.

## Using Getters/Setters
Attributes/Variables of a class should never be publicly exposed. Accessors (Getters) and Mutators (Setters) should be used instead.
Accessors and Mutators should be used to get and set the values of the attributes of a class.
Accessors and Mutators are used to force data encapsulation which is one of the three basic pillars of object oriented programming with polymorphism and inheritance being the other two



## Article/Blog Links

https://blog.fossasia.org/why-coding-standards-matter/

https://www.browserstack.com/guide/coding-standards-best-practices

https://blog.codacy.com/why-coding-standards-matter/

https://blog.udemy.com/java-coding-standards/

https://www.acromedia.com/article/coding-standards-and-development-a-general-overview

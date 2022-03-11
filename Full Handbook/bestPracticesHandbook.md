# **Best Practices Handbook**


# **Introduction**

This handbook was designed to guide developers while estimating tasks for the Sprint Backlog, coding standards and how to adhere to them while developing code and how code should be reviewed before it's pushed to the remote repository.

<p>&nbsp;</p>

# **Task Estimation**

Task Estimation is the Scrum technique used to estimate the length of time a piece of work will take to complete.

The objective is to estimate the amount of time a user story will take to complete based on the priority, complexity or scale of a story and by the time box of the Sprint.

Story Points are the designation given to the amount of time to be allocated to a user story. Story Points are used to understand the relative levels of effort for a user story in comparison to other user stories.

It is important during task estimation to calculate the amount of work the team working on the sprint can achieve during the timebox of the sprint.

To calculate the number of story points a team can complete during a sprint you add the number of days each team member is available during the course of the sprint. i.e. Over a two week sprint there are ten working days (Mon - Fri). If there are 6 team members the team has a capacity of 60 story points. However if there are events such as PTO, training, scheduled appointments or planned company days the capacity should be adjusted.

It is important to remember that the figures given for each user story are an estimate and shouldnt be considered as cast in stone, as the user story is developed there may be additional work required as a result of the changes being made.


## **Best Practices for Task Estimation:**

Task Estimation for the Sprint should take place during the Sprint Planning Meeting with the whole team being present at the meeting.

The Scrum Master should have the Sprint Backlog prepared for the Sprint Planning Meeting.

Story Points should be based on a numeric sizing system from 1 to 10 and should have a value of 1 Story Point is equal to 1 day of work.

The team should calculate their capacity before applying story points to user stories.

A typical Sprint should have a timebox of two weeks.

The team must come to a consensus on the number of story points allocated to a user story by means of voting. If an explanation for a suggested value is required by the scrum master, the team member should provide the relevant reasons for their suggested number of story points. 

If there are additional tasks that have been moved to the next sprint in the Product Backlog but the team has available capacity they should pull in additional user stories into the Sprint Backlog. 

If a user story has become more complex as it is being developed and the team member assigned to the user story feels that the estimate needs to be updated they should explain their reasons for this estimation change at the next Daily Stand Up Meeting. 

At the end of the Sprint the team must complete a Sprint Retrospective Meeting to examine their Sprint Velocity, this can help to improve task estimation in the future. 
This gives the Product Owner and other stakeholders an idea of the project duration. 


## **Article Links for further reading**

- https://www.tutorialspoint.com/scrum/scrum_estimation.htm

- https://www.scrum.org/resources/blog/what-scrum-says-about-estimates

- https://www.altexsoft.com/blog/story-points/

- https://scrumtrainingblog.wordpress.com/2014/11/26/scrum-tools-and-techniques-for-estimating-tasks-in-a-scrum-project/

- https://www.projectmanagement.com/blog/blogPostingView.cfm?blogPostingID=46054&thisPageURL=/blog-post/46054/Task-Estimation-with-Scrum#_=_


#
<p>&nbsp;</p>


# **Coding Standards**

## **What Are Coding Standards?**
Coding Standards are a set of guidelines, best practices, programming styles and conventions that developers adhere to when writing sources code for a project. All bug software companies have them enforced.

A coding standard document tells a developer how they should be writing their code. Instead of every developer writing in their own preferred style, they write all code to the standards outlined in the document.

This makes sure that all large projects are coded in a consistent style and ensures easier readability and avoids confusion between developers.


## **Advantages of Implementing Coding Standards**
- Offers uniformity to the code
- Enables the create of reusable code
- Makes errors easier to detect.
- Improves readability, makes code easier to maintain
- Improves programmers efficiency, helps generate faster results

## **Helps Collaboration**
As much as you might like coding by yourself, there comes a time when you will have to share your production with others. There’s also the possibility you will have to look at their code — especially working in a team, where second opinions are vital to a great-working product. This is when you’ll realize that not everyone writes their code the same way, and you’ll start to think everyone but you is doing it wrong.

## **Writing Code that’s up to Coding Standards**
Coding Standards aren’t a clear-cut thing, as everyone has a different idea about them. These can differ between coding languages. There are a few basics everyone should follow though.

## **Formatting**
Make sure you make the appropriate indentation, add proper amounts of whitespace and continue on new lines to ensure your code is readable. Take naming conventions into account when creating new files.

## **Portability**
It’s extremely important that your code is written in a way so it’s easily moved between platforms - no hardcoded values - these would break when used in other platforms.

## **Modularity**
Try and write code that’s usable by itself and doesn’t rely on anything written by someone else. These dependencies can break easily.

## **Style Guide**
If you work as part of a team, consider creating a style guide that leans heavily on common code conventions. Consistency is always more important than following the rules.

## **Naming Classes**
The name of a class should purely be a noun. A class represents an entity in a software application. A class should not consist of more then one word. An example: naming a class “Car” instead of DrivingCar.

## **Naming Interfaces**
By convention, the first letter of an interface should be capital. Interface names should ideally be adjectives and should generally end with the prefix “able”.
For example, adding onto the “Car” class. A car can be converted into a different vehicle - Motorbike, Truck etc. The “Car” class should implement an interface called Convertible. This interface would contain methods that contain code to convert the Car class instance to another vehicle type instance.

## **Naming Methods**
Methods refer to some sort of functionality performed by the object of the class that contains that method. Logically, a method name should be a verb. A method should be readable enough that it conveys the functionality that it actually encapsulates.
Method names in Java are written in camel case - the first letter of the first word is in lowercase and the first letter of the remaining word in method name is capital.
For example, a method for the Car class would be called startCar, instead of Start or StartCar.

## **Naming Attributes/Member Variables**
Attributes and member variables should be named singular nouns. For example, a Car class can have several attributes/variables. These can be called names such as “name”, “model”, “registration” etc.

## **Using Getters/Setters**
Attributes/Variables of a class should never be publicly exposed. Accessors (Getters) and Mutators (Setters) should be used instead.
Accessors and Mutators should be used to get and set the values of the attributes of a class.
Accessors and Mutators are used to force data encapsulation which is one of the three basic pillars of object oriented programming with polymorphism and inheritance being the other two



## **Article Links for further reading:**

- https://blog.fossasia.org/why-coding-standards-matter/

- https://www.browserstack.com/guide/coding-standards-best-practices

- https://blog.codacy.com/why-coding-standards-matter/

- https://blog.udemy.com/java-coding-standards/

- https://www.acromedia.com/article/coding-standards-and-development-a-general-overview

#
<p>&nbsp;</p>


# **Code Reviews**

## **What is a Code Review?**

A code review is a common software quality assurance activity that involves reading and evaluating the source code of a program or feature. Code reviews can be carried out while the author is in the process of writing it or upon its completion. At least one of the people performing the review must not be the code’s author.Code reviews are also sometimes referred to peer reviews.

## **Why perform a Code Review?**

- Ensures uniform design and implementation - Performing regular code reviews promotes a consistent coding style which increases code readability and makes it easier for someone who may join in on the development process to understand what has been done so far. If there are multiple individuals working on a project , the different styles may clash and the code can quickly become messy and unorganized which can affect its functionality.

 - Guarantees quality code that meets requirements - A team of developers may have different interpretations of the projects  requirements.Performing regular reviews of each team member's work can make sure that all team members stay on track and aren't spending valuable time working on something that isn't required or necessary.

 - Optimizes performance - Junior developers on new team members may not be aware of code code optimization techniques used by the team. The peer review process gives them an opportunity to improve their coding skills and thus the performance of their code.

 - Facilitates team learning - Sharing different techniques and technologies between team members can be an efficient way of overall improving the quality of the project. Regardless of seniority or experience , each team member may have something to positively contribute to the project that other members may not know about.

- Minimizes the impact of mistakes - Anyone who has spent time coding has experienced migraines or strained eyes from sitting , looking at their work too long. Code reviews offer a fresh set of eyes to analyze the code and eradicate any bugs before the problem gets out of hand. This ensures the project can progress more efficiently.


## **How to perform a code review?**

- Author self assessment - Ensure the owner has read through and left comments in the source code before submitting to the team. This can minimize defects and save time.

- Define quantifiable outcomes - When clear goals are set , it increases each member's accountability. Avoid vague statements such as “fix bugs”

- Create a system to record outcomes- Quantifiable metrics or data is what is needed in order to assess how effective the team code review process is.

- Have set time allocated - Make sure sufficient time is given for the review process .Typically a code review should not be longer than 1-1.5 hours. Its should be done slowly so details are not missed.

- Review all project documents - Project requirements and design documentation should also be reviewed so that all team members are clear on what that assignment is asking. 

- Take regular breaks - Take breaks every 20-30 minutes. You should not review more than 300-500 lines of code an hour.

- Ensure identified bugs are fixed - All defects that are identified must be fixed as soon as possible. 
 
-  Use the opportunity to improve the skill of all members-
Code reviews are a great opportunity for each member to expand their knowledge , correct their bad habits and further their review capabilities.

- Don't take the back seat - Trust your team and don't make life harder by over analyzing their code and work through the process.

- Carry out smaller reviews at regular intervals - If the team is aware that their code will be reviewed frequently , they will be more inclined to review it themselves before its submission.

- Utilize code review tools - This increases efficiency and accuracy and optimizes the time spent by your team members reviewing the code.

- Use checklists - By using checklists like this one , remind the reviewer and author on what to be looking out for while conducting a code review which will improve their personal coding abilities.

## **Do’s and Don'ts of code reviews**

## **Author**

## Do:

- Be polite
- Be thankful
- Clarify any solutions you don't agree with or don’t understand directly.
- Leave explanations where suitable for code that is complex and or spans multiple pages or classes.
- Have descriptive , meaningful commit messages.
- Commit your changes after the code review to show the team what has changed.
- Answer as many comments as possible and give thanks when it's due.
- Acknowledge comments even if you don't agree with them.

## Don’t:

- Take comments to heart. It is not personal.
- Insult people.
- Assume anything.
- Misinterpret comments -If comments seem personal or insulting , take a step back and read it again.
-  Make jokes or be sarcastic
- Shift blame to others - avoid “I copied this from _____ “ or “He/She did it this way so I did too”. 
- Strive to improve


## **Reviewer**

## Do:
- Be polite , helpful and humble.
- ”If it's not broke don't fix it” - if the solution isn't wrong then leave it.
- Ask questions when you are unsure of something.
- Give praise where it's due - Make sure you are recognising the good code and not just the bad code.
- Use checklists - This will speed up the process , for example: (1)check style ,2) naming convention ,3) test cases ,etc )
- Write comments that you would like to see on your own code.
- Make sure you put in sufficient time, the project's success depends on all members including you.


Here is some nice advice from Håkon Åmdal, self described as a Digital nomad and Software Engineer in Spacemaker AI. 

“One of my most effective tricks in code reviews is to replace all occurrences of «I»/«me» and «you» with «we»/«us». Such a small trick changes the attitude from «someone is scrutinizing and criticizing my work» to «I am getting feedback such that my team can ship the best possible services and apps possible!».”

## Don’t: 

- Use words like always or never.
- Don’t insult people
- Use jokes or sarcasm as they can be misinterpreted.
- Assume anything.
- Blame team members.
- Leave negative comments such as “this is wrong” , “do it this way”


## **Articles links for further reading:**

- https://www.brightspot.com/learn/articles/5-reasons-why-the-code-review-process-is-critical-for-developers#:~:text=Code%20review%20helps%20give%20a,and%20identifying%20errors%20is%20great.


- https://smartbear.com/learn/code-review/guide-to-code-review-process/

- https://betterprogramming.pub/the-dos-and-don-ts-of-code-reviews-77032ba3a30c

- https://www.michaelagreiler.com/code-review-pitfalls-slow-down/

- https://stackoverflow.blog/2019/09/30/how-to-make-good-code-reviews-better/
  
#
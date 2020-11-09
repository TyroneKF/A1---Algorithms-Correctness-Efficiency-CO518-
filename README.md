# A1-Algorithms-Correctness-Efficiency-CO518-
Second Year Module 

## Briefing Of The Assignment 
![Capture](https://user-images.githubusercontent.com/74104140/98492434-bd51e400-222f-11eb-8840-87916f7fd1ee.PNG)

In this project there is an abstract parent class called IntSet which can have the offspring of; 

• An Empty set object (a set with no values)
• A singleton set is a set with  only one int value in it's set
• A tree set is a set which has a left and right branch which can  attach other objects to it's branches being other: tree objects, empty set objects and  singleton objects attached to itself.

The process of creating a tree starts off with an empty set object and once a value is added to that object this creates a singleton set with that value. Lastly, once a value is added to a singleton this then creates another singleton which both objects are passed onto a tree object. 

A tree works essentially with the idea of abstraction whereby the only important information is the ending objects on the end of a tree branch being a singleton or an empty set. The singleton values inside a tree initially are halved as they are stored on a branch, the left branch holds even numbers and the right branch holds odd numbers. 

A tree branch cannot have two singleton values on one branch leaf so eventually these 2 numbers will need to be continously halved by creating new trees until these numbers are stored on differen't branches being one of them ends up being even and the other is odd.

Each time a new object is created it must be immutable therefore, after adding to any object this program must return a fresh new object.

## What is inside the repository? 
In this repository there is;

• An assignment brief which may be a word doc, pdf.

• A BlueJ version of project in a Zipped Folder.

• A Jar file of the project.

These projects were originally created in BlueJ which may mean you might have to download Bluej to view the files. However, there is a Jar file in the folder which can be used to open, extract and view the code by using certain softwares.

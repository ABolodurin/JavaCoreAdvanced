# JavaCoreAdvanced
___
**JavaCoreAdvanced** -  A set of tasks for an advanced Java core course.

Minor tasks during the project:
- practical experience working with GIT
  - forks
  - pull requests
  - merge
  - commits
- improving code style

## Description of tasks:


### Lesson1. OOP
- Create classes ```Dog```, ```PetCat```, ```Tiger```, ```Animal```
- Animals can ```run``` and ```swim```. As an argument, each method is transmitted length
obstacles.
- Each animal has restrictions on actions
  - for the run:
    - cat - 200
    - dog - 500 
  - for the swim:
    - cat - can't
    - dog - 10
  
  The result of the action will be printied in the console.
- Create one array with animals and force them to run a distance and
swim.
- (adv)Add the calculation of the created pet cats, tigers, dogs, and animals.

___
### Lesson2. OOP
- Create three classes ```Humman```, ```Cat```, ```Robot``` that are not inherited from one class.
These classes should be able to ```run``` and ```jump```(printing in the console).
- Create two classes ```RunningTrack``` and ```Wall```, when passing through which, participants
must perform the relevant actions(run or jump), and the result should be printed in the console(successfully ran, could not run, etc.).
Obstacles have ```length```(for a track) and ```height```(for a wall), participants have restrictions on running and jumping.
- Create two arrays: with participants and obstacles, make all participants go through all obstacles. 
If the participant could not go through one of the obstacles, then he does not go further.

___
### Lesson3. Exceptions
- Create Exceptions: ```MyArraySizeException``` (wrong size) and
```MyArrayDataException``` (wrong data in the cell)
- Write method with one argument(4x4 String[][] array). If an array is of a different size, you need to throw an exception ```MyArraySizeException```.
- The method passes through all elements of the array, transforms data to int, and calculaties ```summ``` of all elements.
If the transformation failed in some element of the array(for example, in the cell lies a symbol or text instead of a number), 
```MyArrayDataException``` must be thrown. The exception should contain detailing, which cell lies the wrong data.
- You need to call the resulting method in ```main()``` and handle possible exceptions ```MyArraySizeException``` and ```MyArrayDataException```.

___
### Lesson4. Generics and collections
- Write a method that changes two elements of an array in places
- Write a method that converts an array into an ```ArrayList```
- Task:
  - Write classes ```Fruit``` -> ```Apple```, ```Orange```
  - Write ```Box```, which can contiain fruits. Each box can contain only one type of fruit.
  - For storage of fruits inside the box, it is allowed to use ```ArrayList```.
  - Write a method ```getWeight()```, which calculates weight of the box. Set the weight of one
	fruit: for apple 1.0f, for orange 1.5f. 
  - Inside the class ```Box```, write method ```compare``` that allows you to compare the current
	box with the one that will be set as an argument. This method should return true when the weight of two compared boxes is equal. 
	Comparing boxes with different types of fruits should be possible. 
  - Write a method, which allows pouring fruits from the current box to another(all objects move to another, and the current box becomes empty). 
	The rule of the same type of fruit is observed. 
  - Don't forget a method for adding fruit to the box. 
  
___
### Lesson5. Collections p.2
- Create an array containing a set of words (from 10 to 20 words, some words should be repeated). 
  Find and print a list of unique words in the console, and calculate how many times each word is repeated in the array.
- Write a class ```TelephoneBook```, which stores a list of surnames and telephone numbers. This telephone book allows:
  - ```add()``` posts
  - Search a phone number by last name using the ```get()``` method. 
  It should be noted that several numbers can be stored under one surname(in the case of namesakes). 
  When such a surname is requested, all correct numbers should be displayed.

___
### Lesson8. Stream API
- Create an array containing a set of words. Find the most commonly repeating words using **Stream API**. 
- Create an array containing ```Employee``` objects(name, age, salary), and calculate average salary.
  Write a method, which finds N eldest employees, and prints in the console message "N eldest emloyees: name1, name2,...nameN"

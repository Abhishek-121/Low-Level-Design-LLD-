# Low-Level-Design-LLD
Write the notes based on understanding from the learning content.

	#Strategy Design Pattern
	
	• Is-A relation is a inheritance only.
		○ Eg: Car is a Vehicle, Bike is a Vehicle etc.

Why we need Strategy Design Pattern ?

	• When there are multiple child of a class and overriding the method defined in base class in same manner as that of other child class then it would led to duplicacy of code.
		Eg: When child class using their own capability instead of using it's parent and other child at same level have the same as of their neighbour child then code duplication occurred and it will continue if there is multilevel hierarchy then we can't do the Code Reusability.

Solution 

We will create a Drive Strategy Interface and it has 2 or n number of methods like normal_drive, special_drive, xyz_drive etc. and instead of defining drive method in Base class, we will create object of Drive Strategy Interface in Base class and now child of this Base class will call the respective method of Drive Strategy Interface.


![image](https://github.com/Abhishek-121/Low-Level-Design-LLD-/assets/56202291/ab3e3be6-9e8c-4fcd-8453-cb96336673dc)


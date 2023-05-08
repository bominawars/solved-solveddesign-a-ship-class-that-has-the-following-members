Download Link: https://assignmentchef.com/product/solved-solveddesign-a-ship-class-that-has-the-following-members
<br>
Design a “Ship” class that has the following members:– A member variable for the name of the ship as a string.– A member variable for the year that the ship was built as a string.– A constructor and appropriate accessors and mutators.– A virtual “print” function that displays the ship’s name and the year it was built.

Design a “CruiseShip” class that is derived from the Ship class. The CruiseShip class should have the following members:– A member variable for the maximum number of passengers as an int.– A constructor and appropriate accessors and mutators.– A print function that overrides the print function in the base class. The CruiseShip class’s print function should display only the ship’s name and the max number of passengers.

Design a “CargoShip” class that is derived from the Ship class. The CargoShip class should have the following members:– A member variable for the cargocapacity in tonnage as an int.– A constructor and appropriate accessors and mutators.– A print function that overrides the print function in the base class. The CargoShip class’s print function should display only the ship’s name and the ship’s cargo capacity.

Demonstrate the classes in a program that has an array of Ship pointers. The array elements should be initialized with the addresses of dynamically allocated Ship, CruiseShip, and CargoShip objects. The program should then step through the array, calling each object’s print function.
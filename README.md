# TheNextCar
This project was created to make it easier to record travel tracks when we use a vehicle (car), the concept is like google maps

- Use of DoorController.cs
DoorController.cs is a class that is used to control and process the data provided by the Door.cs model. There are several functions, such as close() to close the door, open() to open the door, activateLock() to lock and unlock the door, isClose() and isLocked() to check the door is closed or not and check whether the door is locked or not.

- Use of Door.cs
Its function is to provide data that will be processed later by DoorController.cs, this class will return true/false according to the isClose() or isLocked() function.

- Interface Uses OnDoorChanged
Its function is to notify the changed status and security changed from the door, which will accept 2 parameters, namely the value and message in the form of a string.


# Python Object Attributes Lab

## Introduction
In this lab, we will practice using python decorators and instance methods to interact with our instance variables.

## Objectives

* Define Python classes
* Define instance methods that both read and write instance variables
* Use instance methods to create instance variables
* Practice using property decorators and 

## Defining Classes and Instance Methods

Define a passenger class in the passenger.py file in your directory. In this class, define methods that both read and write (get and set) a passengers `_first`, `_last`, and an `_email`, which will represent a passengers first name, last name, and email respecitively. The methods should be named `first`, `last`, and `email` and use the appropriate decorators. 

Next, write an instance method that returns the passengers fullname in all caps and call it `yell_name`. 


```python
passenger = Passenger()
passenger.first = "Jane"
passenger.last = "Doe"
passenger.yell_name() # "JANE DOE"
```

Great, we've filled out some functionality for our passenger class. Now lets do the same for a driver. Define a driver class in the driver.py file in your directory. Then define instance methods for a drivers first name, last name, rating, and miles driven. These attributes should be appropriately named with the leading underscore, (i.e. `_first`, `_last`, `_rating`, `_miles_driven`) and the coressponding getter and setter instance methods should be named `first`, `last`, `rating`, `miles_driven` and use the appropriate deocorators. 

Next, define an isntance method called `update_miles` that takes in an additional argument for the length of a ride. So, when a driver finishes a ride, it adds the new ride length to the driver's miles driven attribute and then returns the newly calculated `_miles_driven`.


```python
driver = Driver()
driver.first = "John"
driver.last = "Doe"
driver.rating = 4.9
driver.miles_driven = 100
# driver finishes a ride that was 37 miles long
# use the update_miles instance method here to update the driver's _miles_driven attribute
driver.miles_driven # 137
```

Awesome! Great work!

## Summary
In this lab, we practiced using attribute 

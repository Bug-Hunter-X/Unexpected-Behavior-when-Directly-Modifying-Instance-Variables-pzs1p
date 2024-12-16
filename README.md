# Unexpected Behavior when Directly Modifying Instance Variables in Ruby

This repository demonstrates a common issue in Ruby where directly manipulating instance variables using `instance_variable_set` can lead to problems.  It is generally best practice to modify an object's state through its methods, ensuring data integrity and encapsulation.
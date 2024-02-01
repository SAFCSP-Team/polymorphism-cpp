# Polymorphism

## Objective
In this project, we will learn to understand `Polymorphism` in C++.

## Problem

Create a `Bank` class that has a virtual function called `getRateOfInterest()` and apply the concept of polymorphism to perform the method in different 
 ways possible.

## Implementation

* Create a base class `Bank` that has a virtual function called `getRateOfInterest()`.
* Create derived Classes of `Bank` can be `SNB` and `SAB`.
* Each derived Classe has its way of calculating the rate of interest.
* The derived Classes can use the `getRateOfInterest()` function to find the rate for that bank.
* Create pointers of type Bank and assign them to objects of the derived classes SNB and SAB, call the `getRateOfInterest()` function through these 
  pointers.

```cpp
#include <iostream>

int main() {

    return 0;
}
```

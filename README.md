# AirPlane Seat Mapping Application

This application intends to plan a seat map of an airplane based on input of the size of plane and traveller request.

#Sample Input:
```
4 4
1W 2 3
4 5 6 7
8
9 10 11W
12W
13 14
15 16
```
```
Input File consists of total no of seats in a row and total rows in the first line
Consecutive Lines are passenger IDs coming in a group ( one line represents a group)
Passenger ID with a "W" indicates the passenger have a window seat preference
```
# Assumption
```
Total no of passengers in input file is equivalent to the no of seats in the airplane for simplification
Group seating will be given preference over window seating preference
If a customer is not allocated a seat, the satisfaction percentage decreases accordingly
```

# Unit Test
```
Test 1: Test for a 100% satisfied seat map plan provided to a set of passengers
Test 2: Test for an unsatisfied (less than 100%) seat map plan provided to a set of passengers
```

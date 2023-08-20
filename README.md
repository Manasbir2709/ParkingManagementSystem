# ParkingManagementSystem
## Introduction:

This system allows you to make your task to park the cars easy. 
Java is a popular programming language that is widely used for developing parking management systems due to its simplicity, versatility, and platform independence. This system analyses for an available space in parking area and on the basis of it gives the output to user. If all slots are full then it will simply tell the user to not park car in that particular area. It increments the available slots if any user removed his/her car from parking area and decrements slots if any user park his/her car. Overall, a parking system in Java provides a flexible and powerful platform for managing parking spaces, improving traffic flow, and enhancing the overall parking experience for drivers. By leveraging the strengths of Java, developers can create robust and scalable parking systems that meet the unique needs of their users.

 

## Explanation:
The Parking System we will build will be a simple console-based application that allows users to park their cars, removed their cars and view all parked cars. It presents a menu with four options: park a car, remove a car, view parked cars, and exit the program. It is very simple with coding point of view as it has only one java class in it. We need to import Scanner class and Array List class. Scanner class used to take input through the keyboard from user while Array List is used to make things simple for adding the cars and deleting them. User needs to provide total number of parking slots and then main menu will be displayed for further operations. In park car method, we will check for availability of slots. If slots are available then user will provide car license number and message will be displayed as “Car parked successfully”. In remove car method, we will check for number of parked cars if it appears as zero then process will not go further. By entering license number of parked car one can simply removed it. Inbuilt functions of Array List ‘add’ and ‘remove’ are used to add cars in array list and remove it from the array list, respectively. Along with the process of adding and removing the available slots will get decrement and increment accordingly. For displaying all parked cars we have used for each loop and displaying Array List named as parked cars. All these three methods have been called for particular case of switch case. 


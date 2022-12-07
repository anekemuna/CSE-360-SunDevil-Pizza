# SunDevil Pizza
SunDevil Pizza is a web application used by the students of Arizona State University to order their favourite pizzas online and get them on their doorstep in the quickest manner possible. This Application has three parts to it. 
The user part, the order processing agent part, and the chef part. 

## Build

### User Part
As mentioned, the user part is the part of the app used by the students to order pizzas, select the kind of pizzas they like, choose their favourite toppings, and finally placing the order. They can also track their order in the app. This app ONLY allows ASU students to place the order so it verifies if a student has the right ASU credentials before their order is placed and only in that case, the order status is set to ACCEPTED orelse its DENIED. 

### Order Processing Agent
The Order processing Agent also uses this app to ensure that the order is ready for processing and then updates the app so that the status of the order is now READY TO COOK.

### Chef
Once the order is ready to cook, chef starts preparing the food and updates it to COOKING. The Chef updates when the pizza is prepared and the order status changes to READY.

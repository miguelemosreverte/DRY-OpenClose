

![](https://i.imgur.com/1Zclh5K.png)

|   |   |
|:-------------:|:-------------:|
| ![](https://via.placeholder.com/543x1132/B0E0E6/ffffff?text=The+use+case) |  ![](https://imgur.com/OdZlidy.gif) |

 ![](https://via.placeholder.com/1080x1132/B0E0E6/ffffff?text=The+gif+you+just+saw+was+made+using+the+following+steps)
 ![](https://i.imgur.com/s7z3ZOT.png)

# Being the steps:
 1. the need for a new React Component is created by the client.
 2.  a new JSON => React Component transformer is made
 3. the new JSON => React Component transformer is exported via the index.js
 4. the new JSON => React Component transformer is taken into account by the pattern matcher.


 ![](https://via.placeholder.com/1080x1132/B0E0E6/ffffff?text=There+are+*two*+problems+with+the+steps+below)

 # Problem 1
 The JSON => React Component is too concrete.
 This violates DRY because the client could at some point ask for the button to have another icon, or be placed elsewhere in the UI.
 And maybe the developers would think of making another _too_ concrete piece of code to satisfy the client.

 # Problem 2
 The step number 2 is unnecesary, prompts the developer to adquire an habit of code revisiting, and most of all, it is an habit that ends up creating code that is not pretty to look at.


 |   |   |
 |:-------------:|:-------------:|
 | ![](https://via.placeholder.com/543x1132/B0E0E6/ffffff?text=Solution!+:D) |  ![](https://i.imgur.com/VcR2xZr.gif) |

 ![](https://via.placeholder.com/1080x1132/B0E0E6/ffffff?text=DRY)
![](https://i.imgur.com/t3whyme.png)


 ![](https://via.placeholder.com/1080x1132/B0E0E6/ffffff?text=OPEN-CLOSE)
![](https://i.imgur.com/t3whyme.png)

# Sometimes the first step towards good code is original code.
The code shown inb the last picture was using a library for pattern matching in JS.

This was making the code rigid, and to be able to obey Open Close the changes needed tho rewrite the module from scratch.

![](https://i.imgur.com/1MhLY8O.png)
# Because now, now we can start hacking away the boring parts
![](https://user-images.githubusercontent.com/9152392/44736541-e90ca780-aac5-11e8-98a6-85d5fe38d50a.png)



 ![](https://via.placeholder.com/1080x100/B0E0E6/ffffff?text=And+thats+how+I+automated+the+imports)
 ![](https://via.placeholder.com/1080x100/B0E0E6/ffffff?text=and+managed+to+leave+alone+the+engine) 
 ![](https://via.placeholder.com/1080x100/B0E0E6/ffffff?text=+when+adding+new+functionalities+as+plugins.)

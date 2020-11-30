# Exercise 8: Look at the Cards

This is an exercise for the coursera course [Introduction to C# Programming and Unity](https://www.coursera.org/learn/introduction-programming-unity)

### Problem 1 - Create a deck and tell it to print itself

Declare a **deck** variable and use the **Deck** constructor to put a new **Deck** object into the **deck** variable.

Tell the **deck** to print itself. Use the help documentation I provided to figure out which method to use.

Note: The deck prints itself from bottom to top, so the last card listed is at the top of the deck.

### Problem 2 - Tell the deck to shuffle and print itself

Tell the **deck** to shuffle itself and print itself. Use the help documentation I provided to figure out which methods to use.

### Problem 3 - Take two cards from the deck and print their ranks and suits

Take a card from the top of the deck and print its rank and suit. Use the help documentation I provided to figure out which **Deck** method to use to get the top card and which **Card** properties to use to print the rank and suit.

Take another card from the top of the deck and print its rank and suit.

Hint 1: The **Card** class doesn't expose a **Print** method, so you have to access a card's properties to print the required information. 

Hint 2: You haven't called a method that returns a value yet. Here's a good way to do that for this exercise:

`card0 = deck.TakeTopCard();`

The **DeckTakeTopCard** method returns a **Card** object. You need to save that object in a variable so you can access its properties.
 
## Installation
To install, follow these steps:

Via Downloading from GitHub:

Download this repository onto your machine by clicking the "Clone or Download" button or Fork the repo into your own Github account
Download and extract the zip file to a directory of your choice.  

Via command line:

`$ git clone https://github.com/puglisac/coursera-c-sharp-ex9.git`  

open Exercise9.sln in [Visual Studio](https://visualstudio.microsoft.com/) and click Run to start.

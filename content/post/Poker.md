---
title: "Project 1: Poker with Python"
date: 2018-06-28T20:12:32+01:00
draft: false
---
Welcome to my first blog post! Using Python, I have attempted to create a simplified game of poker. In this simple version of poker, each player is dealt 5 cards. The player with the highest card wins.  I will go on to explain what I have done in my script and improvements and additions I would make moving forward.  

I began by defining a function for my game so that it could be run by calling poker_game(). First, I created my deck. To do this, I made 2 lists: one for the value of the cards (values) and one for the suits of the cards (suits). Then I combined these lists to make a list for a full deck of 52 cards(deck). Additionally, I created a dictionary to give each card a rank so that eventually they could be compared (card dictionary). To do this I made a list of values that I was able to associate with each card (deck_value). For example, in my dictionary, a 2 of spades has a value of 1 while an Ace of spades has a value of 13. 

Next, I set up my user input. The user will first be prompted to enter the number of people playing which is stored as number_of_players.  Then, they are asked to enter a name for each player which is stored in a list (names). 

Each player is then dealt 5 cards using np.random choice() which are stored in a list called hands.  My loop prints the list of cards for each player. My next step would be to check each hand and pull the highest value card according to my dictionary. Then the highest card from each player’s hand could be compared. I would then print out the name of the winning player and their winning card. 

In addition to adding the necessary parts it would also be important to check for a tie. I could also improve my input options to make sure users enter the correct type of input and get informational warning messages without ending the program. I also think that I could create a better deck of cards that enables a more effective way to check for the winning card and implementing different classes would help improve this program. 

current build https://github.com/cgd3/poker-.git

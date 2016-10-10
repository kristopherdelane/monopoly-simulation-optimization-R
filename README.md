# monopoly-simulation-optimization-R
R code to simulate 100,000 dice rolls then find optimum dice rolls to start the game

Run the Simulation code to build 100,000 dice rolls around the Monopoly Board to see what spaces are landed on most often.

A few notes: There are more than 100,000 results because everytime you land on a Chance or Community Chest and then move to another space, both spaces are counted. Same goes for Landing on Go To Jail. Go to Jail and Jail are counted twice as one roll required both spaces.

The only thing missing in this code is when doubles are rolled thrice. It does not send you to Jail.

This is the simulation of 1 person doing 100,000 rolls of two dice. Not two people rolling 50,000 times or any other iteration.

Next run the Dice Optimization code. This will create a data frame with all possible dice rolls from (1,2) all the way to (6,6) (6,6) (6,6). 

It will then bring in the value for all 861 possible combinations of dice rolls based on the Rent value * the probabilty of landing on the space.

Rolling two dice will produce a Normal curve over a long enough timeline. For this reason the rent values of Electric Company and Water Works are 7(the most probable dice roll) times 4, per the card.

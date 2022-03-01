## How does Observer Pattern work

Observer Pattern follows too many relationships which are explained below,

For example, in your game, there is an instance when the player dies and after that elements change dynamically such as health bar is 0, death animation, game freezes, enemy win animation, etc. In order to accomplish all this, with the help of Observer Pattern we can, 

1. Using Subject we can broadcast the message that the player is killed 
2. Any object/observer can choose to listen/subscribe to the event
3. The list of Objects/Observers may something based on the message


![Alt](Images/2.png "Working of Subject and Observer")

This flow diagram gives you the visual representation of what we have explained above.

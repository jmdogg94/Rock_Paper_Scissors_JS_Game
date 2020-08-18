Rock Paper Scissors

Learning outcomes:
	
	•	Developed a basic JS version of rock/paper/scissors that lets a user specifiy their throw (rock, paper or scissors) and then tallies a score based on the                       outcomes.
	•	console.log the the players and computers choice’s, the score and a log a congratulations message for the winner. 
	•	Demonstrated use of functions and if statmemnts.

Improvement opportunities
	
	•	Error message if users input is not rock paper or scissors.
	•	Add elements to the web page itself to make playing the game easier.
	
conclusion

I completed this task over 2 days. On the first day I created an array to store the strings 'rock' 'paper' 'scissors', I then made a function called computerPlay(){} that would randomly pick one of the 3 words and use it as its 'turn'. I then made a function called playRound(){}. This function acted as a offical round of the game and it would take the computers randomly chosen hand and would take a window.prompt message as the user's turn. In the function I stated that if the players was x and the coputers was y display this message, player or computer wins. If the words were the same i.e. computer plays x and human plays x, the console will log a 'its a draw' message.

On the second day I had to make the game in to 5 rounds, that would log the winner of each round and the winner of the overall game. I found this really hard, i was confused on where to start. the previous day i was doing ok, i was obvioulsy googling stuff but I wasnt stuck for very long. On the second day I was getting stuck alot and everything that I was googling wasnt working quite the way I wanted it too, or not at all. I decided to look at the solutions on the odin projects website which were submitted by students. one users called "simalicrum’s" had a function at the bottom of his code called game(){} which I based my function off. I copied his function in to my code to see if it would work and it did. It didnt work perfectly, there were still weird errors but I managed to get everything to work. I had console.log() arguments and window.prompt() arguments that were logging twice, or I was logging the wrong argument, its hard to explain. But i managed to fix it. 

I then expanded on "simalicrum’s" code so my game would log what the player chose, the computers choice, who the winner was in a string and then the score of that round. Each round gets logged on the console like this, then at the end you get a final message of who won, or its a draw.

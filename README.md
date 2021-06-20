# CardGame
Cards game C# console application

# Please follow below instructions before running the applications:
1.	Solution contains 2 projects.
	*	CardGame - contains the care game application.
	*	CardGameTests	- contains the unit test cases.

2.	Game envirnoment :
		a.	Please run the application on Visual studio 2019.
		b.	Build mode : Debug
		c.	Solution platform : Any CPU
	
3.	Program.cs is the start file of the project.
	
4.	Number of players and Deck size can be modified inside Program.cs
		by changing the readonly variables.
	
5.	Game Rules :
		a.	Card game can have N number of players.
		b.	Card game can have N number of decks.
		c.	Cards in deck are equally distributed among all the players
		d.	If cards cannot be equally distributed among the players,
			additional cards(which cannot be equally distributes) are discarded from the game.
		e.	On each round, all players draw their top card from draw pile.
		f.	Player who draws the highest value card wins the round.
		g.	All the winning cards are added into player's discard pile.
		h.	If players draw pile is empty, then cards from discard pile is shuffeled
			and moved into the draw pile.
		i.	If a player has no cards in either draw pile and discard pile,
			then that player exits the game. Game will be continued among remaining players.
		j.	Game is played untill its left with only one player.
		h.	Last remaining player of the game is declared as the winner of the cards game.


Intent is to create a basic framework and Terminal Display allowing for the creation and automating of various Card games.

In order to accomplish this, we will need to create the following:
- [[Card]] Objects that contain the Suit and Value
	- Consist of two Properties:
		- Suit
		- Value
	- Must be Orderable
		- By Suit and By Value (If Both Suit > Value)
- Concept of a [[Deck]] (4 Suits with one of each Card, optionally with Jokers)
- Concept of a Game Deck (Consisting of 1 or more Decks)
	- A deck must be shufflable
- Concept of a [[Hand]]
	- Made up of n cards
	- Cards can be Added or Removed
- Concept of a [[Game]]
	- Made up of n Players
	- Has a Win condition
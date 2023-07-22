Three Properties
- Suit 
	- Hearts
	- Diamonds
	- Clubs
	- Spades
- Value:
	- Ace (Low)
		- Ace can be treated as two values
	- 2
	- 3
	- 4
	- 5
	- 6
	- 7
	- 8
	- 9
	- Jack
	- Queen
	- King
	- Ace (High)
- Is Picture Card
	- Indicates whether the card is a Jack, Queen, King or Ace as some games treat these differently

 ## Ordering
 ### By Value
 When ordering by Value we will treat each value as numeric with Ace being treated as a One. 

### By Suit
We will assign each suit a numeric value (likely via Enum) then order in that fashion

### By Both
When Ordering by both, the hand ought to be split by Suit, Ordered by Value within the Suit and then combined in suit order.
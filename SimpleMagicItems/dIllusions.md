An alias for using the Deck of Illusions.
This alias will track your remaining cards and pull a random or specific card.  It's possible to reset the deck or discard random or specific cards as well. Optionally the deck can be overridden per server and images added for each illusion.
 
**Drawing from the deck:**
`!dIllusions [card|illusion]` - Quotes aren't necessary. If no card is given a random card is drawn. The first time the deck is used it is automatically filled with all cards. If no card is available an error will be displayed instead.
 
**Example:**
`!dIllusions` - draw a random card 
`!dIllusions fire giant` - draw the fire giant
`!dIllusions "king"` - draw a king of hearts, diamonds or spades (in that order)
 
**Reset the deck:**
`!dIllusions [reset] -d [roll|"illusion"|"card"][...]` - Recreate a new deck. A rolled amount of random cards may be removed or a card with a matching illusion or card face. Here the text has to be quoted if it has spaces, but partial matching is supported. Multiple cards can be removed at once. Cards can also be discarded at any other time.
 
**Example:**
`!dIllusions reset -d 1d20-1` - Create a deck with all cards, but remove between 0 and 19 randomly selected cards.
`!dIllusions reset -d ace -d "king"` - Create a deck but remove all aces and kings. 
`!dIllusions -d 1` - Remove one random card from your currently remaining deck.
 
The deck can be customized with `!svar deck_of_illusions yourgvar-guid-1234-567890abcdef`. The default is `!gvar 3c73c64e-9975-4e9a-8dd0-6a7025e2122c`. It is possible, in your own private deck, to add "img":"<url>" for each card in the json. This image will be shown when that card is drawn. The optional size is also shown if given to help the players determine how big the illusion would be. The images for the default cards can be found with `!monimage <illusion>` if you own the license on beyond.
 
 
The code behind these aliases will be posted as available on my  [Github](https://github.com/TheReverendB/avrae-aliases)
#Kingdom

A two-player kingdom-building and battling card game, played with a standard 52-card deck.

Initial design by [Justin C. Rounds](http://justincrounds.org/) for his [One Game A Month](http://www.onegameamonth.com/) February entry.

##Requirements

+ A standard 52-card deck of playing cards
+ 1 six-sided die
+ At least 20 tokens (preferably more)
+ Two players

##Setup

Shuffle the deck. Each player is dealt seven cards, face-down, to form their *hand*. The remaining cards go face-down in a *draw stack* within reach of each player. Each player receives ten tokens which form their *treasury*. Remaining tokens, if any, go into a *stockpile* within reach of each player.

##Goal

The first player to build a complete *kingdom* wins the game. A *kingdom* is represented by one card from each suit, not counting face cards or aces, and one corresponding face card or ace for each suit, one of each type (one King, one Queen, one Jack, and one Ace).

###Sample Kingdom

<table>
    <tr>
        <td>A&spades;</td>
        <td>K&diams;</td>
        <td>J&clubs;</td>
        <td>Q&hearts;</td>
    </tr>
    <tr>
        <td>3&spades;</td>
        <td>7&diams;</td>
        <td>9&clubs;</td>
        <td>5&hearts;</td>
    </tr>
</table>

##Gameplay

###Start

Determine which player goes first, e.g. highest roll of the die. The first round, each player chooses two cards to discard from their hand, face-down, into the *discard pile*. Then, if they choose to do so, they may begin building their kingdom by placing cards, face-up, in front of them. The first card placed for each suit must **not** be a face-card or ace. For each card thus placed, the player must pay the number of tokens from their *treasury* equal to the number on the card, e.g. two tokens for a 2&spades;. These cards are referred to as *resource cards* because they represent the four different resources in each kingdom: *agriculture* (&spades;), *commerce* (&diams;), *military* (&clubs;), and *fealty* (&hearts;).

Face cards and aces can only be played **after** a card of the same suit has been placed. For example, if the player has a K&clubs; in their hand, they must place a &clubs; card **before** placing the K&clubs;. These cards represent the ruling class of the kingdom and are referred to as *ruler cards*. *Ruler cards* do not cost any tokens to place.

###Subsequent Rounds

After the first round, players alternate turns. At the beginning of the turn, the player draws a card from the top of the *draw stack*. If, after drawing this card, the player has more than **five** cards in their hand, they must discard card(s) of their choosing, so they retain no more than five cards.

Following the draw, the player rolls the die to determine the number of tokens they receive. The amount received is equal to the number on the die minus one, e.g. the player rolls a six and then takes five tokens from the *stockpile* and adds them to their *treasury*.

The player then proceeds to place cards, if desired, as before. Once the player declares they are finished, it becomes the other player's turn. Players take turns until one player completes their kingdom and wins the game.

In summary:

0. Player begins their turn by drawing a card from the *draw stack*, discarding as required so they have no more than five cards in their hand.
0. Player rolls the die and takes that number of tokens, minus one, from the *stockpile*.
0. Player places cards as desired, paying the face value of each card.
0. Player ends their turn.

If the player draws the last card in the *draw stack*, the *discard pile* is shuffled and becomes the new *draw stack*.

###Placing Rulers

*Ruler cards* may be placed only if their corresponding resource (i.e. suit) has already been placed. Only one of each type of *ruler card* may be present in the player's kingdom at any time, e.g. a player cannot place a Q&clubs; if they already have a Q&spades; in their kingdom. *Ruler cards*, unlike *resource cards*, do not require spending tokens to be placed. *Ruler cards* also require that at least one matching *resource card* be present, otherwise the ruler becomes *deposed* and is removed to the *discard pile*. The player needs to place one of each type of *ruler card* to complete their kingdom and win the game.

###Upgrading

Once a *resource card* has been placed, the player may choose to *upgrade* the resource by paying for and placing a card of higher face value on top of it. This can be done regardless of the presence of a *ruler card*. The player may continue to upgrade the resource provided they have the cards and tokens to do so. The upgrading card should be placed in an overlapping manner such that all the cards for that resource are visible to both players.

###Trouncing

A player may choose to use a placed card to *trounce* one of the other player's cards of the same *resource*, provided the face value of the trouncing card is higher, e.g. 10&diams; versus 8&diams;. Both the trouncing and trounced cards are removed to the *discard pile*. If the other player's resource has been upgraded, **only the highest value card of a resource can be trounced**, and only that card shall be removed. If the trounced card is the last card of that player's resource, and a corresponding *ruler card* is present, the ruler is *deposed* and removed to the *discard pile* along with the trounced *resource card*. Similarly, if the trouncing card is the last of that resource and a *ruler card* is present, the player must sacrifice the ruler in order to *trounce* their opponent's card.

##Release Notes

###2013.02.28

Initial release for playtesting.
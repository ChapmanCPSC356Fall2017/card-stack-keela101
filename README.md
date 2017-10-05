#Sean Keelan
#ID: 1928053
#keela101@mail.chapman.edu
#CPSC 356-01
#Assignment #1: Card Stacker
#Description: The following project includes three different layouts (linear,
relative, and frame) that each create an Ace of Hearts playing card in an
XML file (in this case, an Ace of Diamonds was created). Then, using one of
the aforementioned layouts, a stack of 52 cards, each of a different
of suits and values, would be created. The user clicks anywhere on the screen,
drawing (calling the pop() function) the card on the top of the deck. The
user can continue calling this function until the deck (the stack) is empty,
at which point the deck is shuffled and the stack is refilled.

#Notes: The following project is incomplete. Only a LinearLayout version
of a card was made, and stack functionality is non-existent. In the
RelativeLayout, the ImageView widgets were created, but were not placed in
proper positions. The FrameLayout has not been made.

The final solution would have used the RelativeLayout, and any suit icons
displayed in the middle of the card would be displayed as ImageView widgets.
Depending on the number value of the card, certain ImageView widgets would
have their visibility set to either 'gone' (so the invisible widgets do not
interfere with visible ones) or 'visible'. Face card suits would not use the
face card images.

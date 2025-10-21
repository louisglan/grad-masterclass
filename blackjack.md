# Blackjack

When you get ahead you will be building a blackjack command line game. Here is a reminder of the [rules](https://bicyclecards.com/how-to-play/blackjack). The rules are a little more complicated than you may realise so have a read through even if you think you know them. For now, only read up to "Signling Intentions".

## Instructions

Your task is to create blackjack in the terminal using only JavaScript. This coursework should force you to think about how to break a big problem down into smaller chunks. Here are your tasks:
- Install deno: open powershell and run `irm https://deno.land/install.ps1 | iex`. Deno is a modern (but less used) version of node that will allow us to easily get prompts in the command line. To run a js app with deno, in your terminal run `deno <app-name>.js`
- Create a new repository called "blackjack" and clone it. You can start coding now!
- Generate the deck (a list of 52 cards, represented by a digit and a letter e.g., 5C = 5 of clubs)
- Shuffle the deck (use Math.random to achieve this. It is not straightforward)
- Deal the user a hand
- Tell them how many points their hand is worth
- Deal one card to the dealer and show it
- Ask if the user wants to hit or stick (use the deno `globalThis.prompt()` method to get an input from the user). Remember you will need to use `deno <app-name>.js` to run the app with deno. 
- Tell the user their new hand
- If they are bust tell them they bust and lost. Otherwise ask them if they want to hit or stick
- Generate the dealer's hand. The dealer must follow a strict set of rules (see "The Dealer's Play" in the rule)
- Tell the player the dealer's hand and how many points it is worth
- Compare the hands and tell the player whether they win or lose
- Make good use of functions, loops, and control flow. Remember, DRY (Don't repeat yourself)!

# Example

A playthrough of the game might look like this:
Your hand is 5C, 9C
(14 points)
Dealer shows: QH
What do you want to do? ("hit" or "stick") hit
Dealer's hand is 3H, 3S
(6 points)
Dealer's hand is 3H, 3S, 10D
(16 points)
Dealer's hand is 3H, 3S, 10D, 2D
(18 points)
You lose!

In the `"What do you want to do? ("hit" or "stick") hit`" stage, `"What do you want to do? ("hit" or "stick")` requests a prompt and the user enters `hit` or `stick`

# Stretch Tasks

If you manage to complete this you can take it further in many ways:
- Add naturals if you haven't already (see the rules)
- Refactor your code in OOP style (if you have covered the OOP lessons yet)
- Add pair splitting
- Add betting
- Add doubling down to betting
- Add multiple players
- Read the rules and see if you can find anything else to add

[Back](./README.md)
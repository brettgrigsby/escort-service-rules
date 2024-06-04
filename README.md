# Escort Service Rules v1.0.0

Escort Service is a co-op deck-building rogue-like game. You play as a group of mech pilots escorting a shuttle of civilians to safety. You will fight off waves of enemies while escort the shuttle to their home planet. If the shuttle is destroyed, you lose.

The actions you take to defend the shuttle will often generate **HEAT** that must be vented, pushing you farther away from the shuttle. Big actions generate more **HEAT**, so you must balance your actions to stay close to the shuttle.

## Game Setup

-   Lay out the shuttle and 4 column cards in the center of the table
![board-setup](https://github.com/brettgrigsby/escort-service-rules/assets/8657755/95ccc65d-9ca0-4a49-b660-8868d6d60ad6)

-   Shuffle the Scrap Pile and place it face down
-   Place damage counters in a pile that is easily accessible
-   Each player should choose a Character
    -   Grab the Character cards, Starting Deck, and Upgrade Deck for your character
    -   Shuffle your starting deck and place it in front of you as your Draw Pile and place one of your Character cards next to it
    -   Shuffle your Upgrade Deck and place it nearby
    -   Draw 4 cards from your Draw Pile
    ![player-board](https://github.com/brettgrigsby/escort-service-rules/assets/8657755/426d6a94-a93f-4931-912e-a0c06adddcb3)

-   Proceed to scenario setup when everyone is ready

## Character Card

Each character will include 2 Character Cards. One will be placed next to your Draw Pile and the other will be placed on the board. The character card shows:

-   Character Name
-   Health
-   Scrap Slots
![character-card](https://github.com/brettgrigsby/escort-service-rules/assets/8657755/98c713ac-66a3-4122-9530-7f93c589a3ce)


When your character takes damage, place damage counters on the character card next to your draw pile.

## Scenario Setup

-   Place enemies on the board according to the scenario
-   Place player Character cards in a column above the shuttle in any order the team chooses
![scenario-setup](https://github.com/brettgrigsby/escort-service-rules/assets/8657755/99981704-0718-4f12-aee4-f3585a655a6d)


## Game Play

Game play will proceed with 1 unit acting at a time. The unit immediately above the shuttle is the active unit. The unit will perform actions until they choose to stop. After the active unit has completed their turn, the unit that is now in the position immediately above the shuttle will become the active unit.

If the column above the shuttle is empty, all columns move 1 left. This advancement is called a **TICK**. **TICK**s will continue until the column above the shuttle contains unit(s).

![pre-tick](https://github.com/brettgrigsby/escort-service-rules/assets/8657755/b04a535d-a86f-4fe3-bf60-6ee24724676b)
![post-tick](https://github.com/brettgrigsby/escort-service-rules/assets/8657755/b8c95449-7ca9-4353-94af-bf897a83a100)

This game play loop will continue until the scenario resolves or the shuttle is destroyed.

## Enemy Turn

-   **Basic Enemies**

    -   Execute the actions listed on the unit's Character Card
    -   Flip the unit's Character Card to the other side

-   **Elite Enemies**

    -   Turn over the top card for the Elite Enemy's Draw Pile and execute the actions listed on the card

    Elite enemies have a Draw Pile that is shuffled at the beginning of the scenario. When the Elite Enemy's Draw Pile is empty, shuffle its discard pile to create a new Draw Pile. The back of each card will give the players a clue for what type of action the elite enemy will take.

![elite-enemy](https://github.com/brettgrigsby/escort-service-rules/assets/8657755/40dc02c7-eb5c-49ff-85a1-4dd584d13e87)


### Choosing Targets

Enemy units will always choose to attack player units first (unless indicated). If there are no player units in range, they will attack the shuttle. If there are multiple player units in range, they will target the unit with the least remaining health.

#### ZEALOT

Enemies marked as **ZEALOT** will attempt to target the shuttle instead of player units if able. Importantly, player units with the **TAUNT** status still must be targeted by **ZEALOT**s over the shuttle if they are in range.

## Player Turn

-   Play as many cards as you like from your hand one at a time
-   Once you are done playing cards:
    -   If you are still immediately above the shuttle, generate 1 **HEAT**
    -   You may discard any number of cards remaining in your hand
    -   Draw cards from your Draw Pile until you have 4 cards in your hand

## Playing Cards

Each card will list 1 or more actions. Each action must be resolved in the order listed on the card. You must fully resolve an action before moving on to the next action on the card. After you have resolved all actions on the card, place the card in your discard pile (unless it has a status effect that requires it to be placed under a unit).

## Drawing Cards

Cards are drawn from your Draw Pile. If you need to draw a card and your Draw Pile is empty, shuffle your discard pile and place it face down to create a new Draw Pile.

## Taking Actions

Whether playing cards or resolving actions printed on a unit card, actions resolve in the same manner. The card or unit will have a list of 1 or more actions, and each action is resolved 1 at a time.

### Action Types

-   **HEAT**: the amount of **HEAT** generated by the action that must be vented
-   **MELEE**: deal damage to a target equal to the number to the right of the melee icon. Target must be
-   **RANGED**: deal damage to a target equal to the number to the right of the ranged icon
-   **HEAL**: remove damage from a target equal to the number to the right of the heal icon. Healing cannot target the shuttle unless noted on the action.
-   **DELAY**: move the target to the right a number of columns equal to the number to the right of the delay icon
-   **ADVANCE**: move the target to the left a number of columns equal to the number to the right of the advance icon
-   **DISCARD**: choose a number of cards from your hand to discard equal to the number to the right of the discard icon and put them in your discard pile
-   **DRAW**: draw a number of cards from your Draw Pile equal to the number to the right of the draw icon
-   **STATUS**: apply a status effect to a target

#### Action Modifiers

-   **AOE**: the action affects all units within range of the action. Your actions do not damage friendly units unless noted
-   **IN**: the action can only affect target that fall within the range of the action
    -   **NUMBER**: the action can only affect targets that are within **NUMBER** spaces of the unit
    -   **LEFT | RIGHT | UP | DOWN**: the action can only affect targets that are in the direction specified

#### HEAT

When a unit generates **HEAT**, it must vent that **HEAT** by moving to the right a number of columns equal to the **HEAT** generated. If there aren't enough columns to the right of the unit to vent the **HEAT**, they are not prevented from taking the action. Instead, when the unit gets to the rightmost column, they will take damage equal to the amount of remaining **HEAT** that was not vented.

#### Status Effects

Some cards will apply a status to a unit. Status effects will have the status noted at the bottom of the card surrounded by the associated icon. When you play a card that applies a status effect, place that card under the affected unit with the status effect showing. The status effect will remain until the card becomes the active unit. At that time, the card is returned to its owner's discard pile.

#### Status Types

-   **TAUNT**: when an active unit is choosing an enemy unit as the target of an attack, they must choose a unit with the Taunt status if able.
-   **SHIELD**: when a unit with the shield status takes any amount of damage, remove the shield status and prevent that instance of damage.
-   **POISON**: when a unit with the poison status takes damage, they take an additional 1 damage.
-   **HIDDEN**: a unit with the hidden status cannot be targeted by any enemy action. AOE actions can still affect the hidden unit.

## Moving Units

When a unit is moved by any means, they are always placed at the top of the column that they enter. When a unit leaves a column, any units above them are moved down to fill the space.

## Dealing Damage

When a unit takes damage, place damage counters on the unit equal to the amount of damage taken. If a unit has damage counters equal to or greater than their health, they are destroyed.

When an enemy unit is destroyed, remove them from the board and draw a card from the Scrap Pile. Decide as a team which player will receive the Scrap. This may involve arguing or rolling some dice. Have fun with it.

When a friendly unit is destroyed, place their character card below the column in which they were destroyed. If they are later healed to a point where their damage is less than their health, they are returned to the top of the column in which they were destroyed.

## Scenario Completion

When the scenario is complete, the team will have the opportunity to upgrade their deck with Upgrade Cards.

After upgrading, the team will move on to the next scenario.

## Upgrading Your Deck

At the end of a scenario, each player will draw 3 cards from their Upgrade Deck and choose up to 2 cards to add to their deck. The remaining card(s) are placed on the bottom of the Upgrade Deck.

If a player chooses to add 0 cards to their deck, they may instead remove 1 card from their deck. Player decks must always contain at least 10 cards.

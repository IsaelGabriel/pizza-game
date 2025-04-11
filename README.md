# Rodizio Game

A digital card game where you have to eat more than your friends at a pizza place.
Game design originally intended for the [Crossing Latitudes 2024 Game Jam](https://itch.io/jam/crossing-latitudes-2024).

# Game Objective

Based on the Brazillian 'rodízios', the objective of the game is to eat as much as possible (and more than your friends).
The different player stats have different effects.

# Player Stats

## 1. Fullness

- When maxed out: Player throws up
    - Full DISGUST
    - Reputation down
    - Fullness becomes 0

## 2. Thirst

- When reaches zero: Player goes to the bathroom
    - All Food in hand loses 1 WARMTH
    - Player is skipped in next card dealing

## 3. Disgust

- When full: Player cannot eat
- When above 25% of its capacity: FULLNESS effect dealt by food is increased

## 4. Reputation

- When reaches 0: Player is expelled from the restaurant
    - Game Over
- Increases chance of quality cards being dealt
- When below 50%: Food has increased chance of being cold
- Skipping a card deling turn increases REPUTATION

## Score: RESTAURANT LOSS

- Buying extra cards:
    - Reduces LOSS
    - REPUTATION up
- When being dealt cards, choosing expensive ones:
    - LOSS up
    - REPUTATION DOWN
    - Every x turns there is a new expensive card

# Card Types

- Food
- Drinks
    - Have to bought using LOSS as currency
- Actions

# Turn structure

1. Receive a card from the previous player
2. Three food cards are presented to you: Choose one to add to hand
3. Choose up to two cards to play (max. one action card)
4. Choose a card to pass to the next player with decreased WARMTH
# Rummy Game Tracker
An Epic application to track your Home Rummy Games!

## Features

### Dashboard
- Create a new home game
- View previously played home games

### New Home Game Screen
- Auto populate game name, based on date and time
- Record location/Enter location name manually
- Game Mode
  - Cash Game
    - 1st drop penalty amount
    - Mid drop penalty amount
    - Book penalty amount
  - Jackpot Game
    - Points limit
    - Cumpulsory score (Limit - 20)
    - Buy-in amount per player
- Player Selection
  - Create New Players
    - Name
    - Picture
  - Pick from Existing Players
- Start or Cancel New Game

### Current Game Management
- Cash Game
  - Record score
    - Select pre-set penalty from drop down based on points shown (OR)
    - Guess penalty from the (range of) declared points
      - 1 to 10 -> 0
      - 10 to 30 -> 1st drop penalty amount
      - 30 to 50 -> 2nd drop penalty amount
      - Above 50 -> Book penalty amount
  - Stop current game
    - Calculate cash breakup based on current winnings or losses
    - Summary showing money won/lost with what is owed by each player
- Jackpot Game
  - Record score
    - Enter numbers based on the points declared for each player
    - Range from 0 to 80
  - End Jackpot Game prematurely
    - Data loss confirmation
  - Declare winner based on the points entered

### Previous Games
- Current Running game(s) on top of the list
- Older games at the bottom
- Multi-Select a completed games and delete them

### Player management
- Create a new player
  - Name
  - Picture
- Player details
  - Edit player details
    - Name
    - Photo
  - Games history
    - Cash games
    - Jackpot games
- Delete an existing player

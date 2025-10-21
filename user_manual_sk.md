# User Manual

Comprehensive documentation for users to get in touch with functionality of application. 

It aims on practical demonstrations for currently provided features that is explained through interactive animations and videos.

Here's quick navigation for major topics: 
- [Application Access](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#access)
- [Navigation Screen](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#navigation-screen)
- [Smart Version](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#smart-version)
- [Desktop Version](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#desktop-version)

## Access

For successful entrance to enviroment use this link: \
https://hockgeny.grafana.net/d/alrb6gn/home-navigation?orgId=1&kiosk=true

It's highly recommend to made a shortcut on your home screens to simplifying an access.

If you're not logged in system, you'll be prompted to provide your credentials for access. 

Once you'r logged in, your credentials should be remembered in system. For another accessing attempts you'r redirected to navigation board of application without necessarity of login.

## Navigation Screen

After succesful login into the enviroment user is welcomed in navigation showroom where's possible to: 
- Access to application displayed in various methods based on currently used platform - smartphone, desktop computer
- Switching between language versions and acces to user manuals - top right corner
- Get information about latest updates and other types of information regarding application and hockey in overall - bottom section 

It's important to clarify the information regarding platform selection. Difference is not only in adjustment based on screen resolution, but it also related with scope of functionality selected platform could provide. While version for smartphone is more lite but still posses core functionality, desktop version offers some additional features its extends user experience and provides more robust feel while working with.

<img width="750" height="450" alt="image" src="https://github.com/user-attachments/assets/84f5d169-e630-46f9-b41b-319a99331de8" />


## Smart Version 

Here's quick navigation for functionality explanation covered in this section: 
- [Usability Setup](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#usability-setup)
- [Gameboard](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#gameboard)
  - [Player Creation](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#player-creation)
  - [Game Scheduler](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#game-scheduler)
- [Lobby](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#lobby)
- [Roster](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#roster)
  - [Roster Creation](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#roster-creation)
  - [Player Attendance](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#player-attendance-confirm)
- [Stream](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#stream)
  - [Score Counter](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#score-counter)
- [Analysis](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#analysis)
  - [Post-Game Modifications](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#post-game-modifications)
- [Standings](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#standings)

### Usability Setup 

Base screen right after selection of visualization platform serves similar way like login screen with some quick overview metrics.

This section consists of: 
- **Organization select** - by clicking on org. title choose a desired one which will be part of further operations in application
- **Player select** - by clicking on player name choose a desired one which will be part of further operations in application

Each section provides quick look on standard overview about selection's status. Each selection is marked with identifier. Based on screen space saving, this identifier is used in metric overview for quick orientation. 
- **Activity Count Order**
  - Org.: aggregation from count of scheduled games
  - Player: aggregation from count of player's invitation to game lobby
- **Last Status Information**
  - Org. Last Game: information is taken from game scheduler
  - Player Last Activity: information is taken from last join to game lobby

<img width="320" height="600" alt="image" src="https://github.com/user-attachments/assets/41508767-787f-4271-8f12-955b6d3d8310" />

### Gameboard

Home screen for selected organization providing quick overview about: 
- **Usability setup selection** consists of Organization and Player pick
- **Game history** chronologically order by game scheduled date
- **Game status** bar aimed on organization's latest game
- **Quick organization's stats** focused on:
  - **Player leading board** based on collected data on live score counter
  - **Team winning ratio** based on teams who's part of your organization
  - Additional information about most active player based on game invitations counter and last game winning team
 
Bottom part of page involves navigation buttons for: 
- Return to "Usability Setup" page
- Jump into management tool for player creation or game scheduling

<img width="320" height="600" alt="image" src="https://github.com/user-attachments/assets/faf35997-e747-456e-852f-2c92f4cfe204" />

#### Player Creation 

Feature supports full functionality of player's management system covered in desktop version.

This ligther version provides: 
- Quick player creation based on selected name
- Position definition necessar for suggestion system and roster creation

Data about player could be fully modified in desktop version of player's management system.

<img width="320" height="600" alt="image" src="https://github.com/user-attachments/assets/ed7a2d3f-6c5f-464d-91c7-1afca9afc5cf" />

#### Game Scheduler

Feature supports full functionality of organization's management system covered in desktop version.

This ligher version provides: 
- Plan the game by setting date and time
- Set a game cost
- Select home and away teams which will compete in the game

Further modifications of game data or game cancellation could be performed in desktop version of team's management system. 

<img width="320" height="600" alt="image" src="https://github.com/user-attachments/assets/54502cdb-b6fd-4001-ad6a-c02e50d15ec9" />

### Lobby

By the creation of game the process of building a player's invitation room is complete and waiting lobby is ready to be filled.\
Lobby room is feature that helps in organizing event process and makes non-manager players more self-sufficient.

It's important to know lobby room is going to be locked **36 hours** before planned game date.\
Once limit is reached, players are no longer be able to join into game by itself and their chance to be involved into game roster is lower.\ 
Player still could be added into game roster but only by event manager in process of creation of roster by special feature described in "Roster Creation" section. 

After entrance into the lobby player can perform: 
- **Game join** to show interest to be added in game roster
- **Quit game** by leaving lobby and eliminate a chance to be pinned into game roster
- **Chat** with other players by typing a message into chat box

Metrics involved in this particular section provides information about: 
- Last player joined into the lobby room
- Goalie availability in lobby room
- Player count joined in lobby room 

Player could be informed by email notification after every process change in Lobby room.

<img width="320" height="600" alt="image" src="https://github.com/user-attachments/assets/ec61c4e1-7bf0-4fad-a4a7-db00e327f224" />

### Roster

Game cannot begin without preparation. Roster system brings on table powerful alternative of standard excel sheets or other formats of grid and tables necessar to create a simple list of players and their positions.

Functionality covered by this feature involves: 
- Teams game grid separation separated by player's shifts
- Roster management tool to build a quick game grid from available players
- Player attendance confirmation before game starts

It's important to mention "Roster" section is open 36 hours before game starts which is also indicated in "Gameboard" by time counter.

<img width="320" height="600" alt="image" src="https://github.com/user-attachments/assets/c1b39836-00e2-4123-83a2-a477645007d9" />

#### Roster Creation

This tool supports main functionality originally developed for desktop version. It's a lighter version in comparatio of desktop one, but still coveres crucial aspects like: 
- **Adding** player into game roster by picking from **Lobby Room** - it's default player base from which the picks are preferred
- **Adding** player into game roster by picking from Organization **Player Base** - it helps when some players miss oppurtunity to officialy joining the game by game lobby
- **Remove** player from game roster
- **Position suggestion** system based on player specification set at creation process
- **Player occupation** validation in game roster
- **Position occupation** validation in game roster

Whole process of roster creation is divided in 3 steps: 
1. Pick player from Org. players repository or lobby room
2. Choose desired position for selected player based on team, line and grid
3. Confirm selection

Once its confirmed, after refreshing page, selection will appear in game roster.

<img width="320" height="600" alt="image" src="https://github.com/user-attachments/assets/fa2e9821-f8da-4e28-9e28-21302f239987" />

#### Player Attendance Confirm

Successful creation of game roster is first step to start a game. For a player, it serves as a official invitation to game by event menager. Once player is invited, players itself should confirm their availability to participate on game. 

In many cases option to participated on game is conditioned by pay a spot in game roster. For example this could be related to individual costs for event management. This is exact case of relation to game costs which are set in "Game Scheduler" that could be used in further analysis or helping managing whole event.

Confirmation process is simple. Once player is added in game roster, its available to confirm his attendance by clicking on player's name in game grid. In the grid is possbile to check exact time when player was added by clicking on triangle in the corner of particular cell.

<img width="320" height="600" alt="image" src="https://github.com/user-attachments/assets/335dbd59-4f84-474d-b1f2-edf4ac0f5d81" />

### Stream

This feature providing key option to data collection necessary for further analysis and statistics. It unlocks possibilities to live tracing game progression status.\
Since smart version is more tool oriented to provide most easy usage while ongoing game, desktop version is fully oriented like monitoring dashboard with much more complex real time metrics. 

Base screen for "Stream" section offers: 
- Live game result
- Roster-oriented grid view for simple usage related with pointing system
- Simple indication about last scorer for each team

<img width="320" height="600" alt="image" src="https://github.com/user-attachments/assets/b8087229-032f-4206-8f69-ee8522e2a26d" />

#### Score Counter

It works like remote control for control of game result by adding several metrics directly to player. 

Counting works behind on simple pointing system consists of: 
- Goals
- Assists
- Saves
- Shots

System is directly connected with game roster to ensure easy usage and orientation. By selecting player from game grid user is redirected into pointing system selection. Once metric is selected its necessar to confirm metric addition to player.

It's important to know, user can add or remove metric from player's point base.

<img width="320" height="600" alt="image" src="https://github.com/user-attachments/assets/6803dc12-8b4e-463b-ba02-966868ab77b1" />

### Analysis

Option to work with collected data is main goal of this tool. This section provides building an insights after finished games. 

Post game analysis center offers options to: 
- Game result closure
- Game progression overview with information about player with most active game record
- Post game player attendance confirmation

Its important to mention that is available **36 hours** right after finishing the game.

<img width="500" height="500" alt="analysis-insight" src="https://github.com/user-attachments/assets/26421037-c0a5-468f-837b-93e9eca3d671" />

#### Post Game Modifications

Same as this option is part of "Roster" section, it provides additional confirmation in case of player attendance in game. This feature help to event manager in scenarios if participation validations are ongoing after the game, not before.

System for confirmation is similiar then its in "Roster" section, additionally with information about final comparison of all attended players in game.

<img width="320" height="600" alt="image" src="https://github.com/user-attachments/assets/1555f69c-d7fa-4192-99b1-997fb895e21c" />

### Standings 

In early version of application, this section providing possibility to look back on history of each game.\
Basically, features that is part of "Analysis" section is also part of "Standings" section. Only difference that is "Analysis" section is locked 36 hours after the game, but "Standings" section is permanently available. 

For upcoming versions, "Standings" section will provide much more deeper look on selected organization stats and its opening the options to compare metrics between various organizations.

## Desktop Version

Here's quick navigation for functionality explanation covered in this section: 
- Gameboard
- Player Management
  - Player Creation
  - Player Modifications  
- Team Management
  - Organization Creation
  - Group Creation
  - Game Scheduler
  - Game Modifications
- Game Join
  - Player Suggestions
- Game Roster
  - Roster Creation
  - Player Confirmation
- Game Live Tracking
- Game Analytics Tools

# Užívateľská Príručka

Komplexná dokumentácia pre používateľov, ktorá im umožňuje oboznámiť sa s funkciami aplikácie.

Zameriava sa na praktické ukážky aktuálne poskytovaných funkcií, ktoré sú vysvetlené prostredníctvom interaktívnych animácií a videí.

Tu je rýchla navigácia pre hlavné témy:
- [Prístup do aplikácie](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_sk.md#Prístup)
- [Navigačný panel](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_sk.md#navigation-screen)
- [verzia Smart](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_sk.md#smart-version)
- [verzia Desktop](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_sk.md#desktop-version)

## Prístup do aplikácie

Pre úspešný vstup do prostredia aplikácie použite tento odkaz: \
https://hockgeny.grafana.net/d/alpnbp2/home-navigation-sk?orgId=1&kiosk=true

Dôrazne odporúčame vytvoriť si na Vašej domovskej obrazovke skratku pre zjednodušenie prístupu.

Ak nie ste prihlásení do systému, budete vyzvaní na zadanie svojich prihlasovacích údajov.

Po prihlásení by si systém mal vaše prihlasovacie údaje zapamätať. Pri ďalších pokusoch o prístup budete presmerovaní na hlavný navigačný panel aplikácie bez nutnosti prihlásenia.

## Navigačný panel

Po úspešnom prihlásení do prostredia je používateľ privítaný v navigačnom showroome, kde je možné:
- Prístupiť k funkciám aplikácie rôznymi spôsobmi na základe Vami aktuálne používanej platformy - smartfón, stolný počítač
- Prepínanie medzi jazykovými verziami a prístup k používateľským manuálom - pravý horný roh
- Získanie informácií o najnovších aktualizáciách a ďalších informácií týkajúcich sa aplikácie a hokeja všeobecne - spodná časť


Je dôležité objasniť informácie týkajúce sa výberu platformy. Rozdiel nie je len v nastavení na základe rozlíšenia obrazovky, ale súvisí aj s rozsahom funkcií, ktoré vybraná platforma ponúka. Zatiaľ čo verzia pre smartfóny je jednoduchšia, ale stále obsahuje základné funkcie, verzia pre počítače ponúka niektoré ďalšie funkcie, ktoré rozširujú používateľský zážitok a poskytujú robustnejší pocit pri práci.

<img width="750" height="450" alt="image" src="https://github.com/user-attachments/assets/84f5d169-e630-46f9-b41b-319a99331de8" />


## Verzia Smart

Tu je rýchly prehľad funkcií uvedených v tejto časti:
- [Užívateľské nastavenia](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#usability-setup)
- [Herná tabuľa](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#gameboard)
  - [Registrácia hráča](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#player-creation)
  - [Plánovač hry](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#game-scheduler)
- [Čakáreň](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#lobby)
- [Súpiska](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#roster)
  - [Vytvorenie súpisky](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#roster-creation)
  - [Potvrdenie účasti hráča](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#player-attendance-confirm)
- [Zápas](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#stream)
  - [Počítadlo skóre](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#score-counter)
- [Štatistika](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#analysis)
  - [Úpravy po zápase](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#post-game-modifications)
- [História](https://github.com/alphainbeta/beerleaguebox/blob/main/user_manual_en.md#standings)

### Užívateľské nastavenia

Základná obrazovka hneď po výbere vizualizačnej platformy slúži podobne ako prihlasovacia obrazovka s niekoľkými rýchlymi prehľadmi metrík.

Táto sekcia obsahuje:
- **Výber organizácie** - kliknutím na názov organizácie vyberiete požadovanú organizáciu, ktorá bude súčasťou ďalších operácií v aplikácii
- **Výber hráča** - kliknutím na meno hráča vyberiete požadovanú organizáciu, ktorá bude súčasťou ďalších operácií v aplikácii

Každý výberový element je označený identifikátorom. Na základe úspory miesta na obrazovke sa tento identifikátor používa v prehľade metrík pre rýchlu orientáciu.

- **Stĺpcové poradie podľa aktivity pre:**
  - Organizáciu - agregácia počtu naplánovaných hier
  - Hráčov - agregácia počtu prihlásení do hernej čakárne
- **Informácie o poslednom stave pre:**
  - Organizáciu - Posledná plánovaná hra (informácie sa preberajú z plánovača hier)
  - Hráčov - Posledná aktivita hráča (informácie sa preberajú z posledného pripojenia do hernej čakárne)

<img width="320" height="600" alt="image" src="https://github.com/user-attachments/assets/41508767-787f-4271-8f12-955b6d3d8310" />

### Herná tabuľa

Domovská obrazovka pre vybranú organizáciu poskytuje rýchly prehľad o:
- **Vybrané užívateľské nastavenia** - pozostáva z výberu organizácie a hráča
- **História hier** - chronologicky zoradená podľa plánovaného dátumu hry
- **Stav hry** - informačný riadok zameraný na najnovšiu hru vybranej organizácie
- **Rýchle štatistiky organizácie** zamerané na:
  - **Rebríček hráčov** na základe zhromaždených údajov pomocou počítadla skóre zo zápasov
  - **Pomer víťazstiev** na základe tímov, ktoré sú súčasťou vašej organizácie
  - Indikátory najaktívnejšieho hráča (na základe počtu prihlásení do hernej čakárne) a víťazného tímu pre posledné uskutočnené stretnutie

Spodná časť stránky obsahuje navigačné tlačidlá pre:
- Návrat na stránku „Užívateľské nastavenia“
- Prechod do sekcie pre hernú správu, súčasťou ktorej sú nástroje ako registrácia hráča alebo plánovanie hier

<img width="320" height="600" alt="image" src="https://github.com/user-attachments/assets/faf35997-e747-456e-852f-2c92f4cfe204" />

#### Registrácia hráča

Funkcia podporuje plnú funkčnosť systému pre správu hráčov, ktorý je súčasťou verzie desktop.

Táto odľahčená verzia poskytuje:
- Rýchle vytvorenie hráča na základe vybraného mena
- Definíciu pozície potrebnú pre podporný systém pri vytváraní hernej súpisky

Údaje o hráčoch je dodatočne možné modifikovať vo verzií desktop v systéme pre správu hráčov.

<img width="320" height="600" alt="image" src="https://github.com/user-attachments/assets/ed7a2d3f-6c5f-464d-91c7-1afca9afc5cf" />

#### Plánovač hry

Funkcia podporuje plnú funkčnosť systému pre správu a riadenie organizácie, ktorý je súčasťou verzie desktop.

Táto odľahčená verzia poskytuje:
- Nastavenie dátumu a času pre zápas
- Nastavenie nákladov
- Výber domácich a hosťujúcich tímov, ktoré budú účastníkmi zápasu 

Ďalšie úpravy údajov hry alebo zrušenie hry je možné vykonať v desktopovej verzii systému riadenia tímov.

<img width="320" height="600" alt="image" src="https://github.com/user-attachments/assets/54502cdb-b6fd-4001-ad6a-c02e50d15ec9" />

### Čakáreň

Vytvorením hry je proces pozvánky pre hráčov dokončený a čakáreň je pripravená na obsadenie.\
Herná čakáreň je funkcionalita, ktorá pomáha pri organizácii podujatí a umožňuje hráčom, ktorí nie sú súčasťou správy podujatia, väčšiu samostatnosť.\
Správca hry je tak oslobodený od povinnosti prizývania hráčov a hráči sú svojpomocne schopný prejaviť záujem o vybranú hru prihlásením sa do nej.

Je dôležité vedieť, že čakáreň je uzamknutá **36 hodín** pred plánovaným dátumom hry.\
Po dosiahnutí tohto limitu sa hráči už nebudú môcť samostatne pripojiť k hre a ich šanca na zaradenie do herného zoznamu sa zníži.\
Hráč má stále šancu byť zaradený do herného zoznamu, ale iba manažérom udalosti a to až v procese vytvárania hernej súpisky pomocou na to určenej funkcie, ktorá je samostatne popísaná v časti „Vytvorenie súpisky“.

Po vstupe do čakárnej môže hráč vykonať:
- **Pripojiť sa k hre** - týmto krokom hráč prejavuje záujem o zaradenie do hernej súpisky
- **Odpojiť sa z hry** - týmto krokom hráč odvoláva svoje prejavenie záujmu o vybranú hru a eliminuje možnosť byť zaradený do hernej súpisky
- **Četovať v miestnosti** s ostatnými hráčmi napísaním správy do chatovacieho okna

Metriky v tejto konkrétnej sekcii poskytujú informácie o:
- Posledný hráč pripojený do vybranej hry
- Dostupnosť brankára vo vybranej hre
- Počet hráčov pripojených do hry (mimo brankár)

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

## Verzia Desktop

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

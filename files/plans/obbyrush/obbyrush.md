# Obby Rush

A Roblox obby game, but you have to constantly run.

Game is at https://www.roblox.com/games/7124580983/Obby-Rush.

View todo list and game plans at the [Game Plans section](#game-plans).

To see what feature in [game plans](#game-plan) are added in-game, visit [changelog](CHANGELOG.md).

# Contributing

## How to

You can make Roblox maps and levels for the game with Roblox Studio (requires prior Studio knowledge, recommends courses on Roblox website) 
- First create a new game with a place to build your map on.
- You should follow the map guides for each gamemode here (not yet).
- Please keep the map lightweight, recommends Roblox parts only because this is an obby game, pack it in a model.
- When you have done, go to File --> Save to Files and send me the file through [contacts](#contacts), the map will be added to the game and you will get credited on the game description and map selection page.
- Also send your Roblox PlayerId so I can add your name into the game, follow these steps to get it:
    - Open a new or existing place.
    - Create a new script in `StarterPlayer --> StarterPlayerScript`.
    - Copy this in:
    ```lua
    print(script.Parent.PlayerId)
    ```
    - Enter play mode.
    - Open console if you haven't (`View --> Output`), copy the PlayerId printed.

You can view the current maps in game or development [here](#maps).

## Change to plan

You can also contribute and change content in this plan by opening a pull request at [the Github repo](https://github.com/FuniJaerri/FuniJaerri/) (you should read about markdown at https://guides.github.com/features/mastering-markdown/).

Alternatively just [contact me](#contact) here.

# Contacts

Simply message me through where I sent you this (problaby the Discord server) or through [jaerri#1984](https://discord.com/users/679948431103492098).

# Game Plans

### Currency: Point

- Earned by surviving in a match, default is 1 [point](#currency-point)/second, [premium](#free-2x-points) or [gamepasses](#2x-points) players will have a boost to 2 [points](#currency-point)/second.
- Can be used to buy [match power ups](#in-match-one-time-power-ups).
- [Points](#currency-point) are **reset** every new match.

## Game modes

- ### Hunters and Runners 
    - Match will last for a maximun of 3 minutes.
    - Players can only spawn **once**, if killed they will return to lobby or can spectate other players.
    - Two teams:
        - #### Hunters: 
            - Can kill other [Runners](#runners) on touch.
            - Are not allowed to buy [power ups](#in-match-one-time-power-ups).
            - Wins when all [Runners](#runners) are killed or died from obby.
        - #### Runners: 
            - Can only run away from [Hunters](#hunters).
            - Can buy [power ups](#in-match-one-time-power-ups) in match using points.
            - Wins when time runs out or when all [Hunters](#hunters) have died.

## In-match one time power ups 

These items can **ONLY** be bought and used **ONCE** in a match using points:

- ### Respawner
    - Allow player to respawn if killed, best used with a [Respawn Flag](#respawn-flag).
    - Can only be bought in gamemodes where you can only spawn once ([Hunters and Runner](#hunters-and-runners)).

- ### Respawn Flag
    - Place down the [flag](#respawn-flag) at the position player is standing will allow player to respawn there once killed.
    - In gamemodes where you can only spawn once ([Hunters and Runner](#hunters-and-runners)), Respawn Flag are only available when players have bought the [Respawner](#respawner).
    
## Gamepasses

- ### 2x Points
    -  Give a boost to player point/second in match, specifically from 1 point/second to 2 points/second.

## Premium Player Benefits

- ### Free 2x Points
    - Players with premium subscription will automatically have free [2x Points gamepass](#2x-points) benefits.
    - They are **not** allowed to buy the [2x Points gamepass](#2x-points) (already have boost).

## Maps

You can create maps for the game and I will add to the list, instructions [here](#contributing).

Map Name            | Creator           | Finished | Released
------------------- | ----------------- | -------- | --------
Demo Map            | [i_loveflipflop]  | No       | No
          
[i_loveflipflop]: https://www.roblox.com/users/1415347123/profile


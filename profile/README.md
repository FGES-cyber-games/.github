# [FGES CYBER GAMES](https://github.com/FGES-cyber-games)

The goal of this project is to create a "home made" laser game, in which multiple players will play to different game modes.

___

**Languages :** C

**Technos :** Arduino Nano 33 IOT

**Author :** Anatole de Chauveron

**Licence :** All rights reserved

___

## Summary

### [Documentation](https://github.com/FGES-cyber-games/management)

### [Embeded source code](https://github.com/FGES-cyber-games/equipement)

### [Interface and server](https://github.com/FGES-cyber-games/interface)

## Project Description

### Player / Server architecture

The end goal is to have minimum computation embeded on the player. The server must be powerful enough to handle all the realtime requests and send back all informations such as :

- Who shot at him
- End of game
- Game changes (for instance if the player must now hide)
- ...

The code embeded on the player must only receive and emmit modulated laser signals. All signals received are then transmitted to the server who is in charged of processing the informations received.

### Game modes

The game modes are settings the rules of a game. They are initiated with parameters such as the length of the game (in minutes), the number of participants, and the overall goal of the players.

Those goals can change according to the rule. For instance, if the player will play in a team, solo, if changes occur in the game, etc...

## Estimmated budget

| Project vesion | Version Description | Estimmated budget |
|:---:|:---|:---:|
| v0 | A laser shoots whose signal can be modulated, can shoot at a target, that can send a signal to a server in order to identify who shot | **30.75** |
| v1 | Two players are shooting at targets and try to light up all the oponent's targets | _unknown_ |
| v2 | Full scale laser game, with equipement and game modes | _unknown_ |

## Contact

_To contact the owner of this project, please send an email to this address : **adechauveron@gmail.com**_

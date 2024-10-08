# sarpbc-online

![image](https://github.com/user-attachments/assets/70cdcf0a-66f7-45c2-a806-a101b3b03c9a)

_Providing the ability to play Supersonic Acrobatic Rocket-Powered Battle-Cars (SARPBC) online again!_

**Note: I did not make this mod, nor do I host it - All I did was write this `README`**

## Table of Contents

1. [Requirements](#requirements)
2. [SARBC Installation](#sarbc-installation)
3. [RPCN Setup](#rpcn-setup)
4. [Play!!](#play)
5. [Notes](#notes)
6. [Known Issues](#known-issues)
7. [Credits](#credits)
   
## DISCLAIMER

**THIS MOD IS INTENDED FOR PEOPLE WHO 
ALREADY BOUGHT A RETAIL COPY OF SARPBC
ITS ONLY PURPOSE IS TO IMPROVE / PRESERVE 
THE ONLINE FUNCTIONALITY
I DO NOT CONDONE PIRACY, THEREFORE 
I STRONGLY ADVISE YOU TO BUY THIS GAME
ON PS STORE BEFORE PLAYING**

### Requirements

- Supersonic Acrobatic Rocket Powered Battle Cars v1.02 PKG for PS3 **(you must legally own this game!)**
- Supersonic Acrobatic Rocket Powered Battle Cars v1.04 PKG (NPUB30035) (patch)
- `SARPBC Online Mod 1.15.pkg` (patch)
- `stuttering fix.pkg` (patch) (optional)
- [RPCS3](https://rpcs3.net/) PS3 Emulator

### SARBC Installation

**IMPORTANT**: Your packages MUST be installed in the order below (1.02 -> 1.04 -> 1.15):

1) Setup RPCS3 with the appropriate PS3 files per their [Quick Start](https://rpcs3.net/quickstart) instructions.

2) Install the Supersonic Acrobatic Rocket Powered Battle Cars v1.02 PKG file in RPCS3:
   
> File -> Install Packages/Raps/Edats -> Select the PKG file

3) Repeat step #2 with the SARBC 1.04 PKG

4) Repeat step #2 with `SARPBC Online Mod 1.15.pkg`

5) Optionally - Repeat step #2 with `stuttering fix.pkg`

### RPCN Setup

1) In RPCS3, enable RPCN under "PSN Status" and change "Network Status" to "Connected"

> Configuration -> Advanced -> Network

![image](https://github.com/user-attachments/assets/1b5a8fee-1552-483b-b9a2-34a913b55259)


2) In RPCS3, create an RPCN account

> Configuration -> RPCN -> Account -> Create Account

![image](https://github.com/user-attachments/assets/f9d8cfab-7bc7-4fe8-a8c4-c426b61f823f)

![image](https://github.com/user-attachments/assets/815577ed-faad-47d0-b7a1-e9cbb0efd5c0)

> Follow the prompts and enter the token you receive via email

3) Add other RPCN friends - I can't help you there :-)

> Configuration -> RPCN -> Friends

### Play!!

1) In SARBC select "Play Online" and then select "Unranked Match" if hosting, or "Join A Friend" if your friend is hosting.

2) Once in the lobby with your friend, select "Start Matchmaking" (if hosting)

3) Win!!

### Notes

- Unless you need them for troubleshooting, silence the logs in RPCS3 to preserve HDD/SDD health
> Configuration - Advanced - Silence All Logs

- FPS are uncapped in the game engine, I suggest limiting them at around 120-180 in RPCS3
> Configuration - GPU - Framelimiter

- Some values in the game inputs have been adjusted in the patch. To take advantage of them, disable all emulator deadzones/antideadzones for controllers

### Known Issues

- The game can poorly for about 2 minutes at each boot due to emulator incompatibilities 
(queue compile attempt and fail)

- Scoring a goal on the Galleon map crashes the game due too emulator incompatibilities
 (fails to allocate memory)

- Saving replays crashes the game

### Credits

- `kuxir97` - Mod and patch
- `sonic11719` - Logo

# CALDERA

![net](https://repository-images.githubusercontent.com/112409981/e17c0200-8cb2-11eb-8cae-d818ce9e6d65)

So after exhausting my mind in school I decided to understand it on my own and share it with classmate to make it easiyer for them to understand, Not all ;)

## What's Mitre Caldera ?
Caldera is a framework intended to empower cyber practitioners — whether red or blue teams — to save time, money, and energy through automated security assessments.
CALDERA mostly can help defenders with:
* Autonomous breach and simulation exercises
* Identifying weak points within a network
* Lowering the cost of training employees
* Highlighting gaps in defenses
* Reducing resources needed by security teams
* Providing a platform for research and development of defenses
* Answering questions concerning detection and response
CALDERA also depends on MITRE ATT&CK framework when possible.

In short, CALDERA helps defenders to better respond to adversary behaviors by detecting and responding to threat actor behaviors .
#### But how the heck it's doing that !!!!
## Caldera Core components
* Agents
* Abilities
* Adversaries
* Operations
* Plugins

#### Just Chill, i'll explain them :

## Agents
Agents are simple software programs that run on hosts/endpoints and facilitate communication to the CALDERA server.
In short agents are The host that you choose to work on
### CALDERA provides three default agents:
* ***Sandcat*** - primary default agent which communicates through HTTP, Git, or P2P over SMB with the option for further extension .
* ***Manx*** - a TCP-based agent which functions as a reverse-shell
* ***Ragdoll*** - An agent which communicates via the HTML contact

All three of these agents are supported by ***Windows***, ***Linux***, and ***MacOS***.
### Agents configuration
When deploying an agent, users have a variety of configuration options to customize the agents as needed. Below are some examples of the available options:

![net](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*NASr0xMKyUKEKiHX3rBK1g.png)

## Abilities
The abilities within CALDERA are specific ATT&CK tactics or techniques that can be executed on agents. An ability consists of the following components:

![net](https://miro.medium.com/v2/resize:fit:1400/format:webp/1*HxBTayt-1oMkXjBVf3_a3w.png)

## Adversaries
Adversary profiles are collections of abilities which represent the tactics, techniques, and procedures (TTPs) that can be leveraged by threat actors.
The ATT&CK framework outlines these TTPs, which CALDERA uses to create the adversary profiles which are then executed in an operation. 

In short, adversary profiles determine which abilities will be executed during operations.

An adversary consists of the following components:

![net](https://miro.medium.com/v2/resize:fit:720/format:webp/1*djRX7MutQ5WcGM1YiCdvog.png)

## Operations
CALDERA operations combine agents, abilities, and adversaries to execute attacks against specific targets.

An operation is comprised of the following characteristics:

![net](https://miro.medium.com/v2/resize:fit:720/format:webp/1*tQzxPOTn6qjeaxSEef-f5Q.png)

# SUMMARY
* First of all u need to add an ***Agent*** as a host that you will execute the operations on
* Then u will go to operations to choose an ***Adversarie*** to execute.
* The adversaries are The ***Tactics*** from the ***MITRE ATT&CK***
* The adversarie itself have the ***Abilities***
* The abilites are The ***Techniques*** from the MITRE ATT&CK

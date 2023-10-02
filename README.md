Noteworthy Considerations 
1. Guaranteed to work on Minecraft 1.12.2 CC:Tweaked CraftOS 1.8
2. This turtle mining script is best used with Ender Storage and preferably a storage system that is able to pull items from a ender chest (like Refined Storage or Applied Energistics)

![setup](https://github.com/ManiacSpazatron/Mincraft-Basic-Turtle-Miner/assets/103073028/5f8a5aca-d1bd-4a35-9a47-9a00dba4c76f)

Features:
1. Mines 1 whole chunk (16x16 blocks)(hit F3 + g to see chunk borders) then has to be manually reset
2. Checks if the turtle has enough fuel and if the inventory is full every 16 blocks
3. Basic mob detection/defense
4. Basic item auto suck (sucks up items on the ground)
5. Mining stops when it hits bedrock

For these scripts to work you need...
1. Have 2 different kinds of colored ender chests (like the ones from Ender Storage)
2. Fuel for the turtle in an enderchest (coal/coal blocks/blaze rods)
3. The ender chest containing the fuel must be in the turtle's first item slot
4. The ender chest for offloading items has to be in the turtle's second item slot
![image](https://github.com/ManiacSpazatron/Mincraft-Turtle-Miner/assets/103073028/2a85cdab-c7ee-4cc9-a75a-2cad84f41646)

5. Make sure you have edited the computercraft config file to allow http

![image](https://github.com/ManiacSpazatron/Mincraft-Basic-Turtle-Miner/assets/103073028/d6a670c6-5174-4daf-8f97-9d1d3feb1359)
![image](https://github.com/ManiacSpazatron/Mincraft-Basic-Turtle-Miner/assets/103073028/9e99804e-361c-436b-8c50-b0e1a17f6334)

6. Go to my BasicMining code and click on "Raw"

![image](https://github.com/ManiacSpazatron/Mincraft-Basic-Turtle-Miner/assets/103073028/26dd8adc-ecd9-40cc-856d-1c1ef21d9823)

7. Copy the URL

![image](https://github.com/ManiacSpazatron/Mincraft-Basic-Turtle-Miner/assets/103073028/02165abc-5406-44e8-8807-af5e30485f86)

8. Go back to your mining turtle and type "wget" then paste the URL after that and hit Enter 
9. Type: BasicMining  (or whatever the name of the script is)
10. Your turtle should be mining!

Disclaimers
1. Players can prevent turtle's movement by standing in front of it causing it to be misaligned when mining a whole chunk
2. On very rare occasion a mob can prevent the turtle's movement by briefly walking in front of it at just the right time before getting attacked

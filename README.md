# Pokemon-Wiki
![image](https://github.com/SiddharthaKandpal/pokemon/assets/78250442/f473cf3c-07ed-4084-9a8a-34e3bdec06bd)

## Introduction:
Objective: To create the Pokedex on PowerBI and use that to find the most powerful Pokemon.  

Scope: To Create a battle simulator.
## Dataset Overview
This dataset contains information on all 809 Pokemon from all Seven Generations of Pokemon. The information contained in this dataset includes Base Stats, Performance against Other Types, Height, Weight, Classification, Egg Steps, Experience Points, Abilities, etc.  
The information was scraped from http://serebii.net/  
name: The English name of the Pokemon  
japanese_name: The Original Japanese name of the Pokemon  
pokedex_number: The entry number of the Pokemon in the National Pokedex  
percentage_male: The percentage of the species that are male. Blank if the Pokemon is genderless.  
type1: The Primary Type of the Pokemon  
type2: The Secondary Type of the Pokemon  
classification: The Classification of the Pokemon as described by the Sun and Moon Pokedex  
height_m: Height of the Pokemon in meters  
weight_kg: The Weight of the Pokemon in kilograms  
capture_rate: Capture Rate of the Pokemon  
base_egg_steps: The number of steps required to hatch an egg of the Pokemon  
abilities: A stringified list of abilities that the Pokemon is capable of having  
experience_growth: The Experience Growth of the Pokemon  
base_happiness: Base Happiness of the Pokemon  
against_?: Eighteen features that denote the amount of damage taken against an attack of a particular type  
hp: The Base HP of the Pokemon  
attack: The Base Attack of the Pokemon  
defense: The Base Defense of the Pokemon  
sp_attack: The Base Special Attack of the Pokemon  
sp_defense: The Base Special Defense of the Pokemon  
speed: The Base Speed of the Pokemon  
generation: The numbered generation in which the Pokemon was first introduced  
is_legendary: Denotes if the Pokemon is legendary.

## Technologies Used  
1) [.sql](https://www.microsoft.com/en-ca/sql-server/sql-server-downloads)
2) [.PowerBi](https://powerbi.microsoft.com/en-us/downloads/)

## Visualizations Explained-
### 1) Pokemon-Wiki
![image](https://github.com/SiddharthaKandpal/pokemon/assets/78250442/4417b95f-94da-447f-9e19-b21e389826b4)
This dashboard is the Pokemon Wiki. This consists of 5 Slicers Type 1, Type 2, Classification, Name & Generation. These can be used to filter through the Pokemon database.  
This dashboard also has 6 Data Cards that show the 6 basic stats of a Pokemon namely Hp, Attack, Defense, Sp_Attack, Sp_Defense, and Speed. The remaining additional information including the images of the Pokemon is shown by the two matrices.

### 2)  MOST POWERFUL POKEMON BY ATTRIBUTES BASED ON GENERATION
![image](https://github.com/SiddharthaKandpal/pokemon/assets/78250442/b3d6c1d4-dab1-4f50-8b8e-cbeef53ce855)
This dashboard shows the most powerful based on 4 major attributes Hp, Attack, Defense, and Speed. This can also be sliced through the Generation and legendary status of the Pokemon.  
The data Cards show the name and image of the Pokeomns, meanwhile, the clustered column charts at the bottom show the TOP 5 in that category.

### 3)  1V1 Battle simulator
![image](https://github.com/SiddharthaKandpal/pokemon/assets/78250442/6b33e20d-9a46-4823-89b3-92185ebf16c4)

This Dashboard is split into 2 parts (red/blue). You can select the name of the Pokemon from each slicer in the respective parts and their stats will be shown in the respective parts of the dashboard.  
Each data card in part ex-blue zone is not dependent on the slicer in the the red zone. The Base Total score determines the winner.

### 4)  Top 5 according to Type
![image](https://github.com/SiddharthaKandpal/pokemon/assets/78250442/edcd3b4a-b6ad-469d-8647-ea6db3f114b8)
This dashboard shows the Top 5 Pokemons based on types(1&2) in a Matrix with stats and images. Can also be sliced through a legendary slicer on the right corner. 

### 5)  Conclusion
![image](https://github.com/SiddharthaKandpal/pokemon/assets/78250442/aa02e4a4-e59a-4780-85c6-22f4de500deb)  
-We got to know that having a Pokémon with max attribute doesn't transverse to the overall power of the Pokémon. The standard score for determining the strength of a Pokémon is via its base_total score.  
-The most powerful Pokémon according to base_total stats are Rayquaza and Mewtwo.  
-Although Capture rate and legendary status should also be considered in a Pokemon battle. 

### 6) References
Dataset- “The Complete Pokemon Dataset.” Kaggle, 29 Sept. 2017, www.kaggle.com/datasets/rounakbanik/pokemon.  
Information On Pokemon Stats- Bulbapedia, Pokedex, SerebiiImages-  Pokemon images














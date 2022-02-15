# Analysis of the pokemon's creatures

![img_pokemon](https://user-images.githubusercontent.com/39379425/152181573-cd65dfa8-6fcf-4179-82a5-4edb592a6d9b.jpg)

Pokémon are creatures of all shapes and sizes who live in the wild or alongside humans. For the most part, Pokémon do not speak except to utter their names. Pokémon are raised and commanded by their owners (called “Trainers”). During their adventures, Pokémon grow and become more experienced and even, on occasion, evolve into stronger Pokémon. There are currently more than 700 creatures that inhabit the Pokémon universe.
They can be of different types: fire, water, electric, grass, ghost and so on. They can also be strong or weak, as well as slow or fast, and legendary or not.

In this file, we are going to analyze data to answer the following questions:

- Which type of Pokémon has the highest average HP?
- Which type of Pokémon is the fastest?
- Which type of Pokémon has the best attack?
- Which type of Pokémon has the strongest defense?
- Which type of Pokémon has the strongest total strength on average?
- What is the relation between Total, Generation and Legendary?
- How many legendary pokémons are there in each generation?
- What is the distribution between Generation and Speed?
- What is the distribution of Legendary?


We need to do some important steps to answer the question right
- Import necessary libraries;
- Load the data;
- Preliminary check;
- Clean the data;
- Grouping by;
- Visualization and analyzis;

The dataset is available at: https://www.kaggle.com/abcsds/pokemon

The data is described as:

- #: ID for each pokemon
- Name: Name of each pokemon
- Type 1: Each pokemon has a type, this determines weakness/resistance to attacks
- Type 2: Some pokemon are dual type and have 2
- Total: sum of all stats that come after this, a general guide to how strong a pokemon is
- HP: hit points, or health, defines how much damage a pokemon can withstand before fainting
- Attack: the base modifier for normal attacks (eg. Scratch, Punch)
- Defense: the base damage resistance against normal attacks
- SP Atk: special attack, the base modifier for special attacks (e.g. fire blast, bubble beam)
- SP Def: the base damage resistance against special attacks
- Speed: determines which pokemon attacks first each round

To import the libraries is necessary to run the code line for each library:
pip install library_name

for example:
pip install numpy
pip install pandas
pip install seaborn
pip install matplotlib

At Preliminary check's step, we can see important information, such as statistical analysis and missing data, then, convert and clean the data and fill the missing data at Clean the data's step.
At Grouping by's step, we can associate two or more columns to do analysis, then, it will be possible to answer the above questions through data visualization and analysis in the last one step.

So, Gotta Catch 'Em All!? Hehehe...

- Which type of Pokémon has the highest average HP?
![highest_average](https://user-images.githubusercontent.com/39379425/152193357-70f90095-3fec-444c-93e5-e01221b39065.jpg)

We can realize the type of Pokémon Dragon has the highest average, and the Bug has lowest.

- Which type of Pokémon is the fatest?
![fatest](https://user-images.githubusercontent.com/39379425/152194203-44eab71c-84d3-4656-8604-d279f28c2fd7.jpg)

The type of fastest Pokémon is Flying.

- Which type of Pokémon has the best attack?
![best_attack](https://user-images.githubusercontent.com/39379425/152195079-820f8603-83d3-4316-a64f-86492d58f8e4.jpg)

Dragon appears here, it is also the type of pokémon which has the best attack.

- Which type of Pokémon has the strongest defense?
![strongest_defense](https://user-images.githubusercontent.com/39379425/152194953-46f59ece-25e6-4bb3-b933-d9e62db9416b.jpg)

Still is the type of pokémon which has the strongest defense.

- Which type of Pokémon has the strongest total strength on average?
![total](https://user-images.githubusercontent.com/39379425/152194839-20a3dd01-75f1-41d6-9f58-d7e2eb6938f5.jpg)

Again Dragon is on here, it is the type of pokémon which has the summary of all stats strongest strength on average.

- What is the relation between Total, Generation and Legendary?
![total_generation_legendary](https://user-images.githubusercontent.com/39379425/152194843-ae17c4da-af2e-43a1-bbfc-447472f341a3.jpg)

![total_generation_legendary_sep](https://user-images.githubusercontent.com/39379425/152194857-1fb578bb-efdb-4cab-b515-a9803aaacb5b.jpg)

The generation 1 has more legendary pokémon, considering the total.

- How many legendary pokémons are there in each generation?
![generation_legendary](https://user-images.githubusercontent.com/39379425/152194833-9dad3407-0152-4141-8367-5942329659bf.jpg)

The generation 3 has more legendary pokémon, while the generation 2 has less.

- What is the distribution between Generation and Speed?
![generation_speed](https://user-images.githubusercontent.com/39379425/152194834-00f9b775-0015-451d-8f47-b321be6a1d7f.jpg)

We can check out a bit more the numerical values density (median, interquartile range, max, min...). We can realize the generation 4 has the highest median, and the most of its data is in the q1 (first quartile), so there is a lot of data in the range of 25% of the data.

- What is the distribution of Legendary?
![legendary](https://user-images.githubusercontent.com/39379425/152194835-24ce2f06-f7e1-4ca1-adde-68730ec00418.jpg)

There are many more legendary pokémon than non-legendary.



















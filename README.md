# Analysis of the Penguins at Palmer Archipelage
This repository focuses on performing data analysis to uncover interesting patterns and insights from the physical measurements and characteristics of three penguin species: Adélie, Chinstrap, and Gentoo. Additionally, the project explores training machine learning models to predict species or other features based on the dataset.

![yfzm6eoem0641-1742372834](https://github.com/user-attachments/assets/b59a13ca-e29b-4405-ac32-d814743e10a5)

The dataset contains the following columns:



| Column Name             | Description                                                                     |
|-------------------------|---------------------------------------------------------------------------------|
| **Species**             | The species of the penguin (*Adélie*, *Chinstrap*, or *Gentoo*).               |
| **Island**              | The island where the penguins were observed (*Torgersen*, *Biscoe*, or *Dream*).|
| **Culmen Length (mm)**  | The length of the penguin's culmen (upper ridge of the beak) in millimeters.    |
| **Culmen Depth (mm)**   | The depth of the penguin's culmen in millimeters.                              |
| **Flipper Length (mm)** | The length of the penguin's flipper in millimeters.                            |
| **Body Mass (g)**       | The weight of the penguin in grams.                                            |
| **Sex**                 | The gender of the penguin (*Male* or *Female*).                                |
| **StudyName**           | The study during which the measurements were taken.                           |
| **Delta 15 N (o/oo)**     | Ratio of the stable isotopes Nitrogen-15 (15N) to Nitrogen-14 (14N) in a sample, expressed in parts per thousand (‰, "o/oo"). |
| **Delta 13 C (o/oo)**    | Ratio of the stable isotopes Carbon-13 (13C) to Carbon-12 (12C) in a sample, also expressed in parts per thousand (‰, "o/oo"). |

---

# Study and Island distrubution
How many datapoints where collected per study and island.

![obraz](https://github.com/user-attachments/assets/a9be2493-276b-43ab-8090-b5470acef43a)

# Species distribution
Number of penguins per species and their distribution per study and islands.

![obraz](https://github.com/user-attachments/assets/94cd701d-7420-4350-bda5-72d6fcaa325c)
Gentoo penguins are only found on Biscoe island while, chinstrap penguins only on Dream island.

Biscoe island has the highest number of penguins, but only gentoo species.

Adelie penguins are rather evenly distributed across all 3 islands.

# Heatmap of number of penguins in each study and island

![obraz](https://github.com/user-attachments/assets/01dbc70b-827c-425e-b5f6-e1e531d9e734)

# Body statistics analysis
Analysis of culmen length, depth, flipper length and body mass, and their relationships with each other.

## Histogram distribution
![obraz](https://github.com/user-attachments/assets/34303b7a-82db-4992-addb-0db37b6818f5)

## Pairwise relationships
Males vs females show similar patterns in every species, with males being larger.

Gentoo penguins are distinguishably heavier than other species, with shallower culmens
![obraz](https://github.com/user-attachments/assets/8bff6c7a-7e15-46f9-8e6d-b1d067b0b436)
![obraz](https://github.com/user-attachments/assets/07b8670f-002f-4220-8bd1-8da8f7654eba)

## Correlation heatmap
The differences in correlations suggest that each species might occupy distinct regions in these measurement distributions.
![obraz](https://github.com/user-attachments/assets/9c60fcb7-55f9-40d9-bc74-01f836f93b86)

## Sex differences
![obraz](https://github.com/user-attachments/assets/d5316c66-155a-4cec-8728-6ce9ef7fb1c4)
## Regression analysis
![obraz](https://github.com/user-attachments/assets/0f7fad30-22f3-43dc-bc29-bf0125c5bbce)
### By sex
![obraz](https://github.com/user-attachments/assets/55d4e6c6-546b-4c5c-8a09-72afcb1e8693)
![obraz](https://github.com/user-attachments/assets/f2b43588-cd26-44b2-883a-05427c307d72)
![obraz](https://github.com/user-attachments/assets/ed9a37bf-46b9-40a4-87c8-72521cb4d6ed)

### By species
![obraz](https://github.com/user-attachments/assets/485f089b-5682-45e1-abfa-52481aeca1cf)
![obraz](https://github.com/user-attachments/assets/f91dbef8-04f0-43fb-9107-99333999d5a1)
![obraz](https://github.com/user-attachments/assets/aff6c65a-96ca-4ad9-9ce0-86dd6aa12562)

## Joint plots
Differences between Gentoo and other species are very visible.

![obraz](https://github.com/user-attachments/assets/8a924d7e-67d9-45b2-8738-4024326a3aca)
![obraz](https://github.com/user-attachments/assets/b1c2a46e-8b93-45f8-ba03-f45ed76e801e)
![obraz](https://github.com/user-attachments/assets/131d55ae-f98d-4d52-93aa-17660405000c)



# Feeding statistics analysis
## Delta 15 N vs Delta 15 C
Typically, higher δ15N values indicate higher trophic levels in the food web because nitrogen isotopes become enriched as they move up the trophic chain (e.g., from plants to herbivores to predators).

δ13C values are used to infer sources of carbon in an organism's diet and can differentiate between marine and terrestrial food sources or between different photosynthetic pathways (e.g., C3 vs. C4 plants).

![obraz](https://github.com/user-attachments/assets/ae8a5669-f6e6-4461-abce-4cca5011f14d)


Delta 15N values in this range typically indicate a diet consisting of mid-level predators like small fish, squid, or krill.

Delta 13C values suggests the penguins primarily forage in a terrestrial or nearshore marine environment.

The lack of spread in the data suggests minimal variation in diet and foraging behavior across individuals.
The stable values could suggest consistent environmental conditions or food availability in the penguins' habitat.

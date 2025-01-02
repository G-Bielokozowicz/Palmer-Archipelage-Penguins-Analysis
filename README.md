# Analysis of the Penguins at Palmer Archipelage
This repository focuses on performing data analysis to uncover interesting patterns and insights from the physical measurements and characteristics of three penguin species: Adélie, Chinstrap, and Gentoo. Additionally, the project explores training machine learning models to predict species or other features based on the dataset.

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

---
## Interesting insights
Gentoo penguins are only found on Biscoe island while, chinstrap penguins only on Dream island.

Biscoe island has the highest number of penguins, but only gentoo species.

Adelie penguins are rather evenly distributed across all 3 islands.

Gentoo penguins are much heavier than other species and have more shallow culmnes.

Males of each species are bigger than females.

Penguins with longer flippers are heavier, but have more shallow culmens.
# Study and Island distrubution
How many datapoints where collected per study and island.

![obraz](https://github.com/user-attachments/assets/a9be2493-276b-43ab-8090-b5470acef43a)

# Species distribution
Number of penguins per species and their distribution per study and islands.

![obraz](https://github.com/user-attachments/assets/94cd701d-7420-4350-bda5-72d6fcaa325c)

# Heatmap of number of penguins in each study and island
The differences in correlations suggest that each species might occupy distinct regions in these measurement distributions.
![obraz](https://github.com/user-attachments/assets/01dbc70b-827c-425e-b5f6-e1e531d9e734)

# Body statistics analysis
Analysis of culmen length, depth, flipper length and body mass, and their relationships with each other.

## Histogram distribution
![obraz](https://github.com/user-attachments/assets/34303b7a-82db-4992-addb-0db37b6818f5)

## Pairwise relationships
![obraz](https://github.com/user-attachments/assets/bcd884cc-b70f-46dc-bf22-42898137ecfb)

## Correlation heatmap
![obraz](https://github.com/user-attachments/assets/9c60fcb7-55f9-40d9-bc74-01f836f93b86)

## Regression analysis
![obraz](https://github.com/user-attachments/assets/0f7fad30-22f3-43dc-bc29-bf0125c5bbce)

## Joint plots
![obraz](https://github.com/user-attachments/assets/8a924d7e-67d9-45b2-8738-4024326a3aca)
![obraz](https://github.com/user-attachments/assets/b1c2a46e-8b93-45f8-ba03-f45ed76e801e)
![obraz](https://github.com/user-attachments/assets/131d55ae-f98d-4d52-93aa-17660405000c)

## Body attributes by sex 
![obraz](https://github.com/user-attachments/assets/d5316c66-155a-4cec-8728-6ce9ef7fb1c4)

## Regression analysis by sex
![obraz](https://github.com/user-attachments/assets/55d4e6c6-546b-4c5c-8a09-72afcb1e8693)
![obraz](https://github.com/user-attachments/assets/f2b43588-cd26-44b2-883a-05427c307d72)
![obraz](https://github.com/user-attachments/assets/ed9a37bf-46b9-40a4-87c8-72521cb4d6ed)

## Pairwise relationships by species
![obraz](https://github.com/user-attachments/assets/fbfafffb-83e9-4b97-9c5f-a32cfd3f46f1)


## Regression analysis by species
![obraz](https://github.com/user-attachments/assets/485f089b-5682-45e1-abfa-52481aeca1cf)
![obraz](https://github.com/user-attachments/assets/f91dbef8-04f0-43fb-9107-99333999d5a1)
![obraz](https://github.com/user-attachments/assets/aff6c65a-96ca-4ad9-9ce0-86dd6aa12562)


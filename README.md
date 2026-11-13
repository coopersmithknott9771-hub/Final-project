# Final-project

In this google colab notebook I perform a EDA on the first 6 generation of pokemon.

https://www.kaggle.com/datasets/mlomuscio/pokemon

credit to Michael Lomuscio on kaggle.com for posting this dataset for free and letting me use it.

The main reason I decided to do pokemon was because I had a few questions I wanted to answer.

What is the most common type 1 and type 2 for pokemon?
What is the correlation of all the stats of all the pokemon
How could I use this data?


As for the cleaning methods I used, the data was already very clean but I did decide not to include mega evolutions.
I simply just made a df for each generation without mega evolutions

then I sorted the type 1 and type 2 pokemon into their own groups

I did this to make any sorting easier and to have them all grouped together

Then I used some functions to see what the most common type 1 and type 2 were

''' most_common_type_1 = Pokemon['Type 1'].mode()[0]
print(f'The most common type 1 is {most_common_type_1}')

most_common_type_2 = Pokemon['Type 2'].mode()[0]
print(f'The most common type 2 is {most_common_type_2}') '''

Then I made some visualizations of this data to back up my functions
<img width="1229" height="702" alt="image" src="https://github.com/user-attachments/assets/547d18b9-a7bd-402e-bebb-fcfbfd40088e" />
And came to the conclusion that water types were the most common type 1 in the 6 generations, I also did the same for all the type 2

<img width="1242" height="702" alt="image" src="https://github.com/user-attachments/assets/f53d4a3c-0e94-4107-834a-0206233a1a92" />
And here I came to the conclusion that flying types were the most common type 2

Finally I made a heatmap of all the stats
<img width="764" height="682" alt="image" src="https://github.com/user-attachments/assets/f23b8320-0a3c-4407-a928-9cf0da4585dd" />

Along with a little surprise at the end just for fun that lets you look any pokemon name and see its stats

To come back around to these questions I asked

What is the most common type 1 and type 2 for pokemon?
  The most common type 1 is water and the most common type 2 is flying
  
What is the correlation of all the stats of all the pokemon
  Total is connected to everything
  sp. atk, attack and sp.def have the highest correlation with total
  sp. def and defense have a very strong correlation
  atk and sp. def also have a strong correlation
  speed has about no correlation to defense
  
How could I use this data?
  I can use this data for a few things. I can try to predict the next generation type, I can use this information in the games, and I can show this data to others so they can see it and use it for similar or completely different purposes

Again thank you to Michael Lomuscio on kaggle.com for this data




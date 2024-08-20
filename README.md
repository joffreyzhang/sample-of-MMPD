## Introduction
Due to the size of our dataset and copyright concerns, we only offer a sample of it. We will release our whole dataset after paper is accepted. This sample is randomly sampled in our PersonaMov dataset. The movie is called Taxi Driver which is very popular all around the world, directed by Martin Scorsese and starred by Robert Deniro.
### Structure of This Sample
- The JSON file contains the dialogues information with personality and relationshio annotation
- The .mp4 file is clipped according to the timestamp in JSON file.
- The .mp3 file is extracted from .mp4 file using FFmpeg.
- The movie1.ipynb contains the code of scraping data from website and some relevant pre-process.
- The script.ipynb contains the program of how to use GPT to annotate data.
- The final_list1.xlsx includes all the characters in movies and Tv shows.

Each video clip of our dataset is tagged with a "Scene" identifier, which likely refers to a specific segment or moment within a larger narrative or dataset. The ''Dialogue'' field contains an array of objects, each providing a detailed description of a scene and dialogues between characters. The dialogues are presented with time corresponding timestamps, too. The ''Relationship'' field within this object provides a summary or interpretation of their interaction, in this case, indicating a professional relationship with an element of fondness between Gatsby and Daisy. Finally, the ''Personality'' section provides personality profiles for the characters mentioned in the scene, where their personality type distribution are listed along with a ''Votes Distribution'' field.

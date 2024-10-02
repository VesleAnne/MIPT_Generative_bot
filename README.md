# Generative_bot
A generative chatbot that should talk like the character Barnin Stinson from "How I Met Your Mother". The dialog transcripts were downloaded from https://scriptmochi.com/tv-series/how-i-met-your-mother. gpt2 was chosen as the model. The bot ended up being dumb and not much like the specified character. Sometimes it spoke using phrases from Harry Potter for some reason. 
Plans: Try to expand the dataset by possibly generating similar phrases and then retrain the model. 

Upd. T5 on inference shows much better results. Definitely the problem with gpt2 is the model itself. But it still looks faintly like a character, although there are some similarities. I guess the problem is lack of data for training. In the future I plan to use Bro code to make a bigger dataset and RAG to improve results. 

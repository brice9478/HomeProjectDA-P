# Organisation

- from the 16th to the 25th of October, spent that time choosing the dataset, wondering whether my initial idea could be viable (Overwatch), which in fact was but on some specific points, it's a bit difficult to get good conclusion.
Last week (26/10 to 01/11):
- first tried to display the data from the datasets, trying to make a plot that was visually understandable and useful.
- then made some written conclusion about why win rates were changing by using data via web scraping that I found on the Overwatch official website
- then, towards the end of the week, realized I forgot to add the merging part between the data from the dataset and the data from the web scraping (didn't really know what to do here honestly)
- added comments and the conclusion
(and realising too late I had to push progressively on github)

# Prompts

Link: https://claude.ai/share/55d1a4d9-72ac-48cf-a0d0-17112b428424

- First 4 prompts asking if choosing overwatch for the subject is good or not. Asking about other alternatives, but still choosing overwatch in the end.
- Asking about how would I use a website with current data if the dataset is way older -> decision: not using a website for data. Only for webscraping.
- Asking about how to use the official website of overwatch for the web scraping according to the subject -> decision: simply scrapping the text, manually define what is a nerf and what isn't
- Asking how to make a plot stay on a scale of 100 even if all the values are 60 or less -> code generated
- Asking how to make a plot with multiple layers to use multiple dataframe at the same time -> code generated
- Asking how to display the name of the missing hero between the season 1 and seanson 2 datasets -> code generated
- Asking how to use every ranks to display the win rates differences and not just the "All" stat -> code generated and modified
- More asking and trying to figure out how to display multiple layer in a more understandable way -> trial and error, code generated
- Asking what the AI thinks about the "All" stat by giving the results I got using the datasets -> asking for confirmation, "All" was indeed an obscure stat
- Asking for algorithm that will do the web scraping based on a list of all the text cells that contains specific text patterns -> code generated
- Asking how to manually register texts as buffs or nerfs for those which didn't correspond to any or corresponded to multiple pattern while still being in the "Hero Updates" part on the website
- Asking for a simplification of an unnecessarily complicated code -> code generated
- Asking for a revue by giving current result -> elements were missing
- Asking what would I need to implement and for what reason -> over multiple prompts, trying to figure out what the AI was talking about + code generated
- Asking whether adding more lines would be worth it -> decision: no
- Asking for a description of each bloc of code he gave me for the elements that were missing from my original work
- Revue conclusion -> not good enough, needs to be improved -> which I tried to improve without losing the essence of my own conclusions

# Kaggle dataset
https://www.kaggle.com/datasets/mykhailokachan/overwatch-2-statistics/data
(I just barely modified the name of the .csv by removing the date 2023-05-06 at the end, which corresponds to the time the dataset was made, and not when the seasons took place, which could be confusion)

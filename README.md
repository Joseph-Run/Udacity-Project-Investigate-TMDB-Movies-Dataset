# Investigate the TMDb movie dataset

This project was done as part of Udacity's Data Analyst Nanodegree - Term 1.

The TMDb Movie dataset, one of Udacity's curated datasets has been selected for investigation using NumPy and Pandas. The dataset is a collection of information on around 10000 movies. For each movie, the dataset includes information on aspects such as popularity, budget, revenue, cast, directors, production house, date of release, runtime, and its rating. 

## Outline of analysis
* Assessed the data and brainstormed questions that could be answered using the data 
* Performed necessary cleaning steps to unify formats, deal with missing data and prepare the dataset for analysis
* Wrangled and explored the data using Pandas and Numpy to gather insights about the relationship between different aspects, created visualizations using matplotlib and made inferences to answer research questions  

## Research Questions
1. Genres with the most favourable ratings?
2. 2 Actors with the most appearance in movies? 
3. Correlation between Movie Budget and Popularity?
4. Top 10 Movies by Profit?


### Which Genres recieve more favourable ratings

 From our Analysis, we deduced that Animation was the most popular movie genre, followed by Adventure and Fantasy. 
Limitations: There were some rows who had null values in the genre column so they had to be dropped. There are various genres in every movie. Nevertheless, every movie typically has one core genre and a few smaller ones. For instance, Avatar falls within the Action and Science Fiction categories, according to Google search results. Our analysis, however, revealed that the film also contains Adventure and Fantasy aspects. This classification is therefore ambiguous, and because of this ambiguity, we have classified Avatar as a Adventure, science fiction, action, and Fantasy movie. The same film is counted in each of the four genres.

### Actors with the most appearances in movies

 As Evident in the bar chart, Robert De Niro has the most appearances with over 70 movie appearances, followeed closely by Samuel L. Jackson. 
 We can also see that there's not much difference between the top actors with the exception of the Top 4.
Limitations: Some of the rows had the cast missing so also had to be dropped, this made our top actor not inclusive of all movies

### Correlation between Movie budget and Popularity

 Higher budget movies usually had more popularity as compared to lower budget movies.
Limitations: 50% of the budget and revenue values are both zero. Due to this, only about 50% of the rows could be used for income and budget analysis, and we were unable to provide information for the remaining 50%.

### Top 10 Movies by Profit (adjusted for inflation)

 We can identify the following movies as the top 10 Movies
 - Star Wars
 - Avatar
 - Titanic
 - The Exorcist
 - Jaws
 - E.T The Extra Terrestial
 - Star Wars: The Force Awakens
 - The Net
 - One Hundred and One Dalmatians
 - The Empire Strikes Back

Limitations: Although each movie's revenue and budget were known, there was no information on its profit, so I computed it.

# Pokémon: The Myths and The Legends 
Final Project for Data 311 - Machine Learning. This was considered the top project in the 2019 year. The project goal was to analyze some amount of data using various machine learning models and techniques in R to come to some deeper understanding about the given data.

## Contributors:
* **Barret Jackson** - [bearitt](https://github.com/bearitt)
* **Emily Medema** - [emedema](https://github.com/emedema)
* **Kathryn Lecha** - [kzlecha](https://github.com/kzlecha)
* **Lauren St.Clair** - [laurenstclair](https://github.com/laurenstclair)

## Data Source
The dataset examined, accessed from Kaggle and collected by [alopez247](https://www.kaggle.com/alopez247), is [Pokémon for Data Mining and Machine Learning](https://www.kaggle.com/alopez247/pokemon), a set of Pokémon with related statistics and descriptors.
The set contains 721 observations and 23 variables, several of which are categorical.

Of the numerical predictors, the majority are the Pokémon statistics, such as *Total*, *Attack*, *Defense*, *HP*, while others relate to body descriptors such as *Weight_kg* and *Height_m*.
The other numerical predictor, *Pr_Male* is indicative of the probability that when a Pokémon is caught it will be male.
Finally, *Catch_Rate* is a number bounded by 3 and 255 that refers to the ease of catching a Pokémon, where the higher the catch rate, the easier it is to catch the Pokémon.
The statistics of Pokémon were analyzed through a variety of models attempting to predict whether or not a Pokémon is of the legendary type. In order to predict legendary status, the *isLegendary* and *Total* variables were tested against a range of predictors within the Pokémon dataset.

## Research Focus
1. Analysis of legendary pokemon
  * What is the difference between a legendary pokemon and a non-legendary pokemon?
  * What attributes determine this
  * Which machine learning models preform better in modeling this relationship?
2. Probability of being Male
  * How does the probablity of being male affect other statistical properties about a species of pokemon?
  * How does having a gender affect the statistics of a pokemon?

## Conclusions
It was determined through analyses of the Pokémon dataset that Pokémon can be surprisingly progressive, 
however, there remain residual aspects of sexism specific to gendering and fundamental statistics.
Through analyses, the investigation suggested that the statistics of Pokémon can help in predicting a Pokémon’s gender and as well its likelihood of being legendary.
It was found that Pokémon with the highest probability of being female, according to *Pr_Male*, had the lowest *Attack* and *Defense* values.
Similarly, it appears that there is a correlation between catchability and gender, such that Pokémon with lower statistics like *Attack* or *Defense*
are easier to catch and more likely to be female.

It could be said that this bias towards males could be a product of Pokémon’s original target audence.
Pokémon was released in 1996, during a time when video games were primarily targeted at males.
While the distinction of “stronger” traits ascribed to male Pokémon may be attributed to layman views of sex determined roles in the animal kingdom,
it may also be a product of the game developers own internalized biases.

Where Pokémon may be considered more progressive is in its depiction of the legendary Pokémon type, which are the “strongest” types of the Pokémon universe.
While there is a functional reason for the majority of legendary Pokémon being genderless, since it disallows for the ability to breed,
the representation of non-binary gender identity is progressive and incredibly important as game designers could have simply have made all
legendary Pokémon one gender.

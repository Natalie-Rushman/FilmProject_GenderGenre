## Film Analysis based on Genre and Gender

![filmbanner_c_Gerd-Altmann_Pixabay.png](attachment:filmbanner_c_Gerd-Altmann_Pixabay.png)

We reproduce general assumptions and prejudices every day. Automated film suggestions are no exception to that since there are based on given similarities. With the present analysis I like to have a closer look at the participation of male and female actors in films that belong to certain genres:

- Is the gender distribution the way we assume it, primarily male protagonists in action and science fiction movies in comparison to more female lead characters in romantic comedy or family movies?
- Does the gender-related casting have any impact on the films' popularity? Would it be, for example, irritating to the audience if there were more women starring in action films? Or, would it be, on the contrary, even welcomed?
- Can we still detect a certain pattern concerning the casting or is there any change in modern films?
- Could an automated recommendation system based on different feautures than pure similarity change such coded bias?

***

The dataset was provided with a Public Domain Common Licence by Stéphane Rappeneau on __[Kaggle](https://www.kaggle.com/stephanerappeneau/350-000-movies-from-themoviedborg?select=AllMoviesCastingRaw.csv)__. It contains ca. 350.000 observations from themoviedb.org as the primary data source. I chose two tables giving information on movies, genres and cast, and merged them to perform EDA on the following features:

#### Attributes contain:
<b>title:</b> Name of the film<br>
<b>genre:</b> Category of the film<br>
<b>tagline:</b> Related keyword line<br>
<b>language:</b> Original language of the film<br>
<b>year:</b> Year of film release (1900-2017)<br>
<b>revenue:</b> Film gross at box offices<br>
<b>director_name:</b> Director of the film<br>
<b>director_gender:</b> Director of the film<br>
<b>actor1_name:</b> Main starring actors<br>
<b>actor1_gender:</b> Main starring actors<br>
<b>actor2_name:</b> Second starring actors<br>
<b>actor2_gender:</b> Second starring actors<br>
<b>vote_average:</b> Average score<br>
<b>vote_count:</b> Number of votes<br>
<b>imdb_id:</b> Relational IMDB id<br>
<b>summary:</b> Film description<br>

### Tools
- Python
- Pandas
- Seaborn
- Matplotlib

### Procedure
- Data Cleaning
- Exploratory Data Analysis
- Plotting

<div class="alert alert-block alert-info">
<b>Note:</b> The project is part of the Ironhack Bootcamp in Data Analytics (Berllin, August-October 2021). </div>


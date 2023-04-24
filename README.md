# Movie-Finder

<h4>Original Question:</h4> Create a Movie Randomizer that uses Tableau dashboards and have a button that will randomly choose a movie/series from the database of Disney+, Netflix and Amazon Prime movies/Series.

<h3>Insights:</h3>

<h4>Outcome:</h4> Creating a button that will randomize the dataset and display the result ended up being almost impossible to create on tableau, this changed the whole dashboard from being a randomizer to a movie finder. That uses title search to find a movie you are looking for, then displaying the relevant information on the dashboard (age restriction, platform, run time, genre, description and a few more insights)


Python was used to join the three csv files together, to create a single dataset. This proved easy as all three datasets had the exact same number and named rows. 

<img src="https://user-images.githubusercontent.com/123564919/233943556-27348f34-bc1e-447a-b80f-76aa54633855.JPG" width="90%"></img>
<h6>Python Code-Pycharm</h6>

Using this dataset for the orginal question meant not needing to use SQL to create and sub tables for insights, letting us move straight to Tableau to create our dashboard.

Creating the dashboard involed creating Gauges using pie charts and circles, also involed creating multiple calculated fields to display the gauges and insights correctly on the dashboard.

<img src="https://user-images.githubusercontent.com/123564919/233943568-6e06ea1a-75cb-4398-b95e-db971c25f198.png" width="90%"></img>
<h6>Movie Finder Tableau</h6>

<img src="https://user-images.githubusercontent.com/123564919/233948104-d3e78bde-337b-4460-8e26-ee13dd32cb15.png" width="90%"></img>
<h6>Movie Finder Tableau</h6>

<img src="https://user-images.githubusercontent.com/123564919/233948112-66fffc4f-b933-46cf-937e-2697ce9d4a9f.png" width="90%"></img>
<h6>Movie Finder Tableau</h6>

Tableau Link: https://public.tableau.com/app/profile/gavin.lestrange/viz/MovieRandomizer/MovieSeriesDashboard

<h4>Conclusion:</h4> My conclusion with the project is that I over estimated the use of Tableau trying to create a randomizer, I should of created a dashboard using python, as that would of given me all the functionality I needed. I was able to learn many new skills in Tableau such as creating a gauge and getting more indepth with the calculated fields and their calculations.


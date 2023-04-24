# Movie-Finder

<h4>Original Question:</h4> Create a Movie Randomizer that uses Tableau dashboards and have a button that will randomly choose a movie/series from the database of Disney+, Netflix and Amazon Prime movies/Series.

<h3>Insights:</h3>
<h4>Outcome:</h4>Creating a button that will randomize the dataset and display the result ended up being almost impossible to create in Tableau. This changed the whole dashboard from being a randomizer to a movie finder that uses title search to find a movie you are looking for, then displaying the relevant information on the dashboard, such as age restriction, platform, runtime, genre, description, and a few more insights.


Python was used to join the three CSV files together to create a single dataset. This proved easy, as all three datasets had the exact same number and named rows. 

<img src="https://user-images.githubusercontent.com/123564919/233943556-27348f34-bc1e-447a-b80f-76aa54633855.JPG" width="90%"></img>
<h6>Python Code-Pycharm</h6>

Using this dataset for the original question meant that there was no need to use SQL to create and subset tables for insights, allowing us to move straight to Tableau to create our dashboard.

Creating the dashboard involved creating gauges using pie charts and circles. It also involved creating multiple calculated fields to display the gauges and insights correctly on the dashboard.

<img src="https://user-images.githubusercontent.com/123564919/233943568-6e06ea1a-75cb-4398-b95e-db971c25f198.png" width="90%"></img>
<h6>Movie Finder Tableau</h6>

<img src="https://user-images.githubusercontent.com/123564919/233948104-d3e78bde-337b-4460-8e26-ee13dd32cb15.png" width="90%"></img>
<h6>Movie Finder Tableau</h6>

The big issue with the data is that during the joining of the csv files through python, we had issues using the UTF-8 encoder and has to use the ISO-8859-1 encoder instead. Now That we have worked with the data, we can see that thier are many errors in the original csv files, these errors are because many movies use unique characters as they are from different countries. These issues have caused certain title and descriptions to have the wrong characters displayed.

<img src="https://user-images.githubusercontent.com/123564919/233948112-66fffc4f-b933-46cf-937e-2697ce9d4a9f.png" width="90%"></img>
<h6>Movie Finder Tableau</h6>

Tableau Link: https://public.tableau.com/app/profile/gavin.lestrange/viz/MovieRandomizer/MovieSeriesDashboard

<h4>Conclusion:</h4>My conclusion with the project is that I overestimated the use of Tableau in trying to create a randomizer. I should have created a dashboard using Python, as that would have given me all the functionality I needed. However, I was able to learn many new skills in Tableau, such as creating a gauge and getting more in-depth with the calculated fields and their calculations.


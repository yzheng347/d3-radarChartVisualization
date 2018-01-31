# Video Game Sales Visualization
This is an ongoing data visualization project aims to create a tool for anyone who is interested in visualizing and consuming video game sales data. I also used interaction techniques that allow people to intuitively explore the dataset.


### Vis Description:
* The visualization design currently contains three components: a radar chart, a treemap, and a line graph.
* The **line graph** shows the general trend of global sales of each genre. The user is able to zoom in or out the y-axis to better display the data of different period of time.

* The **radar chart** allows the user to display and compares the global sales of each genre in any selected year. The year selection is achieved by a sliding bar below the radar chart.
* In the radar chart, each node on the genre axis represents the global sales of that genre in the selected year. Mouse over each node to read the total sales in million dollars.
* The node in every genre axis has a distinct color, which corresponds to the same genre representation in the line graph.

* The **treemap** elaborate on the selected genre from radar chart and display more detailed information.
* The default display of the treemap is the overall global sales across the entire dataset. The treemap updates when the user clicks on a genre from radar chart display. Branches of the treemap are major publishers, and the leaves are the individual games.
* The treemap can be modified to display either by the global sales, which reflected by the area of the rectangles or number of games sold, where each small rectangle is the same size.
* Mouse over the small rectangle that represent an individual game to display a text box that provides more detailed information such as game tittle, publisher, platform and its global sales.


### Domain and Data:

* The dataset used in the visualization, "vgsales" was collected by sales data from [VGChartz Game Database](http://www.vgchartz.com/gamedb/), and it describes the major video game sales from 1980 to 2015.
* The dataset contains 16600 intances, and has 7 attributes: global sales ranking, game title, platform, year of release, genre, publisher and sales by different regions.

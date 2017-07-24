# Video Game Sales Visualization
### Vis Description:
* The visualization design contains three major components: a radar chart, a treemap, and a line graph.
* The **line graph** shows the general trend of global sales of each genre. It has a single interactive feature: the users are able to zoom in or out the y-axis. Notice that from the year of 1980 to 1995, the sales are relatively low compared to the sales in later years; and the lines are indistinguishable from each other. This feature helps better display the data of different period of time.
* The **radar chart** allows the user to display and compares the global sales of each genre in any selected year. The year selection is achieved by this sliding bar below the radar chart: the user can click on and drag the sliding bar through years axis. When the mouse is released, the radar chart is updated. Each node on the genre axis represents the global sales of that genre in that year. Mouse over each node to read the total sales in million dollars. The node in every genre axis has a distinct color, which corresponds to the same genre representation in the line graph.
* Notice that certain genres are much more popular than others, that is, their sales are considerably larger. Hence, the data is preprocessed by taking the square root to reduce the variance before passing into the radar chart.
* The radar chart also skips the genres that has zero sales to avoid very thin lines, and make it more aesthetically appealing.
* The **treemap** further elaborate on the selected genre from radar chart and display more detailed information. The default display of the treemap is the overall global sales across the entire dataset. The users can click on a genre from radar chart to display corresponding treemap. Now the treemap is updated and broken down by publishers, and the leaves being the individual games. The treemap can be modified to display either by the global sales, which reflected by the area of the rectangles or number of games sold, where each small rectangle is the same size. Mouse over the small rectangle that represent an individual game to display a text box that provides more detailed information such as game tittle, publisher, platform and its global sales.


### Domain and Data:

* The dataset used in the visualization, "vgsales", describes the total video game sales from 1980 to 2020.
* It contains 16600 intances, and has 7 attributes: global sales ranking, game title, platform, year of release, genre, publisher and sales by different regions.
* The dataset was collected by sales data from  http://www.vgchartz.com/gamedb/
* Moreover, this dataset was collected during the year of 2016, the data in year 2016 is incomplete, and therefore omitted from the visualization.



A short video introduction: https://youtu.be/6BFOMD7ORPw
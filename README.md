
# Web-Design-Challenge - Web Visualization Dashboard (Latitude)

## Background

To create a dashboard showing the analysis that was done earlier..
 * To visualize the weather of 500+ cities across the world of varying distance from the equator by utilizing Python library - citipy, and the OpenWeatherMap API and to create a representative model of weather across world cities.

![WebVisualizations/Images/index.jpg](WebVisualizations/Images/index.jpg)

### Resources

1. All the files related to the website are in the root. 

2. 'WebVisualizations' folder contains Images, Resourses, Visualizations as seperate folders.

3. Deployed to GitHub pages.  

4. Site Link : https://v-malm.github.io/Web-Design-Challenge/

## Latitude - Latitude Analysis Dashboard with Attitude

Created a visualization dashboard website using visualizations by plotting [weather data](WebVisualizations/Resources/cities.csv).

In building this dashboard, Created individual pages for each plot and a means by which we can navigate between them. These pages contain the visualizations and their corresponding explanations. This website has 7 pages 
 * The site has a landing page
 * A page where we can see a comparison of all of the plots 
 * A page to view the data used to build the plots displayed on the website
 * 4 pages displayimg each plot and related analysis
  * Button trigger modal to open Linear Regression Model for each visualization.


### Website pages

* A [landing page](https://v-malm.github.io/Web-Design-Challenge/) containing:
  * An explanation of the project.
  * Links to each visualizations page. There is a sidebar containing preview images of each plot, and clicking an image takes the user to that visualization.
* Four [visualization pages](https://v-malm.github.io/Web-Design-Challenge/max_temp.html), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](https://v-malm.github.io/Web-Design-Challenge/comparisions.html) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](https://v-malm.github.io/Web-Design-Challenge/date.html) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table is a bootstrap table component.
    * The source is from exporting the `.csv` file as HTML by first using pandas to read the csv file to a dataframe and then using Pandas method `to_html` that generates an HTML table from the dataframe.


### Navigation

Site has navigation menu at the top of each page that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). The background color changes when the screen is smaller.


### The website has been deployed to GitHub pages.
[Web Visualization Dashboard] (https://v-malm.github.io/Web-Design-Challenge/WebVisualizations/) 
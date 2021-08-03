---
permalink: /index.html
---

# Web-Design-Challenge - Web Visualization Dashboard (Latitude)

## Background

To create a dashboard showing the analysis that was done earlier..
 * to visualize the weather of 500+ cities across the world of varying distance from the equator by utilizing Python library - citipy, and the OpenWeatherMap API and to create a representative model of weather across world cities.

![WebVisualizations/Images/index.jpg](WebVisualizations/Images/index.jpg)

### Resources

1. All the files related to the website are in the root. 

2. 'WebVisualizations' folder contains Images, Resourses, Visualizations as seperate folders.

3. Deployed to GitHub pages.  

4. Site Link : https://v-malm.github.io/Web-Design-Challenge/

## Latitude - Latitude Analysis Dashboard with Attitude

Created a visualization dashboard website using visualizations by plotting [weather data](Resources/cities.csv).

In building this dashboard, Created individual pages for each plot and a means by which we can navigate between them. These pages contain the visualizations and their corresponding explanations.  
 * The site has a landing page
 * A page where we can see a comparison of all of the plots
 * A page displayimg each plot and related analysis
 * A page to view the data used to build the plots displayed on the website


## Latitude - Latitude Analysis Dashboard with Attitude

Created a visualization dashboard website using visualizations created by plotting [weather data](Resources/cities.csv).

In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

### Website Requirements

For reference, see the ["Screenshots" section](#screenshots) below.

The website must consist of 7 pages total, including:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
* Four [visualization pages](#visualization-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a Bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table must be a bootstrap table component. [Hint](https://getbootstrap.com/docs/4.3/content/tables/#responsive-tables)
    * The data must come from exporting the `.csv` file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called `to_html` that allows you to generate a HTML table from a pandas dataframe. See the documentation [here](https://pandas.pydata.org/pandas-docs/version/0.17.0/generated/pandas.DataFrame.to_html.html)

The website must, at the top of every page, have a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown menu on the right of the navbar named "Plots" that provides a link to each individual visualization page.
* Provides two more text links on the right: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). The nav must have similar behavior as the screenshots ["Navigation Menu" section](#navigation-menu) (notice the background color change).

Finally, the website must be deployed to GitHub pages.

When finished, submit to BootcampSpot the links to 1) the deployed app and 2) the GitHub repository.

Ensure your repository has regular commits (i.e. 20+ commits) and a thorough README.md file

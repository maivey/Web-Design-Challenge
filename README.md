# Web-Design-Challenge

Visit my [page](https://maivey.github.io/Web-Design-Challenge/WebVisualizations/index.html)

This script creates a visualization dashboard website using visualizations we've created in WeatherPy. The website will plot weather data.

## Latitude - Latitude Analysis Dashboard with Attitude

In building this dashboard, create individual pages for each plot and a means by which one can navigate between them. These pages will contain the visualizations and their corresponding explanations. It will also have a landing page, a page where we can see a comparison of all of the plots, and another page where one can view the data used to build them.

### Website Requirements


The website consists of 7 pages total, including:

* A ![landing page](WebVisualizations/index.html) containing:
  * An explanation of the project.
  * Links to each visualizations page.
* Four ![visualization pages](WebVisualizations/visualizations), each with:
  * A descriptive title and heading tag.
  * The plot/visualization itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A !["Comparisons" page](WebVisualizations/comparison.html) that:
  * Contains all of the visualizations on the same page so we can easily visually compare them.
  * Uses a bootstrap grid for the visualizations.
    * The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A !["Data" page](WebVisualizations/data.html) that:
  * Displays a responsive table containing the data used in the visualizations.
    * The table is a bootstrap table component.
    * The data comes from exporting the `.csv` file as HTML, or converting it to HTML. 

The website has, at the top of every page, a navigation menu that:

* Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
* Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page.
* Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page.
* Is responsive (using media queries). 




# Web_Visualizations_Dashboard

For this project, I created a visualization dashboard website using visualizations from my weather visualization project. 
In building this dashboard, I created individual pages for each plot and a means by which the user can navigate between them. These pages contain the visualizations and their corresponding explanations. There is also a landing page, a page where the user can see a comparison of all of the plots, and another page where they can view the data used to build them.

The website comprises 7 pages total, including:

* A landing page (`index.html`) containing:
  * An explanation of the project.
  * Links to each visualizations page.
* Four visualization pages(`cloudiness.html`, `humdity.html`, `maxtemp`, `wind.html`), each with:
  * The plot/visualization itself for the selected comparison
  * A paragraph describing the plot and its significance
* A "Comparisons" page](`comparisons.html`) that:
  * Contains all of the visualizations on the same page for easy visual comparison
  * Uses a bootstrap grid for the visualizations
* A "Data" page(`data.html`) that:
  * Displays a responsive table containing the data used in the visualizations
  * The data comes from converting `cities.csv` (Resources folder) file to HTML using pandas
    * The data comes from converting the `.csv` file to HTML using pandas. 
* Has the name of the site on the left of the nav which allows users to return to the landing page from any page
* Contains a dropdown on the right of the navbar named "Plots" which provides links to each individual visualization page
* Provides two more links on the right: "Comparisons" which links to the comparisons page, and "Data" which links to the data page
* Is responsive (using media queries)




￼




# Web Design Challenge

## Task

To create a visualisation dashboard website using HTML and CSS based on weather data and visualisations created in a previous assignment. 

In building this dashboard, there will be individual pages for each plot and a means by which the user can navigate between them. These pages will contain the visualizations and their corresponding explanations. There will also be a landing page, a page where we can see a comparison of all of the plots, and another page where the user can view the data used to build them. 

## Tools and Technologies 

- HTML
- CSS
- Bootstrap
- Python
- Pandas


## Website Layout

The website consists of 7 pages total, including:

* A [landing page](#landing-page) containing:
  * An explanation of the project.
  * Links to each visualisations page. There is a sidebar containing preview images of each plot, and clicking an image takes the user to that visualization.
* Four [visualisation pages](#visualisation-pages), each with:
  * A descriptive title and heading tag.
  * The plot/visualisation itself for the selected comparison.
  * A paragraph describing the plot and its significance.
* A ["Comparisons" page](#comparisons-page) that:
  * Contains all of the visualisations on the same page so they can be visually compared easily.
  * Uses a Bootstrap grid for the visualizations.
    * The grid is two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
* A ["Data" page](#data-page) that:
  * Displays a responsive table containing the data used in the visualisations.
    * The table is a bootstrap table component. 
    * The data comes from converting the `.csv` file to HTML.

The website has, at the top of every page, a navigation menu that:

* Has the name of the site on the lefthand side of the navbar which allows users to return to the landing page from any page.
* Contains a dropdown menu on the righthand side of the navbar named "Plots" that provides a link to each individual visualisation page.
* Provides two more text links on the righthand side: "Comparisons," which links to the comparisons page, and "Data," which links to the data page.
* Is responsive (using media queries). 

## Viewing

View web design at: https://dan1ellec.github.io/dani1ellec.github.io/


## Preview

### <a id="landing-page"></a>Landing page

![Landing page large screen](Images/landingResize.png)


### <a id="comparisons-page"></a>Comparisons page

![comparison page large screen](Images/comparison-lg.png)


### <a id="data-page"></a>Data page

![data page large screen](Images/data-lg.png)


### <a id="visualisation-pages"></a>Visualisation pages

There are four of these, one for each visualisation. Here's an example of one:

![visualize page large screen](Images/visualize-lg.png)



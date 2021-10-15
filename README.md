# CLICK HERE https://arieldunn.github.io/web-design/


# Web Design - Web Visualization Dashboard (Latitude)

## Background

Data is more powerful when we share it with others! Let's take what we've learned about HTML and CSS to create a dashboard showing off the analysis we've done.
## Latitude - Latitude Analysis Dashboard with Attitude

For this homework we'll be creating a visualization dashboard website using visualizations we've created in a past assignment. Specifically, we'll be plotting [weather data](Resources/cities.csv).

In building this dashboard, we'll create individual pages for each plot and a means by which we can navigate between them. These pages will contain the visualizations and their corresponding explanations. We'll also have a landing page, a page where we can see a comparison of all of the plots, and another page where we can view the data used to build them.

![Image 10-14-21 at 9 48 PM](https://user-images.githubusercontent.com/82057838/137419611-772a274d-3e5a-4690-a63b-2d7324c7aec8.jpg)


<img width="1492" alt="Screen Shot 2021-10-14 at 9 48 46 PM" src="https://user-images.githubusercontent.com/82057838/137419616-f93f5766-3818-443e-ab64-878e20d6588a.png">

<img width="1493" alt="Screen Shot 2021-10-14 at 9 49 01 PM" src="https://user-images.githubusercontent.com/82057838/137419622-4c47ca28-34fb-49b8-94f0-bd8df2530ff0.png">
<img width="1499" alt="Screen Shot 2021-10-14 at 9 50 35 PM" src="https://user-images.githubusercontent.com/82057838/137419632-d0a343c7-28a4-4ebc-a6a7-96e488c821b4.png">

<img width="1332" alt="Screen Shot 2021-10-14 at 9 50 18 PM" src="https://user-images.githubusercontent.com/82057838/137419635-3ef3f399-9340-4387-a057-9e39ca400984.png">
<img width="1482" alt="Screen Shot 2021-10-14 at 9 49 45 PM" src="https://user-images.githubusercontent.com/82057838/137419639-7a8b802d-eade-4f50-91f2-b4755a4bfca0.png">

<img width="1290" alt="Screen Shot 2021-10-14 at 9 50 24 PM" src="https://user-images.githubusercontent.com/82057838/137419645-2c0eb300-6c43-45bf-9700-5c07ab032983.png">
<img width="1499" alt="Screen Shot 2021-10-14 at 9 50 00 PM" src="https://user-images.githubusercontent.com/82057838/137419649-3c97a2c2-582f-4e48-a708-f80c930edc8a.png">

<img width="1494" alt="Screen Shot 2021-10-14 at 9 49 16 PM" src="https://user-images.githubusercontent.com/82057838/137419653-a1d66b07-3bfe-46c4-9358-65527e7be5b9.png">



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

### Considerations

* You may use the [weather data](Resources/cities.csv) or choose another dataset. Alternatively, you may use the included [cities dataset](Resources/cities.csv) and pull the images from the [assets folder](Resources/assets).
* You must use Bootstrap. This includes using the Bootstrap `navbar` component for the header on every page, the bootstrap table component for the data page, and the Bootstrap grid for responsiveness on the comparison page.
* You must deploy your website to GitHub pages, with the website working on a live, publicly accessible URL as a result.
* Be sure to use a CSS media query for the navigation menu.
* Be sure your website works at all window widths/sizes.
* Feel free to take some liberty in the visual aspects, but keep the core functionality the same.


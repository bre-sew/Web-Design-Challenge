# Web-Design-Challenge
This challenege utilizes what we’ve learned about HTML and CSS to create a dashboard displaying the analysis conducted for Project 1.

### Website Requirements
The website must consist of 7 pages total, including:

A landing page containing:
- An explanation of the project.
- Links to each visualizations page. There should be a sidebar containing preview images of each plot, and clicking an image should take the user to that visualization.
Four visualization pages, each with:
- A descriptive title and heading tag.
- The plot/visualization itself for the selected comparison.
- A paragraph describing the plot and its significance.
A “Comparisons” page that:
- Contains all of the visualizations on the same page so we can easily visually compare them.
- Uses a Bootstrap grid for the visualizations.
- The grid must be two visualizations across on screens medium and larger, and 1 across on extra-small and small screens.
A “Data” page that:
- Displays a responsive table containing the data used in the visualizations.
- The table must be a bootstrap table component.
- The data must come from exporting the .csv file as HTML, or converting it to HTML. Try using a tool you already know, pandas. Pandas has a nifty method approprately called to_html that allows you to generate a HTML table from a pandas dataframe. See the documentation here

The website must, at the top of every page, have a navigation menu that:
- Has the name of the site on the left of the nav which allows users to return to the landing page from any page.
- Contains a dropdown menu on the right of the navbar named “Plots” that provides a link to each individual visualization page.
- Provides two more text links on the right: “Comparisons,” which links to the comparisons page, and “Data,” which links to the data page.
- Is responsive (using media queries). The nav must have similar behavior as the screenshots “Navigation Menu” section (notice the background color change).
- Finally, the website must be deployed to GitHub pages.

### Considerations
You may use the weather data or choose another dataset. Alternatively, you may use the included cities dataset and pull the images from the assets folder.
You must use Bootstrap. This includes using the Bootstrap navbar component for the header on every page, the bootstrap table component for the data page, and the Bootstrap grid for responsiveness on the comparison page.
You must deploy your website to GitHub pages, with the website working on a live, publicly accessible URL as a result.
Be sure to use a CSS media query for the navigation menu.
Be sure your website works at all window widths/sizes.
Feel free to take some liberty in the visual aspects, but keep the core functionality the same.

Homework 5.

Create a python file that webscrapes GDP by country and plots a stacked interactive bar plot using plotly. Stack countries within regions using the IMF numbers. Please include this in your ipython notebook and output your plot to an html file containing the plot.


Look at the chapter on interactive graphics and, specifically, the code to display a subject's MRICloud data as a sunburst plot. Do the following. Display this subject's data as a Sankey diagram. Display as many levels as you can (at least 3) for Type = 1, starting from the intracranial volume.


Create a simple webpage containing the Sankey graphic and host it on github pages. Instead, you'll have to create a new public repo from your regular github account and add this file. Put the link to your live web page in a markdown cell of your hw5.ipynb file as a text block.


Your homework should include:

A file called hw5.ipynb that has your code for parts 1 and 2.

Two html files, one called sankey.html and one called stacked_bar.html that contain the two plots as html files.

Your hw5.ipynb file should have a text block that contains a link to the live and publicly hosted sankey diagram.
Zip these files for submission. Here's a link for how to host a page on github pages: https://livejohnshopkins-my.sharepoint.com/:v:/g/personal/bcaffo1_jh_edu/IQAXQEct9uwRT60rvaa9zeiUAXaYV3cXsyoU1KZGtFR0HJI
Remember you will need to create your own github repository containing a live link to your sankey html file. So, when I click on that link it should show a page containing your plot. Note plotly objects contain a method called to_html() which is useful for creating an html file.

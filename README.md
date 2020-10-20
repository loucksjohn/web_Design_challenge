# web_Design_challenge

In this repository for the Web Design homework, you will find find all of the elements used to create my Data
Visualization website.  The assignment was to re-purpose the visualizations that were created during the Python API
homework and create a dashboard that contains a landing page, pages for each individual plot, a comparison page, a page to hold all
the data that was used to create the plots, and a navigation menu that allows the user to easily move through all the different pages.

All of the .html files used to create the website are here in this repository along w/ a 'Resources' folder than contains the CSV
file (cities.csv) which houses the data from which all of the plots were generated.  Also in that 'Resources' folder are all of 
the images that were created when plotting the data.  And since we were to use specific components of the Bootstrap tookit you will
find a self-contained bootstrap template (replacing the links to css/js files from CDNs with local files) in the 'assests' folder.

One final component of the project being housed in this repository a jupyter notebook file.  In order to create the 'Data' page, it
was necessary to convert the cities.csv file into html.  And since pandas has a method for converting a pandas dataframe into html, 
I read the cities.csv file into my jupyter notebook as a dataframe, and then used the 'to_html' function from pandas.  After that I
was able to write data (in table form) into an html document using 'html_file.write'.  From there it was just a matter of adding in the 
necessary bootstrap components to make the table responsive, add the navigation pane to the top of the page, and follow the format of the 
other pages. 

The initial set-up part of the process was probably the part that took up the most time.  I had to, first of all, wrap my brain around how
the whole site was to be laid out and everything was to be connected.  And after that it was a matter of picking a couple different elements
from bootstrap templates, I then just had to go about plugging in the different links and images.  I found a really cool zombie-themed Lorem
Ipsum (zombieipsum.com) to use a placeholder until I could go back at the end in and fill in the text.  And it took a little bit of time and 
effort to figure out how to get the table on the data page to display correctly.  Another item of note or helpful thing I learned, was the 
'Live Server' function in VS code.  Once I had that extension installed, it made it so much quicker and easier to see the changes that I was 
making on the actual page.

I have submitted my github pages link in BootCampSpot, but I'll place it here at the end just in case you need it to access the website.

[Latitude Visualization Website link ](https://loucksjohn.github.io/web_Design_challenge/)



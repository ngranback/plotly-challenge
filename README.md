# plotly-challenge

----

Homework 15  - Interactive Visualizations and Dashboards


----

### How it works

The dropdown menu is auto populated with ID options from the given dataset.


Choose an ID from the dropdown menu to view charts related to that ID's data. 



### Critiques

I hardcoded the data into my app.js file to not mess with the python server. But this is clunky and I would rather load it from a separate file.


The bubble chart does not look great. the bubbles are too big or too tiny, but I couldn't make sense of the sizeref attribute. To improve this I would make the size of the bubbles more manageable and make the colors nicer.


The gauge chart is also pretty ugly, but the customization is fairly rigid. I would like to add a little note underneath that will display "very clean person" or "you're gross!" depending on the wfreq value of that ID.
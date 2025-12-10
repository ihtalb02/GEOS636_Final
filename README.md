**Figure Number 1**

This code creates a map of Interior to Eastern Interior Alaska, where the location of my study is. The study site is Manh Choh, located SW of Tok, Alaska.

This code uses:

Coordinate of locations I want to plot on the map.
Pygmt for the map.
A file called “Roads_AKDOT_6859052738519254347.geojson” to plot the major roadways to and from Tok and Fairbanks.
An inset map to show where in Alaska the study location is.



**Figure Number 2**

This code produces a plot of the cooling ages for the rocks I collected for my project & other regional events and dates pulled from literature.

This code uses:
- Pandas
- Matplotlib
- A csv file called "ages_PAG.csv" for my samples and their ages
- plt.axhspan with rounded y-values from the literature to show the extents of events such as metamorphism, putonism, or ages of exposed lithologies in Eastern Interior Alaska.



**Figure Number 3**

This code produces a figure that shows the closure temperature (The temperature, or temperature range, at which minerals crystallize) for specific phases I have or will be dating for my research. 

This code uses:
- Matplotlib
- Each mineral phase is assigned a, x-value and the duration to create the broken histogram look.
- Each phase is stacked from lowest temperature to highest.
- This code can be changed based on the closure temperature that is calculated for specific grains.

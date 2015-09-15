# ticket-system

### Exploratory Data Analysis with ticket system data

The repository consists of three folders `webflow`, `ticket` and `system`. Explanation of how it works and what's inside the folder are provided below.

**webflow:** A webflow record from Google Analytics(GA) of a ticket system website. For more sophisticated work related to GA, click [here](https://github.com/ethen8181/Ecommerce). last update: 2015.6.1
- `webflowdata.xlsx` The main dataset used by this folder.          
- `webflow.md` Contains the whole process of the analysis and thorough detail of the dataset. 
- `webflow.R` Just the R code for the analysis, though may not be as organized and well-explained.                  
- `webflow_files` Contains the graph that the analysis generated.                

**ticket:** Ticket selling information for one of the concert in 2010. last update: 2015.6.1         
- `ticketdata.csv` The raw dataset for this folder. It recorded the ticket selling info to one of the concert provided by the same ticket system as the webflow folder.
- `ticket.md` Shows the entire steps for doing the analysis (Also contains description of the dataset).
- `ticket.R` the R code for the markdown file, including other testing codes. 
- `seat.png` Shows the structure of the arena in which the concert was held. It will be used with "image.R".
- `processdata.csv` A subset of the original dataset ( steps to generating it are shown in the report ) and will be used by "image.R".
- `image.R` Contains a function "image", you can pass a timeline to it, and it will do a plotting on the "seat.png". The plot will show you a number of tickets available for each section in the timeline you specified. An example of how it is used is also shown in the report.
- `ticket_files` contains the plot generated by the analysis.

**system:** Ticket selling information for concerts held in 2010. last update: 2015.7.12
- `data` The folder contains the dataset "system1-4.csv" used for the analysis. 
- `system` The R, md, Rmd, pdf, html version of the report. .R is less informative, it contains only the code for the report, and some other testing codes that were not included in the report. 
- `mosaic_plot.R` Contains the mosaic_plot that plots a mosaic plot of a input data.frame, it is used in the report, that is "system.md" if you're looking at it on github.
- `webflow_files` Plots generated by the report. 

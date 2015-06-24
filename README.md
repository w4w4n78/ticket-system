# ticket-system
## Exploratory Data Analysis with ticket system data

## Introduction
The repository consists of two folders `webflow` and `ticket`. Explanation of how it works and what's inside the folder are provided below.

**webflow:** A webflow record of a ticket system website.  
- `webflowdata.xlsx` The main dataset used by this folder.          
- `webflow.md` Contains the whole process of the analysis and thorough detail of the dataset. 
- `webflow.R` Just the R code for the analysis, though may not be as organized and well-explained.                  
- `webflow_files` Contains the graph that the analysis generated.                

**ticket:** Ticket selling information for one of the concert in 2010.         
- `ticketdata.csv` The raw dataset for this folder. It recorded the ticket selling info to one of the concert provided by the same ticket system as the webflow folder.
- `ticket.md` Shows the entire steps for doing the analysis(Also contains description of the dataset)
- `ticket.R` partial R code for the markdown file.
- `seat.png` Apart from that it also has a png file, which shows the structure of the arena in which the concert was held. It will be used with the `image.R` file.
- `processdata.csv` is a subset of the original dataset(the processing steps are given in the `ticket.md`) and will be used by `image.R`.
- `image.R` what this R code does is, it contains a function image, you can pass a timeline to it, and it will do a plotting on the `seat.png`. The plot will show you a number of tickets available for each section in the timeline you specified. An example of how it is used is also in the `ticket.md` file.
- `ticket_files` contains the plot generated by the analysis.

**system:** Ticket selling information for concerts held in 2010.
- `data` The folder contains the dataset used for the analysis. `system1-4.csv` 
- `system` The R, md, Rmd, pdf, html version of the report. .R is less informative, it contains only the code for the report. 
- `webflow_files` Plots generated by the report. 

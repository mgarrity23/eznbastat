# Ez NBA Stat

RShiny app created by myself and Ryan Crenny (https://github.com/rcrenny) that allows users to visualize advanced NBA statistics. The app allows users to compare NBA players alongside each other, compare NBA team, and evaluate historical trends in the NBA.

Check it out here: https://eznbastat.shinyapps.io/senior-project-nbastatstuff/

This was our final project for the Villanova course: Senior Projects. We had 4 sprint presentations where we discussed what we had accomplished and what we planned to work on for the next sprint. The class ended with a brief virtual presentation by all seniors in front of the Villanova Computer Science faculty.

The app.R code is for the shiny application itself.

All csv files were created calling the NBASTATR library (found here: https://github.com/abresler/nbastatR) and them manipulating that data to get the final chart we watnted. That dataframe was then converted to a csv file so that our shiny app would not have to call the library every time a chart was generated.

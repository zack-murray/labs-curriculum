# Module Inquiry 2

## Questions

1. What technical choices did you make today?
    • Decided to utilize 1 database shared between both back-end and front-end
    • For DS to handle the the creation of graphs and WEB to then style those visualizations
    • To use CSV's instead of a live API to populate the population data table
    • To incorporate regression and knn models when we start to make predictions in release 2
    • 1 endpoint to display city statistics instead of multiple, may change depending on how the 1 endpoint functions
    • Using 4 seperate tables for city statistics and linking them with a look up table, instead of making one giant dataset

2. Pick two technical choices you're happy with. What was your thought process as you made those choices? What did you consider and what did you decide against?
    • Using only 1 endpoint to display the city statistics and using seperate tables with a lookup table. We decided on the one endpoint for simplicity, this is release 1 and we want to see what our learn more/compare summary will look like with all info on the metrics displayed at once. We considered splitting it into multiple endpoints, and still may later on in development, but are moving in this direction for the time being. 

    • Populating 4 different data tables with city statistics and utilizing a look-up table, instead of merging them all into one table. We thought that this would look cleaner and depending on the amount of data we retrieve will be faster to query. We considered merging all info into one giant data table, but decided against it because of the sheer amount of data we'll be storing.

    - Take a moment to think about the advantages in choosing the route that you did.
        • Endpoint - Easier to set-up, will give the user all of the built-in info on given city
        • Data table - Performance enhancement, data centralization, Faster querying
    - Now take a moment to consider the disadvantages.
        • Endpoint - User can't just pick and choose the pertinent statistics they want to see, will always be faced with full summary
        • Data table - Have to set up a data table/be meticulous with making sure all keys line up and that all data is linked correctly

3. In one or two sentences, summarize why you ultimately made the choice you did.
    • We made the choices we did because we feel like this is what the stake-holder has in mind for the first release. They're decisions that we're positive we can implement in the time-frame for our first release and have indicated back-up plans in case these decisions aren't ideal for the final release. 

4. Extracting useful conclusions from your process: 
    - According to your understanding, what makes a good technical choice?
    • A good technical choice is one that benefits the team as a whole, while accomplishing all of the requests of the stake-holder. Any decision that can help improve the speed of the app or save space should be greatly considered and weighed against any potential drawbacks of that decision.  
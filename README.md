# IPL Data Visualization:
A web-app to visualize IPL data using datasets from [Kaggle](https://www.kaggle.com/harsha547/indian-premier-league-csv-dataset).  

## View the web-app:
* View it [here](https://ipl-data-visualization-web.netlify.app/)
* To view it locally, clone this repository, navigate to the project directory and run
```
npm install
npm run serve
```

## Project Structure:
The visualizations have been divided into four sections - <b>Teams</b>, <b>Players</b>, <b>Venues</b> and <b>Seasons</b> and observations have been provided with the visualizations in a side card.

## Major frameworks / libraries used in the project:
- <b>Vue Framework</b>: <i>Provides features like virtual DOM for better performance, routing using vue-router package, data binding and a lot more.</i>

- <b>ChartJS</b>: <i>A simple and powerful API to create different types of charts with animations.</i>

- <b>vue2-google-maps</b>: <i>Vue Component library for integrating google maps in the app. Provides data-binding (which is hard to do with native maps API) with map features.</i>

## Bonus Points:
1. web-app created in vue.js: Developed in Vue.js using component architecture.  
2. Loading time optimized by using the precalculated results from the given CSV files and directly using results from the json files generated. Also used CSS wherever possible for best performance.  
3. The web-app is fully mobile responsive. It has an easy-to-use User Interface (UI) for a greater contrast and better visual appeal.  
4. Tried to make it a Progressive web-app. It is fast, reliable and PWA optimized.  
5. It is usable offline. This was done by caching the JS and CSS files after loading for the first time. The only drawback here is that the Google Maps (to view Venue details) will not work offline.

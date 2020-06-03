# TrainPredictions App

Deployed site: https://psu23.github.io/TrainPredictions/

### Overview

This app is a train schedule application that incorporates Firebase to host arrival and departure data. Information is retrieved and manipulated using Moment.js. This site provides up-to-date information about various trains that the user adds, namely their arrival times and how many minutes remain until they arrive at their station.


### Instructions

* The user comes to the site and adds the following information:
  
  * When adding trains, administrators should be able to submit the following:
    
    * Train Name
    
    * Destination 
    
    * First Train Time -- in military time
    
    * Frequency -- in minutes (how often (in minutes) the train arrives)
  
  * The app calculates when the next train will arrive based on the current time retrieved from Moment.js.

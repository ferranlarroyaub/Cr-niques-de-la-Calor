# Cròniques de la Calor
Code, data and figures of the citizen science project "heat chronicles" where we measure and study the temperature in different neighborhoods and through different associations. This is a pilot to start working with the different communities and to study the future scope of the project. 

The communities involved were:
  - Biblioteca Josep Janés (Collblanc - La Torrassa, Hospitalet de Llobregat)
  - Fundació Comtal (La Ribera, Barcelona)
  - Institut La Ribera (Montcada i Reixac)
  - Escola La Guàrdia (Sant Vicenç dels Horts).

The issue of climate change, heat islands, climate shelters etc. has become a major subject of study in recent years due to the clear effects of the continuous increase in temperature that we are experiencing.

In this sense, we believe that it is very valuable to learn about the perception of the population at the neighborhood level, and to understand how they experience the heat and how is the variability of temperatures within the same neighborhood (knowing that in some places, they do not even have a weather station). A mapping of temperatures along the different streets and places of interest in the neighborhood, together with the experience of the local inhabitants, can clearly help to promote actions to combat the heat. 

In this citizen science project, we use MeteoTracker (https://meteotracker.com/) sensors to record the temperatures and other weather parameters (humidity, pressure...) through different participating communities in very specific neighborhoods. The methodology used in these first pilot tests has been: 

  1. Present the project to interested participants from the community.
  2. Together and using large format maps, elaborate specific routes that pass through different places of interest to measure the temperature. 
  3. Go out on the street by walking, with the temperature sensors recording the GPS location and the weather variables (with high resolution of a few seconds) and perform the previously agreed route.
  4. Stop at the various places of interest, previously defined, and perform a survey on the feeling of heat to the participants. In this way, we can compare the actual temperature measured by the sensor with the general temperature sensation of the group.
  5. Preparation of a report and presentation of the results to the community, discussing together the results and the observations made.

<br> 

### Repository description:

- It contains 4 folders corresponding to the 4 cases of study mentioned above. In each folder, we can find the Data (Original and Processed), the Figures and the Code (Jupyter Notebook) of the different sesions performed.
- Data processing has been kept simple. We eliminated duplicates and the first (and sometimes last) timestamps, where the sensor is being calibrated with the ambient temperature and/or inside a building.
- The code is basically the same in each folder, adapted to each particular case study and location. We plan to create a general code that brings together the general functions used for the study and that can be applied to all cases.

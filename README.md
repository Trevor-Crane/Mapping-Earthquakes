# Mapping-Earthquakes

## Purpose of Project
We have been tasked with creating a server that maps Earthquakes from the past 7 days from across the globe. In order to do this, we will create a custom map that was provided to us by Mapbox. We also get our earthquake data from the website https://earthquake.usgs.gov/

## Multiple Map Options
With our custom map, we have created three possible styles as our base layer option. The first one is the Streets view: <br>
![Streets_View](https://user-images.githubusercontent.com/107770394/190234493-f4b107f7-cc9b-4b94-a1bd-af61b3ded11a.png) <br>
The Second one is a satellite view: <br>
![Satellite_View](https://user-images.githubusercontent.com/107770394/190234417-b4177838-1336-4d4b-8625-b25a6c7607e4.png) <br>
And our final one is a dark view: <br>
![Dark_View](https://user-images.githubusercontent.com/107770394/190233569-77d5d301-5f32-4876-aa04-10fbb0a95bbe.png) <br>

## Multiple Overlay Objects
From there, we will create three unique overlay options. The first of which will be showing the tectonic plate borders of the world,<br>
![Tectonic_Plates](https://user-images.githubusercontent.com/107770394/190234599-5d158b87-c6f3-492b-8f4e-69d66273020c.png) <br>
The second one shows a marker for each earthquake that was recorded from the past seven days. We went with a circle marker for these, with the radius of said marker being determined by the magnitude of the earthquake. To make it easier for the viewer, we also created a legend, with different colors signifying different magnitudes. When you click on a marker for an earthquake, it will give you both the magnitude data and the location for that specific earthquake. <br>
![Earthquakes](https://user-images.githubusercontent.com/107770394/190233687-8acc130e-7c66-4350-8afd-54825413d1db.png)<br>
Finally, we created a layer that shows only major earthquakes, those with magnitudes of 4.5 and above. We included the same markers as the above layer for this. <br>
![Major_Earthquakes](https://user-images.githubusercontent.com/107770394/190234315-256e18f0-2d36-4911-b51e-517915a73e81.png) <br>



## Final product
With all of the above accounted for, you can have a combination of one of the base layer options and any of the overlay objects. As an example, here is one that shows a satellite view with the tectonic lines and all of the earthquakes. <br>
![Final](https://user-images.githubusercontent.com/107770394/190234146-fbc3f48f-97eb-4502-b362-2d3e72f11830.png)

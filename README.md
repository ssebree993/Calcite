Kolache locator for a road trip is “essential fuel”
Sonja Sebree
Geog-576, University of Wisconsin-Madison
Fall 2024
Abstract 
Texas, renowned for its "biggest" attractions, also boasts a unique culinary gem: the kolache. This yeast-dough pastry, filled with various ingredients, has become a beloved tradition in the state. However, finding the perfect kolache bakery, especially during road trips, can be a challenge. This project proposes the development of a mobile web application using Esri.js and ArcGIS Online to address this issue and assist travelers in discovering convenient and family-friendly kolache destinations.
Project Goals
The primary goal of this project is to create a user-friendly mobile application that facilitates the discovery and exploration of kolache bakeries along popular travel routes in Texas. The application will leverage geospatial data to provide accurate information on bakery locations, amenities, and user reviews. Key features will include:
•	Search functionality: Users can search for kolache bakeries based on location, amenities (e.g., dog parks, gas stations), and specific kolache fillings.
•	Interactive map: A visually appealing map will display the locations of bakeries, allowing users to zoom in, pan, and explore the surrounding area.
•	User-generated content: Users can contribute descriptions, locations and ratings of their kolache experiences, enriching the application's database and helping others make informed decisions.
•	Integration with "Buc-ee's" locations: Given the popularity of "Buc-ee's" gas stations in Texas, the application will integrate data on their locations, making it easier for travelers to find kolache bakeries nearby.
Data Sources and Technologies
The application will utilize a combination of geospatial data sources, including:
•	ArcGIS Online: A cloud-based GIS platform that provides mapping, analysis, and data management capabilities.
•	OpenStreetMap: A free, editable map of the world that can be used to supplement ArcGIS Online data.
•	User-generated content: Reviews, ratings, and photos submitted by users will contribute to the application's database.
Esri.js will be the primary development framework, enabling the creation of interactive maps and web applications. The application will be designed to be responsive and compatible with various mobile devices.
Conclusion
The development of a kolache trail mobile app will not only provide a valuable resource for travelers exploring Texas but also showcase the potential of geospatial technologies in enhancing user experiences and promoting local businesses. By combining the power of Esri.js, ArcGIS Online, and user-generated content, this project aims to create a unique and informative tool for kolache enthusiasts and road trippers alike.

Wireframes
  
Figure 1. Overall map interface in mobile form for the “Kolache Locator”. 
On the Figure 1 diagram, the left side of the form includes the ESRI calcite tools in an expandable panel. The left side tools include buttons that expand to show the information about the application, a meat pie icon to add a kolache location, a “show layers” button, a change basemap button, a show legend button, a search the kolache database button, a source credits button, and an expand/contract panel button.
 
Figure 2. A mockup of the Survey 123 input.
The Survey 123 survey form will collect information to populate the back end geodatabase once the “submit” button is pushed. The form design is set up to include both free form text, location data and specific yes/no responses. 


Data Table
The data table includes the “Newspaper” vector tile basemap, a neutral background. Other basemaps can be added to replace the original basemap as needed. The other feature class layers include the editable Kolache Locations feature class layer, used to add bakery locations, or snap a location to an existing bakery location found in the Open Street Map Shops – Bakeries data layer. The other helpful layer is a Buc-ee’s (sic) gas store layer. For people not familiar with the brand, it is a megasized gas store with clean bathrooms, food and souvenirs. 

 
Figure 5. Data table showing sources of the basemap and Feature Layers.
ER Diagram
Starting with the conceptual design, the geodatabase feature class has fields for a unique location identity (LID) that will automatically assign an individual object ID, a NAME field of the business, a food name, whether it was a KOLACHE (Y/N), a location field, a category selector for meat, fruit or cheese kolache, a description of the breakfast item, and the number of items consumed. 

 
Figure 6. ER Diagram of the geodatabase for user interaction, including an interactive Survey 123 form for gathering data.  

 
Figure 7. Relational Diagram derived from the ER diagram showing the unique id, name, subtypes for the presence of meat, fruit or cheese in the kolache, if eaten. 
Sources
1.	Texas Highways Magazine. “Czech out the Texas Kolache Trail. https://texashighways.com/food-drink/czech-out-the-texas-kolache-trail/, accessed 9/30/2024.
2.	Buc-ee’s website: https://buc-ees.com/, accessed September 30, 2024.
3.	Slovacek’s website: https://www.slovacekwesttexas.com/bakery/, accessed September 30, 2024.
4.	David W. Allen, Focus on Geodatabases in ArcGIS PRO, 2021, ESRI Press.  
5.	ERD Plus Online Tool, https://erdplus.com/, accessed September 30, 2024.





# Project Report
## Texas Landcover Change: A Study of Land Use Change Throughout Texas
### https://youtu.be/9MTVT-S-_zA

### Members
Andrew Muse (Project Leader) <atmuse18@tamu.edu>

Daniella Edey <dgedey@tamu.edu>

Anna Bonczynski <bonczysnki@tamu.edu>

Nicholas Keller <nickkeller@tamu.edu>
### Client 
Dr. Julie Loisel  <julieloisel@tamu.edu>

### Goal
This project sought to create an interactive website with web maps to be utilized as a learning tool for high school students to explore the effects of land use/land cover (LULC) change. The product serves as an introductory LULC change learning module using three case studies: Dallas, Houston, and San Antonio. Each case study has its own site linking from homepage, and each contain an embedded slider Story Map of LULC from 1992-2011. Each site also contains supplemental materials such as Highcharts or a static map. Each case study expands on different effects stemming from LULC change, such as flooding, loss of arable land, and urban heat island effect. There are Highcharts displaying temperature change and deviation for San Antonio and loss of arable land in Dallas, and a static map of the floodplains in Houston.

### Motivation
This project was designed to establish the framework for Dr. Julie Loisel in her work to develop a teaching toolkit for educating local Texas high school students on soil and land use change, as it is a topic not commonly taught in secondary education. The student users will be able to go to the website and navigate through the case studies. By utilizing ESRI’s Story Maps, the sites provide an example of the uses of WebGIS for further education in the classroom. Teachers will be able to use this tool to provide their classes with an education not just on LULC change but also on the uses of GIS and WebGIS. Ideally high schools all throughout Texas will begin to implement this tool in their advanced geography courses. High school teachers will be able to choose how much (or how little) of each theme they wish to use in their classroom, allowing the tool to be easily integrated to the following courses: AP Human Geography, AP Physical Geography, Environmental Sciences, and Geographic Information Systems (GIS).

### Users and Use Cases
#### Students (Unfamiliar)
High school students of local Texas schools who are learning about soil and LULC as part of their curriculum in advanced Geography courses. This user group will be familiar with basic geographical knowledge, however their GIS skill set would be at the new and novice user levels. These users will use the online learning module as a classroom activity to fulfill learning objectives put forth by their teachers which include defining and understanding LULC and exploring the use and application of WebGIS.

#### Teachers (Familiar)
Teachers of the above mentioned advanced Geography and GIS courses at the local Texas schools. This user group will implement this WebGIS learning module into their lesson plans as they see fit to fulfill the objectives of defining and understanding LULC and soil degradation and exploring the use and application of WebGIS. This learning module can be applied to any classroom size while meeting national standards of education. It will allow the teachers to implement their individual teaching needs through collaboration with the client and team. Training will be provided by the client and the tutorial will maintain a simple design for those teachers who do not have a base knowledge of WebGIS interfaces.

#### Introductory College Students (Unfamiliar)
Similar to the user group of high school students, this user group consists of college level students from any location that are studying topics on LULC. This user group will also be familiar with basic and more advanced geographical knowledge, however their GIS skill set may vary and will be assumed to be at new or novice user levels.

#### Graduate Students, Researchers, or Professors (Familiarity will Vary)
Similar to the user group of introductory college students, this user group consists of a more general range from experienced graduate students and professors to the general public from any location that are studying or are simply interested in the topics on LULC and looking for introductory material. This user group may or may not be familiar with basic geographical knowledge (which is assumed they may have basic geographic knowledge if they come across this learning module) and their GIS skill set may vary and will also be assumed to be at new or novice user levels. These users will use the online learning module to increase their knowledge on the topics to fulfill research needs or curiosity.

### Approach/Methods/Data
There will be three maps included in this project. Each one will show soil degradation overtime with the use of a slider to change the timeline of the map a person is viewing. The three maps will show Dallas, San Antonio, and Houston. There will also be a learning module covering soil security and why it is important to the world. These maps will also feature a tutorial on making a basic map through ArcGIS Online in order to teach high school students the basics as well as some benefits of GIS.

#### Architecture
After finding available LULC data for the U.S., the team created their assigned case study location and chose the years 1992 and 2011 to show the most dramatic comparison of LULC change as opposed to comparing 2006 and 2001. These 4 years were the only ones available for this data set. The team uploaded the maps to ArcGIS Online to be hosted and shared in order to create slider-style Story Maps for each site. After each Story Map matched in theme, layout, and legend, they were embedded using the shareable link given by ArcGIS Online. The website was then built using a free site as a model for styling and basic HTML and CSS codes. The site is made up of 5 pages total that maintain the same styling and layout: homepage, Dallas, Houston, San Antonio, and FAQ. The team members with the study areas also embedded their respective Highcharts and static maps using inline Javascript, as well as any written information on the topic into the specific page codes. The pages and code were tested frequently as they were being built by all members to ensure proper functionality. 

#### Technologies/Data/APIs:
* National land use and land cover maps on [TNRIS](https://tnris.org/data-catalog/)
* ArcGIS Online
* ESRI Story Map app
* Highcharts
* A Free Design by [Bryant Smith](http://www.bryantsmith.com/template/) (Model for site design)
* NOAA (temperature data)
* USDA.agcensus.com (Dallas Aerable Land Change Data)

#### Task Assignments:
* Andrew - Dallas map/Story Map and Highchart, processing data, some additional HTML
* Anna - Houston map/Story Map and additional still map, CSS/HTML/Javascript coding
* Nick - HTML/CSS/Javascript coding, data sources/research 
* Daniella - San Antonio map/Story Map and Highcharts, some additional HTML/Javascript coding

### Results
The current version of our product consists of a styled homepage that links to 4 sub-pages with a layout that includes a navigation-bar on top. 3 of the 4 linked sub-pages contain embedded slider Story Maps of LULC that compares 1992 data to 2011 data within the extent of the study area. Each site contains supporting educational text, as well as embedded Highcharts for showing data associated with each study site. There are 2 Highcharts displaying temperature change and deviation for San Antonio, a Highchart displaying loss of arable land in Dallas, and a static map of the floodplains in Houston. The 4th linked sub-page contains FAQ, contact, and documentation. Each linked page maintains consistent styling and functionality. The only component missing is the ability to host the site. However, in disuccsion with Dr. Loisel, she offered to tend to this issue by finding a hosting service at a later date for when the overall product containing all learning modules are completed and ready to launch.

### Discussion and Conclusion
This project had originally set out to introduce the related topic of soil degradation in connection to LULC, however locating the soil data had proven to be very difficult with limited study sites and complex classifications. The team settled on using just LULC data for the Story Maps in order to show the change over time (1992 to 2011) and add content on connected topics such as urban heat island effect, flooding, and arable land loss at the suggestion of Dr. Loisel.

This project accomplished establishing the framework for Dr. Loisel in her work to develop a teaching toolkit for educating local Texas high school students on soil and LULC change. The site and maps can be easily modified for different topics and age demographics. For future works, the site will be expanded to include more information on soils and soil degradation, and will be hosted by Dr. Loisel.

### Artifacts

#### Wireframes and Outlines
![Task Outline and Hosting](https://github.tamu.edu/JulieMaps/ProjectDocs/blob/master/Planning/03-27-18/Framework/20180327_143734.jpg)
![Website Wireframe](https://github.tamu.edu/JulieMaps/ProjectDocs/blob/master/Planning/03-27-18/Framework/20180327_143935.jpg)
![Version2 Site Wireframe](https://github.tamu.edu/JulieMaps/ProjectDocs/blob/master/Planning/03-27-18/Framework/WF1.jpg)
![Version2 Site Wireframe2](https://github.tamu.edu/JulieMaps/ProjectDocs/blob/master/Planning/03-27-18/Framework/WF2.jpg)
![Version2 Site Wireframe2](https://github.tamu.edu/JulieMaps/ProjectDocs/blob/master/Planning/03-27-18/Framework/WF3.jpg)

### Model Examples from Other Sources
[News Site Example](https://www.telegraph.co.uk/news/uknews/11674412/Events-mark-800th-anniversary-of-the-Magna-Carta.html) 



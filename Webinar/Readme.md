<a href="https://github.com/IATAdatathon/Athens19">GitHub</a>

Repository for IATA Datathon in Athens 24th June 2019
---
# INTRODUCTION
![INTRODUCTION](https://github.com/IATAdatathon/Athens19/blob/master/Webinar/img/Slide1.JPG?raw=true)

<p style=""><button name="button" onclick="https://www.eventbrite.com/e/iata-aviation-datathon-registration-60260500780">REGISTER</button></p>

IATA Aviation Datathon 2019 focuses on addressing industry challenges and priorities, proposing solutions leveraging data science capabilities in areas where data is already available and accessible. All in support of IATA’s renewed global strategic priorities which includes a strong pillar related to data. The objective is to raise awareness and trigger innovative ways airlines and the wider aviation industry can extract value out of data.
For more information go to: www.iata.org/datathon 

# ABOUT US
![ABOUT US](https://github.com/IATAdatathon/Athens19/blob/master/Webinar/img/Slide2.JPG?raw=true)

# AGENDA
![AGENDA](https://github.com/IATAdatathon/Athens19/blob/master/Webinar/img/Slide5.JPG?raw=true)

# CHALLENGES
![CHALLENGES](https://github.com/IATAdatathon/Athens19/blob/master/Webinar/img/Slide6.JPG?raw=true)

![CHALLENGE1](https://github.com/IATAdatathon/Athens19/blob/master/Webinar/img/Slide7.JPG?raw=true)

![CHALLENGE2](https://github.com/IATAdatathon/Athens19/blob/master/Webinar/img/Slide8.JPG?raw=true)

![CHALLENGE3](https://github.com/IATAdatathon/Athens19/blob/master/Webinar/img/Slide9.JPG?raw=true)

# JURY
![JURY](https://github.com/IATAdatathon/Athens19/blob/master/Webinar/img/Slide10.JPG?raw=true)

# PRIZES
![PRIZES](https://github.com/IATAdatathon/Athens19/blob/master/Webinar/img/Slide11.JPG?raw=true)

# Q&A
![Q&A](https://github.com/IATAdatathon/Athens19/blob/master/Webinar/img/Slide12.JPG?raw=true)
<br>
**Q:** Will the set of info together with data be printed (I assume “shared”) on Github?<br> 
>**A:** Data sets will be available in [GitHub](https://github.com/IATAdatathon/Athens19) and [Google Drive](https://drive.google.com/drive/folders/16rVqW4TR3eQJ_1SFy7uBzGYCAGF3657k?usp=sharing) with the corresponding specifications<br>

**Q:** Is the data being in English?<br>
>**A:** Data for made available for the challenge will be in English. The evaluation from the Jury will be based on the work made for English as the core language. Nonetheless, participants are welcome to directly include or provision for other languages on their proposed solutions.<br>

**Q:** Are we keeping “test” datasets where we will evaluate the results of the different solutions?<br>
>**A:** Datasets are available at least 2 weeks before the event and participants are free to use it at their own discrection to work on the solutions for the challenges.<br>

**Q:** Names of some of the sources<br>
>**A:** Datasets consists of data collected from different public sources (tracking services, airports sites and METAR services) or accesible to the general public (twitter API). Additionally for challenge 2, data is excracted from IATA GADM databaes through anonimization and removing sensitive data elements, preveting exposing any particular entity.<br>

**Q:** When we say “documentation” does that include webpage dashboards and notebooks?<br>
>**A:** We are in the final stage of finalizing the documentation which includes this Webinar presentation, this Q&A, data sets and data specs. If time allows we are intending to create a Notebook as an example and guidance for the challenges. Unfortunately we cannot guarantee when this will be available. Stay tuned! <br>

**Q:** Do the participants need to bring their own laptops?<br>
>**A:** Yes, Participants are expected to bring their own equipment and IDE or software to work on the challenges.<br>

**Q:** Clarification question: Do the participants need to cover 1 out of 3 challenges – not all of them?<br>
>**A:** Participant are required to compete for at least one challenge. Opting for a second or third challenge is optional.<br>

**Q:** How and when will the team be constructed?<br>
>**A:** Participants can opt to compete individually or in groups, from their own organization or mixed corporations. In order to increase the efficiency of the event logistics and allow more time for the presentations, IATA will contact <br>

**Q:** Can the participants assume that intellectual property ownership of any algorithms, visualizations etc. stay with the teams that created them?<br>
>**A:** Code and IP remains with participants. However, IATA and the industry can use the proposed solutions as inspiration for future developments. <br>

**Q:** Will we send the recording session?<br>
>**A:** Audio failed and hence not shared. Instead we are posting the Q&A through this GitHub chanel.<br>

**Q:** For the five-minute presentation – who is the audience? Technical data scientist or business people?<br>
>**A:** Five minutes is tentative and we might need to reduce the time for presentions due to the anticipate very large number of teams. Audience will be the Datathon participants, Sponsors, Jury, some IATA Management and if agenda allows industry partners present in Athens.<br>

------------------------------------
## Webinar 2:

**Q:** Is the provided data being final? 
>**A:** Final data has been provided and moved into <a href="https://drive.google.com/drive/folders/16rVqW4TR3eQJ_1SFy7uBzGYCAGF3657k?usp=sharing"><b>GOOGLE DRIVE</b></a>. 
Note that following suggestions from participants, we have enhanced some of the datasets:
* Departures/Arrival: Defined delays and added Departure and Arrivels Status labels to v2.
* GADM: Added an additional 4K dataset that can be used for testing the modules trained with the 20K dataset.
* Twitter: Added dataset of tweets containing Airport/Airline's hastags.

**Q:** In the sample data, there was no data in English 
>**A:** Non-English wording can be either ignored, programatically translated or analyzed through multilanguage word processing. 

**Q:** Will there be more data? 
>**A:** Data provided is final. However participants are welcome to include their own relevant additional data.

**Q:** Will the labels be provided on-site? 
>**A:** If by label is referred to define Delays and label the dataset, this has been done and published. GADM and Twitter will not be labeled.

**Q:** Do you confirm that the data is provided for a limited list of airports? Yes 
>**A:** Departure, Arrival and METAR data contains data for the following airports. 
Airports:<br>
ATH, BVA, CDG, CDG-ORY-BVA, EWR, FRA, IBZ, JFK, LAX, LCY, LGA, LGW, LHR, LTN, MIA, PMI, SEN, SFO, SYD

**Q:** “accuracy of the algorithm – will IATA provide a “testing data set” at the Datathon for participants using our model and the measure the errors of our predictions? 
>**A:** 

**Q:** Some fields are not easy to understand: would it be possible to get a description?  
>**A:** please contact us through datathon@iata.org and we will note and clarify to all participants.

**Q:** On challenge 2: Some instances have multiple labels, is it meant to be like that?  
>**A:** On AGDM dataset? Yes. These labels are the meta data of the incidents which may apply to multiple categories.

**Q:** Is it an open challenge? Will participants be able to call some of their specialists that might not be on-site? Participants may work with their specialists before the event, however, during the Datathon, they would have to work with the team that is present on-site. 
>**A:** 







![THANK YOU](https://github.com/IATAdatathon/Athens19/blob/master/Webinar/img/Slide13.JPG?raw=true)






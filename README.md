# Impossible College Dataset
Python valgfag.
Gruppe: Impossible College.
Medlemmer: Bo Henriksen, Christian Lykke, Anders Nissen.


## UFO Reports from USA

Ufo-Reports er en samling af over 80.000 reporter om møder med ufoer. I datasettet er det beskrevet, hvor der er set ufo, i hvor lang tid, hvordan ser ufoerne ud og hvad skete der.  

## Spørgsmål

#### Hvilket sted er der flest UFO observationer?  

#### Hvordan har antallet af observationer udviklet sig over tid?  
Som besvarelse til det her spørgsmål vil det give god mening at lave et plot. Det er valgfrit, hvordan i laver plottet.  

#### Hvornår på året er der flest observationer?  

#### Hvordan ser en ufo ud?  
Find flere buzzwords som f.eks. form, farve eller andet. Her kan det være en fordel at bruge textBlob.  https://textblob.readthedocs.io/en/dev/  

#### Hvor lang tid kunne de se ufoen(gennemsnit)?

#### Plot 1.  
På hvilke dage er det sandsynligt at se ufoer(i procentvis fordeling)?  
x i plottet er mandag til søndag.  
y i plottet er 0 til 1.  

Hints:  
Hvor mange ufo sightings er der i alt?  
Brug datetime når du skal finde dagene.  

![alt text](https://github.com/BoMarconiHenriksen/impossibleCollegeDataset/blob/master/img2.jpg)

#### Plot 2.  
Lav en graf over polaritet og sentiment.  
x i plottet er index over observationer.  
y i plottet er 0 til 1.  

Hints:  
Brug textBlob.  
Får i minus tal så normaliser(fjern minus) tallene.  

![alt text](https://github.com/BoMarconiHenriksen/impossibleCollegeDataset/blob/master/img1.jpg)

##### TextBlob  
https://textblob.readthedocs.io/en/dev/  
https://textblob.readthedocs.io/en/dev/quickstart.html#sentiment-analysis  

##### State Boundaries:  
https://github.com/jgoodall/us-maps  
https://bubinga.co/geojson-us-states-and-counties/  

#### Plot 3.  
Lav et plot, der viser antallet af ufo observationer pr stat i USA, og farvekode jeres resultat. Mørk farve indiker mange observationer, og lys farve indiker få observationer.  

Brug evt. følgende moduler. Har du kendskab til andre moduler må du gerne bruge dem.    
https://pypi.org/project/folium/  

State Boundaries:  
https://github.com/jgoodall/us-maps  
https://bubinga.co/geojson-us-states-and-counties/  

![alt text](https://github.com/BoMarconiHenriksen/impossibleCollegeDataset/blob/master/img3.jpg)


#### Link til csv fil.  
https://raw.githubusercontent.com/planetsig/ufo-reports/master/csv-data/ufo-scrubbed-geocoded-time-standardized.csv  

#### Link til dataset på kaggle.com - Få et hurtigt overblik over navnene på kolonnerne her  
https://www.kaggle.com/NUFORC/ufo-sightings#complete.csv 

#### Link til dataset på github. 
Csv filen er taget fra planetsig github repository. Der kan derfor være forskel på det, som ligger på kaggle.com og i planetsig github repository https://github.com/planetsig/ufo-reports Vi andefaler at i bruger planetsig github repository til besvarelserne.  


-----


## Speed Dating Experiment

Datasettet er indsamlet over en periode på 2002 til 2004. Hver deltager har datet i 4 minutter med alle af det modsatte køn. 

Når alle havde datet blev deltagerne spurgt om de ville på en yderligere date. 

Derudover blev de også bedt om at vurder deres date på følgende områder attraktiv, oprigtighed, inteligens, sjov, ambitiøs og samme interesser.

Hvor ofte er der et match når man speed dater?

Når der er et match, hvad har personen så vurderet højest(attraktiv, sjov osv.)?

Hvad er gennemsnitsalderen for en speed dater?

Hvilken Erhverv har en speed dater oftest?

Hvad mener folk er vigtigt i et forhold?

Hvor kommer speed datere fra?

https://data.world/annavmontoya/speed-dating-experiment/workspace/file?filename=Speed+Dating+Data.csv

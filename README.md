# Analysis of the speechs of the president of Mexico throughout his six-year term using Python

In this repository the word clouds of different speeches by the Mexico's  president are generated, each speech corresponding to an annual activity report.

The words with the highest number of repetitions will occupy a greater space in the selected mask, in this case the map of Mexico.

First of all is necessary call the libraries that we will use: principally **pandas**, **numpy** and **matplotlib**, this are very important for the data management and representation.

Libraries like **request** and **BeautifulSoup** are important to get and pull out data from HTML and XML files and are commonly used for web scrapping.

From every year report from the Mexico's president we obtained a different png image.

## First government report
![PrimerInformedeGobierno](https://user-images.githubusercontent.com/37748958/139569571-9b34373e-8598-42f2-94fb-585eefb69ce8.png)

## Second government report
![SegundoInformedeGobierno](https://user-images.githubusercontent.com/37748958/139569575-e503e024-f3c8-48fc-a184-8f1f5d2755c3.png)

## Third government report
![TercerInformedeGobierno](https://user-images.githubusercontent.com/37748958/139569586-f4c778f5-3846-4671-a9b9-166e731c944b.png)

##### Over time the discourse has changed, highlighting the increment/decrement of different words including the appearance of new ones.

The data used for this project was scraped from the official government speechs transcription site https://lopezobrador.org.mx/

# Klasifikacija novinskih vesti
Ovaj projekat je nastao u svrhu kursa Mašinsko učenje na Matematičkom fakultetu. 
### Podaci
https://www.kaggle.com/rmisra/news-category-dataset
### Postavka zadatka
Na osnovu skupa podataka izvršena je klasifikacija i isprobani razni modeli mašinskog učenja, nakon čega su analiyirani i upoređeni dobijeni rezultati.

### Predprocesiranje podataka
Baza podataka se sastoji od tekstualnih atributa koje opisuju novinske članke(naslov, autor, link, kratak opis i datum kreiranja) i ciljnje promenljive kategorije samih vesti. Nad podacima su prvo obrisani duplikati i spojene kategorije koje su bile ekvivalentne(npr. ARTS & CULTURE" i "CULTURE & ARTS"). Zatim je izvršeno standardno prdprocesiranje teksta (brisanje znakova interpunkcije, čestih reči kao što su a, an, the, I i slično i brojeva) kao i lemitizacija.Sledeći korak je vektorizacija i podela na test, trening i validacioni skup.
### Modeli
Modeli su prvo formirani za skup svih kategorija. Usled velikog broja kategorija(36) modeli nisu bili najsavršeniji pa je broj kategorija redukovan na 10 gde su uzete one kategorije koje su se najbolje klasifikovale u modelu od 36 kategorija. Na kraju je urađena i binarna klasifikacija dveju najbrojnijih kategorija.
### Metode
- neuronske mreže
- knn
- naivni Bajes
- logisticka regresija
### Biblioteke
- sklearn
- numpy
- pandas
- nltk
- tensorflow
- keras
- matplotlib
- pickle
- string




 ### Autori:
- [Tijana Tošev, 1101/2019](https://gitlab.com/tijanatosev)
- [Jovana Nikolić, 1106/2019](https://gitlab.com/nickjovana)

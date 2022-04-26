# TSP

Denne oppgaven ble løst med dijkstra implementasjonen som ble gitt til oss i Canvas. Denne oppgaven gikk ut på å finne den billigste veien fra Timisoara til Bucharest i Romania. Siden vi fikk en oversikt over alle byene og kostandene for å komme seg mellom byene har jeg ikke kjørt noe benchmarking fordenne oppgaven. Siden datamaskinen allerede vet kostandene mellom alle byene vil den alltid velge samme vei og ingenting klommer til å endre seg uansett hvor mange ganger jeg kjørte det. Hadde jeg derimot hatt en annen algoritme å sammenligne den med vill benchmarking vært et alternativ for å se hvem som er mest effektiv av de to.

Bildet inneholder den korteste veien mellom start og slutt
![image](https://user-images.githubusercontent.com/79580243/165332580-50b4e8ea-d205-4d37-a4bc-250354b6d5c3.png)

Resultatet viser at den billigste måten å komme seg fra Timisoara til Bucharest er å først dra til Arad som er node 2, så til Sibiu som er node 7, så til Rimmicu Vilcea som er node 11, så til Pitesti som er node 13 og til slutt til Bucharest.

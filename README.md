# DecisionTree-PCA-Apriori in Matlab
 In this repository i am going to implement Decision Tree, Principle Component Analysis, Apriori in Matlab with an example.

## 1. PCA – Hauptkomponentenanalyse: 

Die Hauptkomponentenanalyse (englisch Principal Component Analysis, kurz PCA) ist ein Verfahren der multivariaten Statistik. 
Man versucht die Attribute zu ersetzen durch eine Menge von Linearkombinationen dieser, wodurch die Anzahl reduziert wird.

<figure class="image">
  <img src="./img/1.png">

</figure>
  <div align="center">
  Daten von einem 3 dimensiomnalen Vektorraum in einen 2 dimensionalen Vektorraum
 </div>

Die Daten werden dabei durch eine Hauptachsentransformation in einen Vektorraum mit einer neuen Basis überführt und dadurch wird die Korrelation der Attribute minimiert.

Das ganze lässt sich gut anschaulich erklären, wenn man die Daten als Wolke oder Ellipse in einem n-dimensionalem Raum auffasst. Dabei wird der Ursprung des Koordinatensystems in den Schwerpunk der Wolke gelegt. Nun werden nach und nach die Achsen so ausgerichtet, dass den Richtungen mit der größten Varianz bzw. der größten Ausdehnung folgen. Dabei entspricht die erste Achse der größten Ausdehnung und die zweite Achse der zweitgrößten Ausdehnung

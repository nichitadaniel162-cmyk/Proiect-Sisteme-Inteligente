Proiect Machine Learning: Analiza PCA vs t-SNE si Clasificarea Cifrelor

###1) DE CE AM ALES PROIECTUL
Am ales acest proiect deoarece reducerea dimensionalitatii este o problema fascinanta si esentiala in invatarea automata. M-a atras foarte mult ideea de a lua date complexe, cu multe dimensiuni (cum sunt miile de pixeli dintr-o imagine), si de a le comprima in 2D sau 3D pentru a le putea vizualiza si intelege uman. De asemenea, mi-am dorit sa compar o metoda liniara clasica (PCA) cu o metoda neliniara avansata (t-SNE) si sa observ practic cum afecteaza aceste transformari performanta si viteza unor algoritmi clasici de clasificare.

### 2) UN LINK DE UNDE AM LUAT DATELE
Pentru acest proiect am ales celebrul set de date MNIST, care contine 70.000 de imagini reprezentand cifre scrise de mana (de la 0 la 9). 
- **Link catre date:** [OpenML - MNIST_784](https://www.openml.org/d/554)


### 3) OBIECTIVELE PROIECTULUI MEU
Problema principala pe care incerc sa o rezolv este recunoasterea cifrelor scrise de mana intr-un mod cat mai eficient.
1. Sa curat, sa explorez si sa pregatesc setul de date MNIST pentru antrenare (EDA).
2. Sa implementez si sa analizez vizual algoritmii PCA (Principal Component Analysis) si t-SNE pentru reducerea dimensiunilor.
3. Sa folosesc datele transformate pentru a antrena si optimiza 3 algoritmi diferiti de Machine Learning (KNN, Random Forest si SVM).
4. Sa compar modelele din punct de vedere al acuratetii si al timpului de executie, justificand alegerile facute si extragand concluzii clare.

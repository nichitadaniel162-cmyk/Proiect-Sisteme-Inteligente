Analiza Tehnicilor de Reducere a Dimensionalității: PCA vs t-SNE

  📝 Descrierea Proiectului
   Acest proiect se concentrează pe studiul și aplicarea a două metode fundamentale de reducere a dimensionalității: **PCA (Principal Component Analysis)** și **t-SNE (t-distributed Stochastic Neighbor Embedding)**. 

Tema aleasă vizează un set de date din domeniul sănătății (donarea de sânge). Scopul este de a transforma datele multidimensionale într-un spațiu bidimensional pentru a identifica structuri ascunse, clustere de donatori și pentru a compara modul în care o metodă liniară (PCA) versus una non-liniară (t-SNE) reușește să păstreze informația esențială.

   📊 Sursa Datelor
Setul de date utilizat este **Blood Transfusion Service Center**, preluat de pe platforma OpenML.
* **Link către date:** [OpenML Dataset ID 1464](https://www.openml.org/search?type=data&sort=runs&status=active&id=1464)
* **Descriere:** Datele conțin informații despre 748 de donatori, având următoarele atribute:
    * **Recency:** Luni de la ultima donare.
    * **Frequency:** Numărul total de donări.
    * **Monetary:** Cantitatea totală de sânge (c.c.).
    * **Time:** Luni de la prima donare.
    * **Target:** Variabilă binară (dacă persoana a donat sau nu în perioada analizată).

   🎯 Obiectivele Proiectului
1. **Curățarea și Standardizarea datelor:** Pregătirea atributelor numerice pentru algoritmi (scalare obligatorie).
2. **Aplicarea PCA:** Reducerea dimensionalității prin maximizarea varianței și vizualizarea raportului de informație păstrată.
3. **Aplicarea t-SNE:** Vizualizarea relațiilor non-liniare și optimizarea hiperparametrilor (perplexity, learning rate) pentru o segmentare vizuală clară.
4. **Analiză Comparativă:** Evaluarea celor două metode în ceea ce privește separabilitatea claselor de donatori.


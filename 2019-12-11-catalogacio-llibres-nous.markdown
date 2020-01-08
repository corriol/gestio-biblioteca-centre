# Catalogació de llibres nous

Una vegada dins del sistema PMB cal comprovar si el llibre ja està registrat des de l’opció catàleg. L’opció més ràpida és la búsqueda per ISBN que podrem llegir amb el lector de codi de barras.

![Cerca per ISBN](/assets/img/cataleg00.png)

En cas que el llibre no estiguera caldrà afegir-lo al catàleg. La millor opció és capturar les dades mitjançant *el protocol Z39.50* que es troba al menú lateral baix de tot.

![Captura de dades via Z39.50](/assets/img/cataleg02.png)

Les biblioteques principals són:

* Biblioteca Nacional
* Catálogo Colectivo Bibliotecas España
* Rebeca

Haurien d’estar seleccionades, tal com mostra la imatge anterior. En aquest cas també és la millor opció usar l’ISBN.


En els resultats de búsqueda tenim disponibles les ocurrències del llibre trobades.

![Resultats de búsqueda Z39.50](/assets/img/cataleg03.png)

En prémer `Resultats` obtindrem les ocurrències trobades.

![Ocurrències trobades Z39.50](/assets/img/cataleg04.png)

En aquest cas usarem la segona opció ja que inclou també el nom de l'autor. A vegades pot ser que hi hagen diverses edicions d'un llibre, caldrà triar la que es correspon amb el nostre exemplar.

Com es pot observar en la imatge anterior, a vegades, en algunes ocurrències les paraules accentuades es mostren amb errors. Caldrà corregir-ho abans de copiar el registre.

Com s'observa en la imatge següent, ja hem corregit els cognoms de l'autor. Altre camp important és el d'*Indexació decimal* que ens facilitarà la generació del teixell. En el nostre cas en ser un llibre sobre les matemàtiques l'hem indexat com a tal.

![Corregir i ampliar la informació](/assets/img/cataleg05.png)

Després de corregir i ampliar la informació del registre cal `Copiar el registre`

Una vegada copiat el registre caldrà crear l'exemplar. El número d'exemplar s'assignarà automàticament.

![Registre insertit](/assets/img/cataleg01.png)

Cal parar especial atenció amb la signatura que seguix el següent esquema:

INDEXACIÓ CDU (cal veure l'esquema)
AUTOR (3 primeres lletres del cognom)
titol (3 primeres lletres del titol sense articles)

Com que el llibre que hem inserit és *Ernesto el aprendiz de matemago* de José Muñoz Santonja i la temàtica són les matemàtiques (index 51 del CDU) la signatura que posarem serà

En el nostre cas: 51 MUN ern

El número d'exemplar es genera automàticament i caldrà anotar-lo per després poder traure els teixells.

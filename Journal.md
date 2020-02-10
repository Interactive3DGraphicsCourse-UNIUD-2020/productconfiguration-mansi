# Journal
## Product Configuration - Interactive 3D Graphics
## Andrea Mansi UNIUD 2020

---

---
#### Giorno 1: 07/2/2020

- Scelta della tipologia di prodotto
- Specifica dei requisiti
- Pianificazione del progetto (stesura di una prima bozza di roadmap, contenente le fasi principale per completare il progetto.)

REQUISITI [ver 1]

| ID | Requisiti principali |
| :---:        |    :----:   
| 1 | La pagina web deve  visualizzare un oggetto 3D composto da diversi materiali|
| 2 | L'utente deve poter ruotare l'oggetto o la visuale |
| 3 | L'utente deve poter selezionare di quale materiale deve essere composta una specifica parte dell'oggetto |
| 3A | deve quindi poter selezionare la parte su cui agire |
| 3B | deve quindi poter selezionare il nuovo materiale |
| 4  | il sistema deve garantire buone performance su dispositivi mobili |



ROADMAP [ver 1]
| n° | Task | Priorità|
| :---:        |    :----:   | :---: |
| 1 |Modellazione di un prodotto composto da più parti da usare come test per le fasi successive.| Principale |
| 2 |Implementazione di un sistema che permetta di cambiare agevolmente il materiale di una |Principale |determinata parte del prodotto.|Principale |
| 3 |Implementazione di una GUI che permetta di interagire con il codice a run-time.|Principale |
| 4 |Ideazione del sistema di illuminazione|Principale |
| 5 |Ideazione di vari materiali per configurare il prodotto |Principale |
| 6 |Modellazione del prodotto finale |Principale |
| 7 |Creazione del sistema finale: luci, prodotto, GUI etc. |Principale |
| 8 |Sistema per il controllo delle luci | Opzionale |

### Lavoro svolto:

- Scelta del prodotto finale
- Scelta del software di modellazione e successiva creazione di un primo modello composto da 2 mesh come punto di partenza.
  - software scelto: Blender
- Strutturazione del codice iniziale, importazione del modello tramite GLTF.loader e prime sperimentazioni con l'assegnazione/cambiamento del materiale dei vari mesh

Primo modello di test

![ModelloDiTest](images/journal/img1.png)

Funzione di assegnazione di un nuovo materiale a una specifica parte del modello:

![Funzione1](images/journal/img1.png)

Funzione per creare dinamicamente nuovi materiali una volta selezionati vertex e fragment shaders:

![Funzione2](images/journal/img1.png)


---
---
#### Giorno 2: 08/02/2020

### Lavoro svolto:
- Implementazione BRDF Lambertiana + Microfacets
- Modellazione del primo prototipo di modello
- Primi test di rendering

Immagini del primo modello:

![PrimoModello](images/journal/img1.png)

Immagine del primo test di rendering:

![PrimoRender](images/journal/img1.png)


---
---
#### Giorno 3: 10/02/2018
- Aggiunta di una cubemap

![Cubemap](images/journal/img1.png)

- Implementazione della GUI per interagire con l'oggetto tramite la liberaria di THREE.JS

![PrimaGUI](images/journal/img1.png)

- Implementato un sistema che interagisce con la GUI e cambia a run-time le modifiche dell'utente sui materiali

![GIF modifiche](images/journal/img1.png)

- Update del Journal
- Pulizia del codice





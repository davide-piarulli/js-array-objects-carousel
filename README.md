Title
===
**Consegna:**
Dato un array di oggetti letterali con:
 - url dell’immagine
 - titolo
 - descrizione
Creare un carosello come nella foto allegata o come il vostro già realizzato.
**Milestone 0:**
Come nel primo carosello realizzato, focalizziamoci prima sulla creazione del markup statico: costruiamo il container e inseriamo l’immagine grande in modo da poter stilare lo slider.
**Milestone 1:**
Ora rimuoviamo i contenuti statici e usiamo l’array di oggetti letterali per popolare dinamicamente il carosello.
****
Al click dell’utente sulle frecce verso sinistra o destra, l’immagine attiva diventerà visibile e dovremo aggiungervi titolo e testo.
**Milestone 2:**
Aggiungere il **ciclo infinito** del carosello.** Ovvero se la miniatura attiva è la prima e l’utente clicca la freccia verso destra, la miniatura che deve attivarsi sarà l’ultima e viceversa per l’ultima miniatura se l’utente clicca la freccia verso sinistra.
**BONUS 1:**
Aggiungere le thumbnails (sottoforma di miniatura) ed al click attivare l’immagine corrispondente.
**BONUS 2:**
Aggiungere funzionalità di autoplay: dopo un certo periodo di tempo (3 secondi) l’immagine attiva dovrà cambiare alla successiva.
**BONUS 3:**
Aggiungere bottoni di start/stop e di inversione del meccanismo di autoplay.

## STEP DA SEGUIRE
1. inizializzo my-carousel-images dove creerò dinamicamente le mie img
2. aggiungo con il for each in modo statico img grande, thumbnails ed i 2 bottoni
3. aggiungo classe active sia a img grande e a thumbnail
4. richiamo i bottoni e credo gli eventi click ad ogni bottone
5. creo le 2 funzioni per i bottoni che poi aggiungo nei click degli stessi
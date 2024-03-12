Title:Vue Slider
===
**Descrizione:**
Partendo dal markup della versione svolta in js plain, rifare lo slider ma questa volta usando Vue.
**Bonus:**
1- al click su una thumb, visualizzare in grande l’immagine corrispondente
2- applicare l’autoplay allo slider: ogni 3 secondi, cambia immagine automaticamente
3- quando il mouse va in hover sullo slider, bloccare l’autoplay e farlo riprendere quando esce
4- al doppio click sullo slider cambia la direzione dell’autoplay

## SVOLGIMENTO
1. inserire le immagini grandi con un counter 
2. faccio un ciclo for( che mi restituirà sia gli elementi che gli indici) per le thumbnails per stamparle in pagina 
3. associo l'indice delle thumb al contatore delle immagini grandi in modo da visualizzare la stessa immagine e attivare la classe active 
4. creo la funzione che richiamo nei tasti next e prev associando i valori boooleani

### BONUS 1 
1. al click sulla thumb il contatore sarà uguale all'indice e verrà visualizzata l'immagine grande.

### BONUS 2
1. creo una nuova funzione con un setInterval che richiama la funzione nextPrev ad un intervallo di 2 sec 
2. richiamo la funzione loop in mounted


### BONUS 3
1. creo un flag di default true e lo metto come condizione per il loop delle immagini nel setInterval
2. creo gli eventi nel contenitore contenente tutto con mouseenter (dove il flag diventa false ) e mouseleave (dove il flag diventa true)


### BONUS 4 
1. 



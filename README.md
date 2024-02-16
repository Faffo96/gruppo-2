# Build week - Gruppo 2 

<!-- BANNER DA INSERIRE QUI --> 
![banner](https://github.com/Faffo96/gruppo-2/assets/157897660/d29a9fdb-2ce2-4ff5-857e-54d4cfbe7531)

<!-- piccola descrizione del progetto --> 
<h3 align="center" >L'obiettivo di questa build week era quella creare una copia della Benchmark platform di EPICODE quanto più possibile fedele all'originale, sia per aspetto, che per funzionalità.  </h3>

<br>
<!-- SPAZIO DA METTERE + BADGES (dynamic e static) --> 
<!-- https://shields.io/badges // link per creare le badges --> 
<br>


Ci siamo focalizzati su due principali fini : 
1. _La creazione del layout con HTML e CSS con classi pre-organizzate_
2. _La gestione dei vari collegamenti delle pagine e funzionalità tramite Javascript usando le idee progettate all'inizio_

<br>

## Table of Contents 
- [Come funziona](#come-funziona)
- [Partecipanti](#partecipanti)


<br> 


## Com'è strutturato

il nostro progetto è suddiviso in: 
> ![Static Badge](https://img.shields.io/badge/HTML-black?style=for-the-badge&logo=HTML5)

- Welcome page (index)

![index](https://github.com/Elekekic/EPICODE-REPO/assets/157897660/bd8e8e08-e745-4474-8e9c-d396cb854126)
<div align="center"> la prima pagina, composta da un titolo e vari paragrafi, con un button e una checkbox. Attenzione però, se non si clicca sulla checkbox non sarà possibile andare avanti! </div>


<br>


- Question page

![Domande-](https://github.com/Elekekic/EPICODE-REPO/assets/157897660/8c6db3b3-0155-42e8-aef1-339e4d0e7bf1)
<div align="center"> Seconda pagina, dove ci saranno una serie di domande e risposte con un timer in alto a destra. Alla sua scadenza le domande comunque proseguiranno </div>


 <br> 

 
- Results page

![resultts](https://github.com/Elekekic/EPICODE-REPO/assets/157897660/8afef1db-0d65-42f2-9403-81fbf85a229f)
<div align="center">  Terza pagine dove verranno visualizzati i dati raccolti dalle risposte in percentuale, con anche il numero di risposte corrette e sbagliati sottostanti, per proseguire bisogna cliccare il button "rate us" </div>


 <br>

 
- Feedback page

![feedback](https://github.com/Faffo96/gruppo-2/assets/157897660/d28399e4-0281-4ed2-b30b-1e0b1e332238)
 <div align="center">  Quarta pagina, in questa pagina si può lasciare una valutazione tramite la selezione da 1 a 10 delle stelle e lasciando un commento </div>


 <br> 

  
 ![Static Badge](https://img.shields.io/badge/Javascript-black?style=for-the-badge&logo=javascript)

- Welcome page
- Question page
- Results page
- Feedback page


  <br>

  
 > ![Static Badge](https://img.shields.io/badge/CSS-black?style=for-the-badge&logo=CSS3)
- Stylesheet unico


<br>

  
## Come funziona 
in pratica spiegare il js delle varie pagine 

- _**prima pagina**_:
  
la logica di questa pagina si basa sul click del button e della checkbox. 
Se la checkbox è stata cliccata, quando anche il button verrà cliccato ci porterà direttamente alla prossima pagina.
Altrimenti comparirà  un messaggio sotto la checkbox per indicare all'user di eseguire prima quel step per riuscire a proseguire. 

<br>

- _**seconda pagina**_:
  
Qua invece la logica è un po' più complessa:
Abbiamo un array di domande e risposte da dover implementare nella pagina grazie a dei "document.getElementbyID" e "innerText". (continua)

<br>

- _**terza pagina**_:

La logica qui fa si che ci porti i dati raccolti nella pagina prima in forma di array diviso in stringe, con valori booleani dentro.
I risultati poi, vengono visualizzati nel grafico a ciambella tramite quattro principali modalità: 
1. Variabile di chart.js con le sue proprietà dentro in modo da porterlo visualizzare nella pagina
2. Funzione denominata "stampa" fa si che per ogni risposta 'true' o 'false', si aggiungeranno alle loro rispettive variabili per tenere conto delle risposte date, per poi essere mostrate ai lati del grafico in forma di percentuale.
3. Funzione di addEventListener che richiama al momento del caricamento della pagina la funzione 'init' avente dentro il grafico e la funzione stampa.
4. Un'altra funzione di addEventListener che al click del button "rate us" ci porterà alla prossima pagina. 

<br>

- _**quarta pagina**_:

In questa pagina la maggior parte delle funzioni stanno nel attivare



<br> 
<!-- SPAZIO DA METTERE + COLLEGARE IL LINK DELL'ACCOUNT GIT A CIASCUNO DI NOI (metti badges anche qua) --> 

## Partecipanti

| PARTECIPANTI | RUOLI | ACCOUNT GIT | 
| ----------- |  ----------- | ----------- | 
| Fabio Scaramozzino | Team leader | ![Static Badge](https://img.shields.io/badge/Faffo96-%233eb752?style=for-the-badge&logo=github) | 
| Ferdinando Di Nocera | membro gruppo |![Static Badge](https://img.shields.io/badge/fdinocera-%23e2940d?style=for-the-badge&logo=github) |
| Felice Cesarano| membro gruppo |![Static Badge](https://img.shields.io/badge/felicecesarano-%233c4211?style=for-the-badge&logo=github) | 
| Rosa Giordano|  membro gruppo |![Static Badge](https://img.shields.io/badge/Rosannag16-%2323e3ea?style=for-the-badge&logo=github) | 
| Elena Kekic | membro gruppo | ![Static Badge](https://img.shields.io/badge/Elekekic-%23a30049?style=for-the-badge&logo=github) |
| Giancarlo Amoruso | membro gruppo | ![Static Badge](https://img.shields.io/badge/TheGianky-%235200af?style=for-the-badge&logo=github) | 

<br>

- [Torna su! :D](#Build-week---Gruppo-2)

<!-- anchor per tornare susususu --> 








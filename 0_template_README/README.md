SUPSI 2022-23  
Corso d’interaction design, CV427.01  
Docenti: A. Gysin, G. Profeta  

Elaborato 2: Antologia a due mani  

# Titolo progetto
Autore: Hans Manon  
[MediaPipe demo-ES6](https://ixd-supsi.github.io/2023/esempi/mp_hands/es6/1_landmarks)


## Introduzione e tema
Basandoci su alcuni temi scelti da noi da una lista che ci è stata fornita dai docenti, lo scopo del progetto era quello di realizzare una pagina web che trattasse del tema specifico da noi scelto. Nel mio caso, ho scelto il tema degli Anelli (in accordo con il tema focale del progetto Antologia a due mani, che vede come protagoniste appunto le mani). 


## Riferimenti progettuali
Per il mio progetto ho voluto realizzare una pagina web che prendesse in considerazione tre aspetti fondamentali sul tema Anelli, tre momenti per essere più specifici: la loro origine, la loro storia, e il loro presente. 


https://user-images.githubusercontent.com/6561331/236182302-68a6bd12-7b83-4d19-b83e-c9b7db795881.mp4


## Design dell’interfraccia e modalià di interazione
La pagina web è quindi stata progettata suddividendola in header, origini, evoluzione, presente e footer. Prendendo in considerazione le singole parti, le tre centrali, ho voluto lasciare la parte riguardante l'evoluzione degli anelli puramente visiva, inserendo solo poche informazioni importanti, un po' come se fossero una sorta di carta d'identità del gioiello. La prima e terza parte invece, sono prettamente testuali.

[<img src="doc/cards.gif" width="500" alt="Magic trick">]()


## Tecnologia usata
Per impostare tutto il progetto come prima cosa dopo alcune prove manuali ho impostato delle griglie precise entro le quali stare, in modo da ottenere un layout preciso e fisso. Ogni parte della pagine è suddivisa in blocchi ben evidenziati, per sottolineare ancora di più le fasi e le argomentazioni che si vanno a toccare. Di seguito, un estratto di codice usato per impostare la prima parte, l'header:


```Html
<body>
	<header>
	  <h1 class="page-title" style="padding: 80px; margin-top: 60px; color: white; font-size: 30px;">Anelli, gioielli senza tempo</h1>
	  <h1 class="page-title" style="padding: 80px; margin-top: -40px; color: white; font-size: 16px;">
		<span style="font-weight: lighter; margin-right: 30px;">origini</span>
		<span style="font-weight: lighter; margin-right: 30px;">evoluzione</span>
		<span style="font-weight: lighter;">significato</span>
	  </h1>
	  
	  
	  <h1 class="page-title" style="padding: 80px; margin-top: -40px; margin-left: 1300px; color: white; font-size: 16px;"> <a  href="https://ixd-supsi.github.io/2023/progetti/2_antologia_a_due_mani/" style=" color:white; font-weight: lighter; text-decoration: none;">indice</a></h1>
	  
	</header>
	  
	<img src="./assets/img/pexels-cottonbro-studio-4974392.jpg" alt="Immagine" 
	class= "img" style=" margin-top: -90px;">
```

## Target e contesto d’uso
La pagina è facilmente accessibile a tutti coloro capaci nell'utilizzare un computer. L'interazione principale che si può avere è molto limitata dato che si può solo effettuare uno scroll verso il basso. Questo tipo di layout unicamente verticale è stato scelto per facilitare la lettura e la consultazione delle informazioni presenti. In conclusione, il target di riferimento risulta abbastanza ampio; partendo da un adolescente e arrivando fino alle persone più adulte.

[<img src="doc/munari.jpg" width="300" alt="Supplemento al dizionario italiano">]()

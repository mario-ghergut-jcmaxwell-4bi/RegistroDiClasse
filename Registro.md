#<b> Registro Elettronico </b>
##<b> Descrizione programma </b>
Il programma permette ai professori e agli studenti di accedere al registro con delle credenziali. I professori potranno vedere i voti di tutta la classe mentre gli studenti potranno vedere i voti di ogni materia. viene calcolata una media per ogni materia e lo studente potrà vedere in rosso la scritta A RISCHIO BOCCIATURA se la media è insufficiente mentre in verde la scritta PROMOSSO se la media sufficiente.
  
###<b> Scomposizione in componenti semplici </b>
Utilizzo dei Macro Blocchi come componenti più semplici
###<b> Istruzioni di installazione </b>
Il registro elettronico online verrà installato in locale sul proprio pc. Inoltre sarà progettato per essere installato e utilizzato attraverso un server remoto, per consentire a tutti gli utenti di visualizzare i voti o scrivere gli argomenti delle lezioni svolte, tramite internet.
###<b> Manuale d’uso </b>
Se è la prima volta che si accede al registro si deve fare una registrazione con username e password che verrano richiesto ogni vola all'accesso appena si entra nella pagina del portale si potranno vedere delle caselline con su scritte le materie se si clicca sulla casellina appare con tutti i voti della materia stessa.Se la media è inferiore a 6 la scritta appare in rosso altrimenti appare in verde.Invece per i professori della materia appariranno tutti i voti ed ogni voto negativo verra scritto in rosso, e potra aggiungere e togliere i voti.
Se si prova ad accedere su un altro Pc apparirà la scritta "l'user è attuamente in uso in un altra piattaforma".
###<b> Architettura </b>
Il programma sarà suddiviso in 3 classi: la classe Voto, la classe RegistroProf, e la classe Studente. La classe Voto avrà come attributi il numero, di tipo float, mentre come metodi, il costruttore di nome Voto, setNumero che assegnerà il numero,di tipo float,e getNumero che richiederà il numero , di tipo float. Poi abbiamo la classe RegistroProf che avrà come attributi N, di tipo int, e un vettore di nome RegistroProf[]. Come metodi avremo il costruttore RegistroProf con parametro N, poi getN che richiederà il valore di N, poi InserisciVotoNominativo che inserirà il voto dello studente richiesto nel registro, con parametro voto , di tipo float, poi VisualizzaVotoNominativo che visualizzerà il voto dello studente richiesto nel registro, con parametro voto, di tipo float, poi InserisciMedia che farà la media dei voti dello studente richiesto, con parametro voto, di tipo float, poi VisualizzaMedia che visualizzerà la media dello studente richiesto, con parametro voto, di tipo float. la terza classe è Studente che avrà come attributo il nominativo di tipo string, poi i metodi saranno; costruttore Studente con parametro nominativo di tipo string, setNominativo che assegnerà il nominativo, con parametro nominativo di tipo string, poi getNominativo che richiederà il nominativo , di tipo string, poi VisualizzaVotoNominativo che visualizzerà il voto dello studente richiesto , con parametro voto ,di tipo float, e infine VisualizzaMedia che visualizzerà la media dello studente richiesto, con parametro voto, di tipo float.  
###<b> Autori </b>
<p> George Bostan </p>
<p> Mario Ghergut </p>
<p> Fabio De Cicco </p>
<p> Davide Tudisco  </p>

###<b> Ringraziamenti </b>

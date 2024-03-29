# **funzionamento corretto dell'interfaccia grafica:**

 Una volta avviata l'applicazione sulla sinistra mostra la lista degli acronimi errati, catalogati per il nome
 dell'acronimo e del nome breve quando disponibile, ad esempio CAP (senza nome breve) oppure GUIT - [\GuIT] (con nome breve)
 selezionando un acronimo nella lista, nella parte a destra ne vedremo le caratteristiche e le operazioni disponibili,
 in particolare per ogni acronimo selezionato verrà mostrato il nome esteso, sotto all'etichetta "Acronimo" e il motivo
 per il quale è finito nella lista degli errori sotto l'etichetta "Problema Riscontrato". Sotto all'etichetta "Correzione
 Proposta" è presente un menù a tendina che si attiva solamente quando l'acronimo è considerato errato perchè ha un
 nome esteso non corretto e mostra le varie correzioni proposte dall'applicazione, permettendo all'utente di selezionare
 quella più adatta, se nella lista delle correzioni è presente solo una correzione, l'etichetta è al singolare
 "Correzione Proposta", mentre se sono presenti 2 o più correzioni l'etichetta è al plurale "Correzioni Proposte",
 se invece l'acronimo è considerato errato perchè non è stato trovato nel dizionario, il menù rimane comunque bloccato,
 ma mostra il messaggio "Premi per aggiungerlo al dizionario". Di Default il menù mostra automaticamente la correzione
 più ottimale, così da far risparmiare tempo all'utente e di poterla correggere subito senza visionare le altre correzioni.
 Sotto a questi campi sono presenti dei pulsanti che permettono di correggere o ignorare gli errori, in particolare
 il pulsante "Aggiungi al dizionario" si attiva ogni volta che l'acronimo selezionato è errato, permettendo appunto di
 aggiungere al dizionario l'acronimo ( e di scriverlo nel file dizionario ).
 Il pulsante "Correggi" si attiva solo quando l'acronimo ha nome esteso non corretto, permette di correggere l'acronimo
 nel file con quello selezionato nel menù a tendina e di sovrascrivere il documento.
 Il pulsante "Ignora" si attiva ogni volta che l'acronimo è errato, permette di ignorare l'errore semplicemente rimuovendo
 l'acronimo dalla lista degli errori.
 Il pulsante "Correzione Automatica", sempre attivo, permette di correggere automaticamente il documento, correggendo solo
 gli acronimi con nome esteso non corretto e scegliendo per loro la correzione più ottimale.
 Sulla sinistra è inoltre presente un altro pulsante, "Visualizza Lista Completa" che permette di cambiare la lista
 visualizzata da quella degli errori a quella completa, in questo caso l'applicazione continua a funzionare e a offrire
 le stesse funzionalità, solamente che quando si seleziona un acronimo corretto sono disabilitati i pulsanti per la
 correzione e viene visualizzato sotto all'etichetta "Problema riscontrato", Corretto. Si può tornare a visualizzare la
 lista degli errori con lo stesso pulsante, che ha cambiato nome in "Visualizza Acronimi Errati".
 Una volta aggiunto un acronimo manualmente nel dizionario il tool ci da la possibilità di ripensarci e di andare a
 rimuoverlo dal file dizionario, infatti basta visualizzare la lista completa degli acronimi, selezionare l'acronimo
 appena inserito nel dizionario e cliccare sul pulsante "Rimuovi dal dizionario" (Lo stesso pulsante che precedentemente
 ci ha permesso di inserlo nel dizionario, ma con un nome diverso).

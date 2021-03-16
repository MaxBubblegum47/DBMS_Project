Per utilizzare "Digital Delivery & Shipping N.32" è necessario creare un database, quindi fare login nel tool di amministrazione del DBMS e creare un nuovo server.
Una volta fatto ciò, aprire il file "Table", copiare tutto il contenuto ed incollarlo nel qeury tool del nuovo database. 

Ripetere l'operazione per il file "Trigger" ed infine "Dati Inserimento". Le query di interrogazione che abbiamo generato sono all'interno di "Query Interrogazione_Update_Delete";
per poterle utilizzare è necessario copiare e incollare all'interno del query tool del medesimo database solamente il codice sql. Per chiarezza sono state numerate e descritte
nel titolo di ciascuna di esse.

Per lanciare il file jar da console, posizionarsi(i) nella directory dove l'eseguibile è contenuto e digitare:

java -jar N_32.jar

Il programma chiederà l'address del server. Assumendo che il server sia stato chiamato "Digital Delivery & Shipping N.32" e stia utilizzando il socket default, inserire la seguente stringa:

postgresql://localhost:5432/Digital Delivery & Shipping N.32

Inserire ora nome utente e successivamente password.

--------------------------------------------------------------------------------------------------------------------------------------------------------
i: se si esegue l'operazione su sistema operativo windows basta aprire la cartella contenente il file N_32.jar, premere "File" in alto a sinistra,
premere "Apri WindowsPowerShell" e successivamente nel secondo menù a tendina premere "Apri WindowsPowerShell". Infine eseguire la stringa riportata
poca'anzi.

Se si esegue su sitema operativi UNIX basta premere il tasto destro del mouse sulla cartella contente N_32.jar e premere
"apri nel terminale", dopodiché copiare ed eseguire la stringa citata poc'anzi. Se il terminale dovesse dare errore verificare che si sia installato java
sul sistema operativo UNIX e a tal proposito consigliamo questa guida: https://linuxize.com/post/install-java-on-ubuntu-18-04/
-----------------------------------------------------------------------------------------------------------------------------------------------------------

Algeri Riccardo, Cavalli Mattia e Stigliano Lorenzo.

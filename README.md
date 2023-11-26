# Wine-Store (ENG)

[![Windows](https://img.shields.io/badge/Windows-11-blue?style=flat-square&logo=windows&logoColor=white)](https://www.microsoft.com/windows/) [![Eclipse IDE](https://img.shields.io/badge/Eclipse%20IDE-2021--09-5B69E8?style=flat-square&logo=eclipse-ide&logoColor=white)](https://www.eclipse.org/ide/) [![Java](https://img.shields.io/badge/Java-11-ED8B00?style=flat-square&logo=java&logoColor=white)](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html)

Assignment 2 - Software Engineering UniPR

The objective is to define UML diagrams for use cases and classes that document a software system for online wine sales, and to implement the system in Java, using appropriate object-oriented programming techniques.

Wines are identified by name, producer, year, technical notes, and the grape varieties they are derived from. Note that the system must also keep track of the number of bottles for each wine and vintage produced.

The system interacts with users (people who want to purchase wine) and employees (people who manage the sales). Each person is identified by their first name, last name, and email address.

A user can register, search for wines by name and production year, and purchase wine bottles after authenticated login. An employee can ship wine bottles to customers and replace sold bottles.

Every time a user places an order for a certain number of bottles of a given wine, the operation must be recorded by the system, which also decrements the number of bottles available for sale. If the stock reaches zero, the system must indicate the stock depletion, and the employee must acquire an appropriate number of bottles of that wine type. Upon arrival of the bottles, the system should update the data accordingly.

If the bottles of a particular wine are not available, a user can subscribe to a notification request for the availability of the desired number of bottles to be purchased. When the requested bottles become available, the system notifies the user of their availability.

Once the system code is defined, a simple simulation needs to be implemented that:
1) Initializes the system with some users, an employee, and wines.
2) User UX registers and purchases some bottles of a certain wine UX.
3) User UY registers and purchases all the bottles of a certain wine UY.
4) User UZ registers and wants to purchase some bottles of the no longer available wine UY. User UZ requests a notification when the wine UY is available again.
5) The employee adds a certain number of bottles of wine UY, and the system notifies user UZ of the new availability of the wine.

# Wine-Store (ITA)

Assignement 2 - Software Engineering UniPR

L’obiettivo è definire i diagrammi UML dei casi di uso e delle classi, che documentano un sistema
software per la vendita online di bottiglie di vino, e implementare il sistema in Java, utilizzando in
modo appropriato le tecniche di riferimento della programmazione orientata agli oggetti.
I vini, sono identificati da: nome, produttore, anno, note tecniche, e i vitigni da cui derivano. Si noti
che il sistema deve anche tenere traccia del numero di bottiglie di ogni vino per ogni annata prodotta.
Il sistema interagisce con utenti (persone che vogliono acquistare del vino) e impiegati (persone che
gestiscono la vendita). Ogni persona è identificata da nome, cognome e indirizzo email.
Un utente si può registrare, fare ricerca dei vini per nome e anno di produzione e acquistare bottiglie
di vino dopo un accesso autenticato. Un dipendente può spedire le bottiglie di vino ai clienti e
rimpiazzare le bottiglie di vino vendute.
Ogni volta che un utente fa un ordine per un certo numero di bottiglie di un dato vino, l’operazione
deve essere memorizzata dal sistema che inoltre provvede a decrementare il numero di bottiglie che
possono essere messe in vendita. Se la giacenza diventa nulla, il sistema deve segnalare l’esaurimento
delle scorte e l’impiegato deve quindi acquisire un numero adeguato di bottiglie di quel tipo di vino
e, all’arrivo delle bottiglie, aggiornare i dati sul sistema.
Nel caso in cui le bottiglie di un particolare vino non sono disponibili, allora un utente può
sottoscrivere una richiesta di notifica sulla disponibilità del numero di bottiglie che vorrebbe
acquistare: quando le bottiglie richieste saranno disponibili, il sistema notificherà la loro disponibilità
all’utente.
Definito il codice del sistema, bisognerà implementare una semplice simulazione che:
1) Il sistema viene inizializzato con alcuni utenti un impiegato e dei vini;
2) Un utente UX si registra e fa l’acquisto di alcune bottiglie di un certo vino UX;
2) Un utente UY si registra e fa l’acquisto di tutte le bottiglie di un certo vino UY;
3) Un utente UZ si registra e vuole fare l’acquisto di alcune bottiglie del vino UY non più disponibile
e chiede di ricevere una notifica quando il vino UY sarà di nuovo disponibile;
4) L’impiegato aggiunge un certo numero di bottiglie del vino UY e il sistema notifica l’utente UZ
della nuova disponibilità del vino.

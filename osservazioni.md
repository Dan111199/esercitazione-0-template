# Osservazioni — Esercitazione 0

Gruppo:

Componenti (nome, cognome e username GitHub di entrambi): Daniele Palmaccio Dan111199, Alessio Cosmin dragomir dragomir-ac

URL del repository condiviso:https://github.com/Dan111199/esercitazione-0-template.git

Chi ha usato la tastiera nello step 1 e nello step 2: Meta' per ognuno in ogni step

Compilate insieme le osservazioni e discutete le risposte: entrambi dovete
saper spiegare le prove svolte.

## Step 1 — Hello World: compilazione ed esecuzione

Comando di compilazione: gcc -std=c17 -Wall -Wextra -Wpedantic -Werror hello.c -o hello

Comando di esecuzione e risultato osservato: ./hello, e' andato solo a capo senza stampare niente su terminale

Che cosa ho capito su sorgente ed eseguibile: modificando la sorgente ma non ricompiando il file l'eseguibile rimane alla versione precedente.

Output richiesto e comportamento del programma prima della modifica: nulla perche' il programma aveva soltanto "return 0" nel main, pero' compilava lo stesso perche' all'effetivo non c'erano errori nel codice.

Esito dopo la modifica e spiegazione della correzione: "Hello, computational physics!" e a capo. Nel main e' stato scritto un comando che stampava una frase, percio' dopo averlo compilato e' uscito scritto nel terminale.

## Step 1 — Git

Quali file ho incluso nel commit e perché: osservazioni.md e hello.c perche' sono i file utili che ho modificato e che ho bisogno che siano aggiornati. Ho aggiunto un commento per tracciare ciò che è stato cambiato

Come ho verificato che la versione provata sia presente su GitHub: andando sulla cronologia delle modifiche ho potuto vedere cio' che era stato cambiato. I dati su terminale e su github corrispondono

Che cosa ho osservato prima e dopo `git pull`, e perché non serve un nuovo clone: prima di git pull il file su computer e' rimasta l'ultima versione salvata localmente. Dopo il pull, il file e' cambiato, aggiungendo le modifiche effettuate sul sito. Non serve un altro clone perche' il collegamento con il server era ga' stato effettuato.

## Step 2 — Eco: prima prova

Argomenti passati, comando e risultato: argomenti: "boh, 010, 1.20202222222
", comando: "./eco boh 010 1.20202222222", risultato: "boh 10 1.202022"


Che cosa posso concludere: i comandi atoi e atof permettono di convertire in numeri delle stringe che possono anche contenere alcuni errori, come lettere al posto di numeri, o cifre inutili. puo' essere utile per dare valori direttamente da terminale invece che modificare ogni volta il programma.

## Step 2 — Eco: seconda prova

Argomenti passati, comando e risultato: "ok, A23c, 1.054" , comando: "./eco ok, A23c, 1.054", risultato: "ok, 0 1.054000"

Che cosa ho capito su testo, conversioni e stampa: posso inserire lettere solo dopo i numeri, ma dal terminale posso cambiare i valori del codice in maniera piu' rapida ed efficace. Grazie alle conversioni posso dare degli input numerici anche se teoricamente vengono percepiti come stringhe.

## Step 2 — Risultato ed errori

Previsioni per l'esecuzione con argomenti validi e per quella con `dodici`: previsione validi: "ciao 12 3.500000", previsione 'dodici': "Usa: ./eco TESTO INTERO REALE"

Contenuto di `eco.txt`, messaggi nel terminale e codici di uscita osservati: "ciao 12 3.500000", "Usa: ./eco TESTO INTERO REALE"

Come un controllo automatico può riconoscere un errore: Lo si puo' riconoscere dando delle frasi o dei valori di riconoscimento che bloccano l'esecuzione del programma scritto

## Step 2 — Parametri e calcolo fisico

Quando serve ricompilare e quando basta cambiare gli argomenti: serve ricompilare se devono essere modificate le funzioni interne al programma, mentre per modificare soltanto i valori basta scriverli su terminale

## Step 2 — Git

Come riconosco nella cronologia i commit dei due step: li riconosco  dal file che ho uploadato e dal commento opportunamente scelto

Come ho verificato che la versione finale sia presente su GitHub: ho controllato nella cronologia e ho verificato che il codice fosse giusto

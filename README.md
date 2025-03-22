LA DEFINIZIONE

Vorrei creare un videogioco di Tris moderno, bello e fresco dal front-end fino al back-end, consiste in un'attività strategica per due giocatori che si svolge su una griglia quadrata di 3×3 caselle. Ogni giocatore utilizza un simbolo specifico, generalmente X o O , e l'obiettivo è formare una linea di tre simboli consecutivi (in orizzontale, verticale o diagonale) prima dell'avversario. I giocatori si alternano nell'inserire il proprio simbolo in una casella vuota fino a quando uno dei due completa una fila di tre o tutte le caselle sono occupate (risultato in pareggio). 

IL DESIGN

Non deve essere un videogioco di Tris qualsiasi, deve assolutamente avere queste funzionalità che ti sto per elencare. La UI e UX, devi creare un interfaccia coerente, moderna, tasti animati e uno sfondo a tema Tris nella schermata home (ad esempio delle X e O che fanno tris su delle griglie generate a caso (chiaramente non sovrapposte l’una con l’altra e non interagibili dal giocatore). Quindi per la UX e UI devi utilizzare Material Design 3 sviluppato da Google: https://m3.material.io/ 
Dovrà avere una ottima gerarchia delle informazioni, ad esempio dare la priorità ai tasti più importanti del gioco (come i tasti delle modalità rispetto ad altri); prendi spunto da questo sito: https://www.robadagrafici.net/che-cose-la-gerarchia-nel-design-una-guida-alluso-della-gerarchia-visiva-per-una-piu-facile-comprensione/
Visto che non sono un designer, non so darti delle dritte specifiche, perciò sentiti libero di cercare nel web. 

LA SCHERMATA HOME

Quando il giocatore aprirà il gioco, si ritroverà la schermata home, il cuore pulsante che consente al giocatore di iniziare. Il giocatore o i giocatori avranno la possibilità di immettere il proprio nome prima di iniziare qualsiasi modalità; questo serve per salvare le statistiche dei giocatori in locale sul dispositivo (Vittorie; Sconfitte e Pareggi). La schermata avrà i seguenti tasti:

    • Single Player (o “Giocatore Singolo” in italiano): Consente al giocatore di iniziare a giocare a Tris contro l’intelligenza artificiale, che avrà 3 livelli di difficoltà (Facile; Media; Difficile) Nota: la modalità difficile non deve essere imbattibile. L’intelligenza artificiale avrà un nome, si chiamerà semplicemente IA (o “AI” in inglese).

    • Multiplayer (o “Multigiocatore” in italiano): Consente al giocare di iniziare a giocare contro una persona umana (cioè una vera).

    • Learn (o “Impara” in italiano): Consente al giocatore di imparare delle tecniche avanzate nel Tris, quindi migliorare le proprie capacità di gioco. Questa sezione del videogioco deve avere animazioni fluide, dinamiche e smooth dal punto di vista del design; in modo da rendere più coinvolgente il percorso di apprendimento. Inoltre dovrà avere una funzionalità nel rilevare gli errori del giocatore, e quindi tramite l’intelligenza artificiale open-source gratuita in locale sul dispositivo direttamente dall’app, può imparare dai propri errori.




    • Settings (o “Impostazioni” in italiano): Consente al giocatore di modificare la propria esperienza di gioco, avrà la possibilità di modificare il tema da scuro a chiaro e viceversa, modificare l’alto contrasto, ingrandire il testo di tutta l’applicazione, il feedback aptico del dispositivo (che andrà in funzione durante le azioni importanti), il lettore di testo per i non vedenti, la modifica della lingua (Inglese e Italiano), informazioni sull’applicazione (created by Trae AI; by rickytech7 etc…). Ogni impostazione dovrà essere abbinata con icona giusta e soprattutto dare un’ottima gerarchia delle informazioni.  

    • Statistics (o “Statistiche” in italiano): Consente al giocatore di salvare le proprie statistiche (e di altri), vittorie, pareggi e sconfitte, accompagnato prima con il nome del giocatore in questione; è tutto questo salvato in LOCALE sul dispositivo. Dovrà avere l’icona del trofeo.

LA SCHERMATA DI GIOCO

Una volta inserito il nome, si accederà alla schermata di gioco; la schermata più importante dell’intero gioco. Nella parte centrale ci sarà la griglia 3x3, in alto ci sarà una barra che conterrà le informazioni dei giocatori (nome) e le vittorie, pareggi e sconfitte nel intera partita. Una volta finita volontariamente la partita, le statistiche dei giocatori di quella partita verranno salvate in locale nel dispositivo (infatti l’obiettivo di questo videogioco è la PRIVACY, che ad oggi è un concetto obsoleto). 

Quando un giocatore fa Tris, cioè che allinea i tre simboli consecutivamente, ci sarà un’animazione che rispecchia il tema del gioco (Material Design 3), che passa per il centro delle lettere (O o X) per indicare la vittoria, prima di chiedere di continuare la partita o terminarla. 

COMPATIBILITÀ

Questo gioco deve essere ottimizzato per qualsiasi dispositivo mobile esistente sulla faccia della terra! Sarà compatibile con Android e IOS.
Come linguaggio di programmazione ti consiglio Flutter, ma se trovi un linguaggio migliore, usa quello. Tutti i commenti dovranno essere in inglese, perché visto che sarà un progetto open-source con la certificazione, vorrei che sia comprensibile da TUTTI, nessuno escluso. Il codice deve avere meno errori possibili e segui alla lettera tutto quello che ti ho elencato.

Buon lavoro :)

by rickytech7

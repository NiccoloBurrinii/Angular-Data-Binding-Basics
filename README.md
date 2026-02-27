# Angular Data Binding Foundations

Progetto introduttivo allo sviluppo frontend con **Angular**, focalizzato sulla gestione del flusso di dati tra logica TypeScript e template HTML tramite Standalone Components.

## Descrizione
L'esercizio esplora le meccaniche fondamentali di reattività del framework Angular. Attraverso un'interfaccia semplice, il componente gestisce lo stato di un contatore e la proprietà di attivazione di un pulsante, dimostrando come Angular sincronizzi automaticamente la vista al variare delle variabili nel codice.



## Funzionamento del Sistema:
* **Standalone Architecture**: Utilizzo della struttura moderna di Angular (v17+) che elimina i moduli a favore di componenti indipendenti e configurazione tramite `app.config.ts`.
* **Interpolazione `{{ }}`**: Visualizzazione dinamica di stringhe e numeri (es. `title` e `numClick`) passando i dati dal file `.ts` direttamente nel template.
* **Property Binding `[ ]`**: Controllo degli attributi HTML tramite logica TypeScript, utilizzato nel progetto per disabilitare il pulsante (`[disabled]`) una volta cliccato.
* **Event Binding `( )`**: Gestione degli eventi utente tramite il listener `(click)`, che scatena l'esecuzione della funzione `clickButton()` nel backend del componente.
* **State Management**: Implementazione di una logica di aggiornamento dello stato che incrementa un contatore e modifica la disponibilità degli elementi della UI in tempo reale.

## Tecnologie e Concetti
* **Angular 17/18**: Framework frontend enterprise per la creazione di Single Page Applications (SPA).
* **TypeScript**: Linguaggio tipizzato per la gestione della logica applicativa.
* **Component-Based Development**: Separazione netta tra struttura (HTML), stile (CSS) e logica (TS).
* **CSS Scoped**: Utilizzo di stili incapsulati che influenzano esclusivamente il componente corrente (es. colore rosso degli header).

## Riepilogo Sintassi Utilizzata
| Sintassi | Tipo Binding | Direzione Dati | Scopo |
| :--- | :--- | :--- | :--- |
| `{{ valore }}` | **Interpolation** | TS ➔ HTML | Mostrare variabili a video |
| `[prop]="var"` | **Property** | TS ➔ HTML | Modificare attributi o proprietà HTML |
| `(click)="fun()"` | **Event** | HTML ➔ TS | Rispondere alle azioni dell'utente |

---
*Progetto sviluppato per consolidare le basi della comunicazione tra template e controller in ambiente Angular.*

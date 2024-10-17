# calcolo-numerico-git

Una raccolta di documenti a supporto dello studio del Calcolo Numerico utilizzando MatLab.

## Cosa troverai qui

Questa repository è una raccolta di esercizi e nozioni per il corso Calcolo Numerico 6 CFU dell'Università degli studi di Catania - Dipartimento di Matematica e Informatica.

Per aggiunte, modifiche, correzioni di errori e contribuire in generale a questa repository, utilizzare gli issues di Git oppure contattare uni400802@studium.unict.it

> Questa repository non è ancora ultimata. 
>
> In versioni successive della repository saranno aggiunti ulteriori elementi di teoria, miglioramento codice ed esercizi svolti da esami passati.

## Citazioni necessarie

Buona parte di queste note sono state prese e riadattate dal file PDF del collega R. Tringali, vedere la versione originale nel documento Note Tringali.pdf

## Cosa contengono le cartelle

### "Argomenti"

Contiene un file per argomento, ognuno con una spiegazione e spesso degli esempi. 

Il nome del file rappresenta l'argomento o il sotto-argomento trattato.

### "Funzioni utili"

Una piccola raccolta di funzioni o elementi interessanti nativi di matlab e delle sue estensioni, che potrebbero tornare comode dal punto di vista grafico, sintattico e della performance del codice.

Per maggiori informazioni sulle funzionalità di MatLab consultare i link presenti all'interno dei documenti.

### "PDFs"

Tutti i file con estensione pdf che possono essere utili per confronto e apprendimento. NON verranno pubblicati testi senza il consenso degli autori originali.

## Convenzioni

### Codice

Man mano che questa repository verrà aggiornata, questa sezione indicherà se ci sono elementi di codice "anomali" da tenere in considerazione.

> La [MATLAB Programming Style Convention di Richard Johnson](https://www.ee.columbia.edu/~marios/matlab/MatlabStyle1p5.pdf) fornisce un'ottima base sulle code conventions, invito a dare una lettura per adottare uno standard internazionale.

***Nomi delle variabili***

MatLab potrebbe interpretare il nome della variabile matrice_associata come
<img src="https://latex.codecogs.com/svg.image?\text{matrice}_{a}\text{ssociata}" />
quando riporta il suo nome, per esempio, in un plot.
Utilizzare \_ solo quando questo comportamento coincide con quello desiderato (per esempio x_0 --> <img src="https://latex.codecogs.com/svg.image?x_{0}" />).

Le variabili e le funzioni anonime utilizzeranno lo stile camelCase, le funzioni non anonime il PascalCase e le costanti saranno indicate in UPPERCASE.

***Plot Decorators*** 

Quando verranno usate delle funzioni a supporto del plot delle funzioni, saranno indentate sotto al plot di riferimento. La motivazione è quella di poter "separare" visivamente il resto del codice da ciò che ne è solo a supporto, garantendo una maggiore fluidità nella lettura. I comandi hold on e hold off verranno trattati come se fossero delle parentesi.

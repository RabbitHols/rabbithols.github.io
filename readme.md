# rabbithols.github.io

# CORS


Il funzionamento di Cross-Origin Resource SHaring (CORS) è semplice: permettere ad un sito di fare una richiesta ad un altro sito.

L'implementazione è sia lato server che client.


cors spec: https://fetch.spec.whatwg.org/


Capitolo 1:
Il capitolo tratta di:

- Quali problemi risolve CORS
- Come funzionano le richieste CORS
- I benefici di usare CORS

Di default il browser applica la same origin policy tramite cors deleghiamo a server a scegliere 
a chi vuole esporsi.

Il server deve autorizzare il client a includere intestazioni di richiesta personalizzate su una richiesta multiorigine. Questo comportamento è unico per le richieste multiorigine; le richieste della stessa origine possono includere qualsiasi intestazione di richiesta personalizzata. Se il server non inserisce nella whitelist le intestazioni della richiesta, la richiesta fallirà
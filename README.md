# IncluDO
## Il progetto
Il progetto prevede lo sviluppo di un sistema in TypeScript che modella la struttura operativa di una scuola di formazione professionale per migranti (IncluDO), concentrandosi sulle interazioni tra migranti, corsi di formazione e aziende partner.
## La struttura del progetto
<ol>
  <li>
    <p>Creare interfacce per i partecipanti, le aziende e i corsi</p>
  </li>
  <li>
    <p>Creare le classi per implementare le istanze</p>
  </li>
  <li>
    <p>Istanziare oggetti per le diverse classi</p>
  </li>
</ol>

## Sviluppo: logica e funzionamento
Il sistema è composto da tre istanze:
<ul>
  <li>
    <p>Partecipante: rappresenta i migranti iscritti ai programmi di formazione. IPartecipante include le informazioni personali e un metodo,"iscrivitiCorso", che consente l'iscrizione ad un corso specifico proposto dalla scuola.</p>
  </li>
  <li>
    <p>Corso: rappresenta i corsi di formazione offerti dalla scuola. ICorso contiene informazioni descrittive e un elenco degli iscritti. Inoltre è presente un metodo che consente l'iscrizioone aggiungere un         partecipante al corso.</p>
  </li>
  <li>
    <p>Azienda: rappresenta le aziende partner che offrono opportunità lavorative. Un’azienda può proporre una specifica posizione lavorativa a un partecipante formato.</p>
  </li>
</ul>
Le classi Partecipante, Corso e Azienda implementano le interfacce corrispondenti, fornendo l’implementazione concreta dei metodi definiti. A partire dalle classi vengono create le istanze, che rappresentano gli oggetti reali del sistema. Le interazioni operative avvengono esclusivamente tra questi oggetti. Un oggetto di tipo Partecipante interagisce con un oggetto di tipo Corso richiamando il metodo di iscrizione, che a sua volta utilizza i metodi esposti dall’interfaccia del corso per aggiornare l’elenco degli iscritti.

## Linguaggi utilizzati
<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="JavaScript" width="60" height="60"/>
</p>

### Link al CodePen <a>https://codepen.io/Stefano-Gollo/pen/yyJMqjJ</a> 

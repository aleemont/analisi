# Analisi Matematica
Appunti di Analisi Matematica per il corso di Ingegneria e Scienze Informatiche (A.A. 2021/2022).

INFO: https://corsi.unibo.it/laurea/IngegneriaScienzeInformatiche

Come collaborare:


Clone repository (Solo la prima volta)

>  git clone https://github.com/aleemont/analisi/

Oppure pull repository (Prima di iniziare a lavorare, obbligatorio o si causerà un conflitto)

> git pull origin main

Crea/Usa la tua branch (NomeCognome)

> git branch -M NomeCognome

Esegui le modifiche e aggiungi i file modificati

>  git add --all

Crea il commit (è consigliato creare un commit ogni volta che si modifica un file, e non creare modifiche esagerate per ogni commit, in modo da non dover
rivedere migliaia di righe prima di trovare un eventuale problema o altro)

>  git commit -m "Commento brevissimo sulle modifiche" -m "Commento più lungo (opzionale)"

Sincronizza le modifiche sulla tua branch

>  git push -u NomeCognome

Tutorial per LaTeX:

https://www.overleaf.com/learn

Compilatore LaTeX (Scelta consigliata per rendere più fluido il workflow con git):
**Attenzione, il compilatore non offre un'interfaccia grafica**

https://www.latex-project.org/get/

**Editor/Compilatore grafico per LaTeX**

https://www.xm1math.net/texmaker/

**Per sistemi GNU/Linux il pacchetto LaTeX è sicuramente disponibile nelle repository della vostra distro.**

Comandi per compilare da cli:

> pdflatex analisi.tex

**Se non si vuole scaricare il compilatore LaTeX si può utilizzare un compilatore online:**

https://www.overleaf.com

Utilizzare un compilatore online è ottimale per i principianti o per chi non è molto confident con la cli. Allo stesso tempo però renderà molto più macchinoso il workflow tramite git.
Bisognerà infatti:

  - Fare il pull della repo
  - Copiare e incollare il codice su overleaf
  - Modificare il codice
  - Scaricare il codice
  - Creare un commit
  - Fare il push sulla propria branch

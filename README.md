# OMG Virtual Lab

Simulazioni didattiche di elettronica ed elettrotecnica per il progetto **OMG — Elettroni e dintorni**.

## Struttura

- `index.html`: indice pubblico dei simulatori
- `assets/omg.css`: stile condiviso
- `resistenze-serie/index.html`: primo simulatore interattivo
- `.nojekyll`: disattiva la trasformazione Jekyll su GitHub Pages

## Pubblicazione senza terminale

1. Su GitHub crea un repository **pubblico** denominato `omg-virtual-lab` (puoi inizializzare senza README).
2. Estrai il file ZIP sul computer.
3. Nel repository usa **Add file > Upload files** e trascina i **contenuti della cartella** `omg-virtual-lab` (non il file ZIP). Mantieni le sottocartelle.
4. Conferma con **Commit changes**.
5. Apri **Settings > Pages**. In **Build and deployment**, seleziona `Deploy from a branch`; Branch: `main`, Folder: `/(root)` e premi **Save**.
6. Dopo la pubblicazione vai a `https://NOMEUTENTE.github.io/omg-virtual-lab/`.
7. Per incorporare su Google Sites: **Inserisci > Incorpora > Per URL**, incolla `https://NOMEUTENTE.github.io/omg-virtual-lab/resistenze-serie/`, poi ridimensiona il riquadro.

**Importante:** `NOMEUTENTE` è un segnaposto. Sostituiscilo con il nome del tuo account GitHub. Non configurare il dominio `ohmmygod.it` come dominio personalizzato di GitHub Pages: per il momento è già destinato a Google Sites.

## Aggiungere un simulatore

Crea la cartella `nome-simulatore/` contenente `index.html`, includi `../assets/omg.css`, e aggiungi il relativo link all'indice generale. Ogni app rimane autonoma.

## Verifiche didattiche

La simulazione attuale usa resistori e generatore ideali. La corrente in serie è uniforme, la resistenza totale è la somma e le tensioni parziali rispettano la legge di Ohm. Nessun dato degli studenti viene raccolto o inviato.

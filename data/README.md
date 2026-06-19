# Dataset

Questa cartella contiene i dataset CSV utilizzati dalla dashboard.

## Convenzioni

Ogni file CSV segue questa struttura di base:

- `valore`: il numero o la percentuale;
- `unita`: unità di misura (%, mln, mld €, anni, ecc.);
- `anno`: anno di riferimento;
- `fonte`: istituzione o report primario;
- `note`: caveat, approssimazioni o limiti interpretativi.

## Fonti preferite

- ISTAT
- Ministeri competenti
- OCSE / Eurostat
- Banca d'Italia
- CEPEJ
- UNHCR / Frontex
- Istituti accreditati (ISMU, Moressa, Antigone, CSM, DAP)

## Aggiornamenti

Quando aggiorni un dataset:

1. specifica l'anno di riferimento;
2. aggiorna la nota metodologica;
3. se il dato cambia un claim narrativo, aggiorna anche `index.html` e `dashboard.html`;
4. aggiorna `kpi_master.csv` nel repository hub.

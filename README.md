# BaseDati22_23

ESAME BASE DI DATI 2022-2023
Documentazione:
# Schema Entità
@ Specifiche

esistono 3 tipi di utente:
 - Segreteria:  -> Gestisce Studenti e Docenti
 - Docente:     -> Gestisce i calendari e le valutazioni
 - Studente:    -> si può iscrivere agli esami

I *Corsi* di laure sono composti da un insieme di *insegnamenti*
uno studente può iscriversi all'*esame* di un corso ma quest'ultimo può essere vincolato da degli esami *propeudetici* che devono essere prima stati superati
gli *esami dati* vengono registrati.





# Gestione Base di Dati
- Mantenimento informazioni studenti rimossi  (se uno studente rinuncia o si laurea i suoi recond vanno spostati in Tabelle Archivio).

- Gestione iscrizioni ad un esame, l'esame deve essere nel suo corso e rispetta le propeudeticità

- nel calendario non è possibile programmare più appelli dello stesso corso e dello stesso anno ( 2 esami dello stesso corso previsti per lo stesso anno non possono essere lo stesso giorno)

- produrre la carriera di ciascuno studente (con voti e dati di tutti gli esami sostenuti), la segreteria può stampare la carriera di tutti

- produzione carriera valida di uno studente

- produrre le informazioni complete per un corso di laurea (almeno l'elenco degli insegnamenti, con descrizioni e responsabile)



## WEB APP
- Segreteria:
    -creare e gestire utenze di docenti e studenti
    -inserisce e gestisce corsi di laurea ed insegnamenti
    -associa studenti e docenti ai corsi
- Docente:
    -Crea e gestisce il calendario degli esami dei propri insegnamenti, registra i voti degli esami
- Studente:
    -può iscriversi agli esami


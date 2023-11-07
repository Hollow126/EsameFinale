# Documentazione esame finale 
## Creazione Cartella GitHub 
il primo step del progetto è stato creare la cartella sul sito di *GitHub* , cartella chiamata EsameFinale, dopodiche 
da Visual Studio siamo entrati nella cartella del desktop dove risiedono i nostri file, denominata esameFinale chiamata esameFinale
e aprendo il terminale abbiamo eseguito in serie questi comandi 

```
git init
git add --all
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Hollow126/EsameFinale.git
git push -u origin main
```
grazie a questi comandi, abbiamo iniziallizato una cartella git locale, creato un file Readme,createa una nostra prima commit, rinominato il branch da master a main, collegata la repository locale a quella remota, ed infine caricato tutto online

## Script Sql 
Utilizzando l'estensione sqlite3, abbiamo caricato 2 query, la prima per creare le tabelle dandogli il nome della tabella ed i nomi dei campi della tabella  

```
CREATE TABLE IF NOT EXISTS Studenti (
	first_name TEXT NOT NULL,
	last_name TEXT NOT NULL,
	email TEXT NOT NULL
);
```

dopodichè abbiamo inserito 10 dati di prova utilizzando questa sequenza di query qui 

```
INSERT INTO Studenti (first_name,last_name,email) VALUES ('tiziano','gessa','tizigesgmail.com');
INSERT INTO Studenti (first_name,last_name,email) VALUES ('greta','difabio','aa.com');
INSERT INTO Studenti (first_name,last_name,email) VALUES ('simone','rizzo','aa.com');
INSERT INTO Studenti (first_name,last_name,email) VALUES ('greta','difabio','aa.com');
INSERT INTO Studenti (first_name,last_name,email) VALUES ('greta','difabio','aa.com');
INSERT INTO Studenti (first_name,last_name,email) VALUES ('greta','difabio','aa.com');
INSERT INTO Studenti (first_name,last_name,email) VALUES ('greta','difabio','aa.com');
INSERT INTO Studenti (first_name,last_name,email) VALUES ('greta','difabio','aa.com');
INSERT INTO Studenti (first_name,last_name,email) VALUES ('greta','difabio','aa.com');
INSERT INTO Studenti (first_name,last_name,email) VALUES ('greta','difabio','aa.com');
```
## Caricamento OnliNe
infine utilizzando 
```
git add --all 
git commit -m "esercizio completo"
git push origin main 
```
carichiamo i file modificati nella repository online 
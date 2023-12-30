# Proiect-final-27.01.2024

| Data  | Descriere  | Autor | Comentarii | 
|---|---|---|---|
| 10.11.2023 | Plan testare pentru versiunea 1.0 | Ioana Gornateanu |   |
| 20.11.2023 | Plan testare pentru versiunea 1.1 | Ioana Gornateanu | Adaugare detalii pentru implementarea testelor  |
| 10.12.2023 | Plan testare pentru versiunea 1.2 | Ioana Gornateanu | Corectare detalii pentru implementarea testelor  |

1. Introducere
     
      1.1 Scopul proiectului
     
      1.2 Functionalitati in scop
     
      1.3 Functionalitati si teste in afara scopului
   
2. Procesul de testare
      
      2.1 Planul de testare
     
      2.2 Analiza 
     
      2.3 Design 
     
      2.4 Implementare 

      2.5 Executie teste
   
      2.6 Inchidere

      2.7 Monitorizare si control

3. Livrabile

      3.1 Plan de testare

      3.2 Conditii de testare

      3.3 Cazuri de testare

      3.4 Raport zilnic

      3.5 Matrice de trasabilitate

      3.6 Rezultate teste

      3.7 Raport bug

      3.8 Raport de finalizare a testului

      # 1. Introducere
      
OpenCart este o platforma online care poate fi accesata in mod gratuit pentru comert electronic.
Opencart  oferă o bază profesională și de încredere cu ajutorul careia putem sa accesam cu succes un magazin online.

Aceasta platforma atrage o mare varietate de utilizatori: de la dezvoltatori experimentați care caută o interfață ușor de utilizat, până la proprietarii de magazine care tocmai își lansează afacerea online pentru prima dată.

OpenCart are o cantitate mare de caracteristici care vă oferă o baza puternică asupra personalizării magazinului dvs.

Cu instrumentele OpenCart, vă puteți ajuta magazinul online să-și ridice potențialul maxim.

Cele 2 story-uri de mai jos au fost create în JIRA și contin un rezumat al cazurilor de testare și al modificărilor care trebuie implementate, pentru care se realizează proiectul final.

STORY 1
![Daily report!](https://github.com/ioanagornateanu/Proiect-final-27.01.2024/blob/main/Story%201.png)

STORY 2
![Daily report!](https://github.com/ioanagornateanu/Proiect-final-27.01.2024/blob/main/Story2.png)

  ## 1.1 Scopul proiectului

  Scopul proiectului final pentru cursul de testare manuala si testare automata in cadrul IT FACTORY este sa folosesc toate cunostintele si informatiile acumulate la curs si sa le aplic in practica folosind site-ul https://demo.opencart.com. 

  Adresa site testat: https://demo.opencart.com/

 Adresa documentatia aplicatiei: https://docs.opencart.com/

  ### 1.2 Functionalitati in scop:

 Parti folosite in procesul de testare: 

-	 Parti folosite in procesul de testare: folosirea butonului "Filter" ca si scurtatura pentru cautarea produselor din site, schimbarea datelor produselor de pe site;
  
-	Tipuri de testare: Graphical User Interface.

### 1.3 Functionalitati si teste in afara scopului

-	Parti folosite inafara scopului : Testare automata
-	Testare non-functionala.
  
  
     # 2. Procesul de testare

  ### 2.1 Planul de testare

#### Roluri si responsabilitati

| Rol | Nume | Responsabilitate |
|---|---|---|
| Senior Tester | Ioana Gornateanu | va testa: use "Filter" as a shortcut to search, change specification for Manufacturers |
| Tester | Popescu Marian | will test:  change specification for products|

#### Criterii de intrare:

-	cerintele de business sunt definite
-	rolurile necesare pentru proiect sunt alocate.
  
#### Criterii de iesire:

-	toate testele au fost executate
-	65.4% dintre teste au fost rulate cu succes
-	Nu avem situatii cu un risc ridicat. Toate defectele gasite au un risc si o severitate scazuta.

  
#### Riscuri:
Riscuri de proiect:
-    termen scurt pentru procesul Zephyr Squad;
-   indisponibilitatea meniului de testare;

Riscuri de produs:
-	datele utilizatorilor (produsele) ar putea fi afectate de testele de actualizare
-	Browserul folosit Chrome poate avea probleme de performanță
-	Versiunea browserului Chrome poate avea probleme de vulnerabilitate in siguranta utilizarii 
-	organizarea paginii web ar putea fi afectată atunci când este deschisă pe dispozitive mobile
-	noul browser posibil sa nu fie suportat
-	riscuri de stabilitate (crashuri, deconectări etc.)

  ### 2.2 Analiza
  
-	Procesul de testare se va face pe baza cerințelor de business: folosirea butonului „Filtru” ca scurtătură pentru căutare, modificarea specificațiile pentru Producători, modificarea specificațiile pentru produse;
  
  ### 2.3 Design
  
-	Toate cazurile de testare sunt scrise și revizuite
-	Cazurile de testare funcționale vor fi create în Zephyr Squad folosind Jira ca instrument de gestionare a testelor
-	Cazurile de testare GUI vor fi create în Zephyr Squad folosind Jira ca instrument de gestionare a testelor


  ### 2.4 Implementare
  
-	toate datele de testare sunt disponibile și revizuite (date de test= exemple de e-mail, exemple de parole)
-	A fost creat Cycle summary  și cazurile de testare au fost adăugate la Cycle summary  
-	Mediul de testare este activ și rulează: https://demo.opencart.com/
-	Accesul la mediul de testare este dat:  Username : demo | Password : demo


  ### 2.5 Executie teste
  
-	Testele vor fi executate pe primele 4 browsere utilizate: Chrome, Mozilla Firefox, Microsoft Edge, Apple Safari
-	Cazurile de testare vor fi executate pe baza Cycle Summary creat
-	Erorile (bugs) vor fi raportate pe baza testelor eșuate


  ### 2.6 Inchidere
  
-	Aproape 65.4% dintre teste au fost realizate cu succes
-	Nicio situaite critica nu are status de "Open"
-	Testele exploratorii au fost realizate


  ### 2.7 Monitorizare si control
  
-	Rapoarte periodice (zilnica/saptamanale) vor fi generate pentru a reflecta starea curentă a procesului de testare. 

     # 3. Livrabile
 	
  ### 3.1 Plan de testare

-	Planul de testare este conceput pentru a descrie toate detaliile testării pentru următoarele caracteristici:  folosirea butonului „Filtru” ca scurtătură pentru căutare, modificarea specificațiile pentru Producători, modificarea specificațiile pentru produse;
-	Planul identifică elementele și caracteristicile care trebuie testate, tipul de testare care trebuie efectuată, rolurile și responsabilitățile pentru procesul de testare, riscurile asociate cu planul, resursele și programul necesar pentru finalizarea testării.

  ### 3.2 Conditii de testare 

- Următoarele condiții de testare pot fi găsite aici: [test conditions](https://github.com/ioanagornateanu/Opencart-project/blob/main/Test%20condition.pdf)
  
### 3.3 Cazuri de testare
  
- Cazurile de testare cu pași pot fi găsite aici: [test cases](https://github.com/ioanagornateanu/Opencart-project/blob/main/Test%20case%20with%20steps.pdf)

### 3.4 Raport saptamanal
  
- The following status report was generated after all of the test cases were executed, on 7th of October 2023 [Summary test execution](https://github.com/ioanagornateanu/Opencart-project/blob/main/test%20Summary%20executed.png)
- link to daily test summary report (number of tests ran today, % of them failed, passed, re-test, etc) [Daily test execution](https://github.com/ioanagornateanu/Opencart-project/blob/main/Daily%20Test%20Execution.png), [Weekly Report](https://github.com/ioanagornateanu/Opencart-project/blob/main/Weekly%20Report.png), [Test execution by test cycle](https://github.com/ioanagornateanu/Opencart-project/blob/main/Test%20execution%20by%20Test%20Cycle.png), [Test execution by Tester](https://github.com/ioanagornateanu/Opencart-project/blob/main/Test%20execution%20by%20Tester.png) .

 ### 3.5 Matrice de trasabilitate
 
 - Link catre matrice de trasabilitare [Traceability Matrix](https://github.com/ioanagornateanu/Opencart-project/blob/main/Forward%20Traceability%20Matrix.png) .

  ### 3.6 Rezultate cazuri testare

- Rezultatele cazurilor de testare pot fi găsite aici: [Test case results](https://github.com/ioanagornateanu/Opencart-project/blob/main/Test%20case%20result.pdf)

   ### 3.7 Raport bug

  - Erorile (bugs) raportate pot fi găsite aici: [Bugs](https://github.com/ioanagornateanu/Opencart-project/blob/main/Bugs.pdf) 

   ### 3.8 Raport de finalizare a testului

  - link către raportul de finalizare a testului (cazurile de testare au rulat, câte TC au fost trecute și câte au eșuat):
  
    ![Daily report!](https://github.com/ioanagornateanu/Opencart-project/blob/main/Raport%20executie%20GUI%20TESTING.png)

    ![Daily report!](https://github.com/ioanagornateanu/Opencart-project/blob/main/Raport%20executie%20AD-HOC.png)
  - A fost generată diagrama de execuție a testelor, raportul final arată că un număr de 9 teste au eșuat din total 26 pentru TESTARE GUI.
  - Au fost planificate pentru execuție un număr de 27 de cazuri de testare și toate au fost executate.
  - S-au găsit un număr de 9 bug-uri în total, dintre care prioritatea este: medie.
    
 ### 3.9 Program

 - Pentru fixarea erorilor testarea s-a facut intr-un interval de 30 zile
 - avem 27 teste
 - pentru a termina rularea de regresie ar trebui să rulăm un numar de 3 teste/zi




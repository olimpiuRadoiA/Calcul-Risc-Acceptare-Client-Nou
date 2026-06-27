1. Scopul aplicatiei

Aplicatia raspunde la intrebarea:

„Cat de riscant este potentialul client pentru o misiune de audit intern?”

Rezultatul final poate fi:

Scor	Nivel risc	Recomandare
0–30	Risc redus	Client acceptabil
31–60	Risc mediu	Acceptare cu atentie / verificari suplimentare
61–80	Risc ridicat	Acceptare doar cu conditii clare
81–100	Risc critic	Recomandare de neacceptare sau aprobare speciala

2. Criterii de risc

Am folosit 6 zone:

Risc financiar
  pierderi recurente
  datorii mari
  cash-flow slab
  capitaluri proprii negative
Risc operational
  procese neformalizate
  lipsa procedurilor interne
  dependenta de persoane-cheie
  volum mare de tranzactii
Risc de conformitate
  controale ANAF / ASF / alte autoritati
  amenzi recente
  declaratii depuse cu intarziere
  litigii
Risc de guvernanta
  lipsa organigramei
  decizii fara documentare
  conflict de interese
  conducere instabila
Risc IT / date
  lipsa backup
  acces necontrolat in aplicatii
  lipsa jurnalelor de modificare
  fisiere Excel folosite excesiv
Risc reputational
  presa negativa
  actionari / administratori cu istoric problematic
  domeniu sensibil
  relatii comerciale neclare
  
3. Logica simpla de calcul

Pentru fiecare zona, utilizatorul alege un scor:

Scor:
1	risc foarte mic
2	risc mic
3	risc moderat
4	risc ridicat
5	risc foarte ridicat

Apoi aplicatia aplica ponderi:

Zona	Pondere
  Financiar	20%
  Operational	20%
  Conformitate	20%
  Guvernanta	15%
  IT / Date	15%
  Reputational	10%

Formula:

Scor final = suma(scor zona x pondere) x 20

Rezultatul va fi intre 0 si 100.

4. Interfata aplicatiei

Aplicatia iti va cere sa completezi:

date client: denumire, domeniu, cifra de afaceri, nr. angajati;
selectie scor pentru fiecare zona de risc;
camp de observatii;
buton Calculeaza risc;
rezultat final cu:
  scor numeric;
  nivel de risc;
  recomandare;
  sumar pe zone.

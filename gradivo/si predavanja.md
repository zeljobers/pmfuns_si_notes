# si predavanja - kljucne reci "!!!", "test", "?", BITNO, PUNCHLINE, HIGHLIGHT, `**`
# ne napamet, ali nabrajaj - 
# https://www2.informatik.hu-berlin.de/swt/intkoop/jcse/
# 4. nedelja - zvrkanje
- nisam slusao prve minute...
## Procena troskova
## Analogije metod
- propustio sam da snimim, nakon prve pauze. tacke metoda sta je rekao pojasnjenje.
## Predstavljanje funkcijskih bodova
- 10:10 - ako je spec. zahteva losa i procena troskova ce biti losa.
### Principi
## Slozenost zahteva
### Proizvodne funkcije
- input data
- output data
- query data
### Product data
- data
- reference data
## Klasifikacije ulaznih podataka
## Kategorizacija preliminary requierments-a
- Zasto IBM-u potrebno 65bodova za 650h, a VW mnogo vise?
## Pauza 11:10-11:23
## TEMA 7 - nije bila, ali sada jeste u nastavi
## Proizvodni modela pravi tekstualne spec. vise preciznijim
## Modeli.
- 11:33AM Najavljeno trik pitanje
- Modeli u elekronskom inzinjerstvu
- 11:38AM - Trik pitanje, original ili model sta je starije? - Zavisi.
- Konekcija modela i pogleda
- 11:44AM - HIGHLIGHT !!! dva nacina za produktno i objektno-orijentisana техника za izradu produktnog modela
  - постоји и аспектно-орј., али њу изостављамо.
- 11:50AM - BITNO !!! 
  - plemenita ideja 
  - nacin da se silazi niz dijagram 
    - konacnim automatima
    - umlom
---
# 4. nedelja - obnavljanje
## Procena troskova - tema 6
- a) Procena troskova i uticaj faktora na utvrdjivanje troskova
- b) Pristupi (Osnovne metode)
- c) Metodi funkcijskih poena
- d) Primeri primene metoda FP-a - radi se na vezbama
- Analiza i definicija u waterfall-u
  - U fazi planiranja
    - nakon odradjenog recnika i preliminarnih specifikacija zahteva, ide procena troskova
### Zasto?
- BITNO! organizacija datuma i osoblja
  - **broj osoblja**
  - **duzina angazovanja osoblja**
- ugovori sa fiksnim cenama
### Kako?
-  ulaz (na osnovu cega)
-  izlaz (ocekivanja)
### Jedinice mere
- 3 MJa:
  - MM - covek meseci
    - MY - covek godina
  - LOC - line of code
  - Function Points - 3 karakteristicne mere kojima izrazavamo troskove projekta
- 10 MY = 12*10 MM = 5 2MY = 1 10MY = 1 day for 3650 employees - bitno: besmisleno je skracivanje vremena na ovaj nacin : trud oko medjusobne  komunikacije isto raste...
- Optimalno vreme za razvoj softvera
  - $2,5*(\text{empirijski effort MM})^S$ - Boehm 1981
    - S = 0,35 za online sisteme
    - S = 0,32 za sisteme u realnom vremenu
  - Na primer : za 9 MM i optimalnu duzinu $2,5*9^{0,35}$ = 5,3 meseci
  - Broj radnika $= 9 MM / 5,3 meseci = 1,7 (2)$
### uticaj faktora na utvrdjivanje troskova
- zavisnosti:
  1. LOC
  2. Kvalitet zahteva (visoka efikasnost, bezbednost)
  3. Kvalitet programera (produktivnost)
  4. Kompanijsko iskustvo sa slicnim zadacima
     - predznanje iz slicnih prethodnih iskustava
- Procena vremena
  - kada se troskovi ustanovljavaju
    1. sto pre
    2. tokom studija izvodljivosti za preliminarnu specifikaciju zahteva
    3. nakon potpisivanja ugovora za konacnu specifikaciju zahteva
## 4/6 pristupa za procenu troskova:
1. metod Analogije
2. metod Multiplikator
3. metod Tezine
4. metod %Procentrualni
5. ~~metod relacioni~~
6. ~~metod parametarski~~
- **BITNO! TEST! Za sve ove metode je zajednicko to da se zasnivaju na prethodnom iskustvu**
### 1. metod Analogije - najopstiji
- poredjenje razvoja da bi bio utvrdjen i vec zavrsena izrada proizvoda zasnovana na slicnim zahtevima.
- zahtevi isti/slicni :
    1. polje primene
    2. velicina proizvoda
    3. stepen slozenosti
    4. progLang
- 27:30 - primer: na osnovu prethodnog proizvoda imamo MM i % koliko je razlicito i racunamo za ovaj koliko
  - obratiti paznju na pridodat koeficijent kompleksnosti
### 2. metod Multiplikator
- 3 koraka: 
  - Particionisanje sistem u podsisteme
  - Utvrdjivanje troskova za podsisteme
  - Dodeljivanje tezinskih faktora slozenosti
- Na osnovu karakteristika (LOC) prethodnog softvera sa kojim smo imali iskustva izracunavamo procenu
- desno jedno mnozenje na osnovu prethodnog iskustva i levo mnozenje dodavanja
### 3. metod Tezine
- odredjivanje faktora za utvrdjivanje
  - ponovna korisnost potrebnih atributa, algoritama su blaze slozeni
- Racunanje sa izracunljivom formulom
- metod Funkcijskih poena
### 4. metod %Procentrualni
- sa kojim nasim prethodnim iskustvom
- na osnovu kog sada radimo procenu troskova
- 34:00 - na osnovu  3 verzije iskustava:
    1. polje primene
    2. na osnovu tehnickih uslova nasih iskustava
    3. koliko smo dugo proveli u razlicitim fazama softvera
- Besplatna izrada procene troskova, ali i citava analiza i definicija - primer IBM i nemacka izdavacka kuca
## Korist metoda utvrdjivanja troskova 
- 37:30 - tabela
  ---
## Funkcijskih bodova metodi 2. deo
### Istorija - Alen Albreht IBM
- moguce merne jedinice
  - funkc. spec.
  - velicina softverskog projekta
    - LOC (velicina implementacije) - **lose** na osnovu ovoga vrsiti procenu troskova prerano
    - Funkcijski poeni (velicina zahteva) 
      - Zahtevi su kolicinski usaglaseni sa FP, 
      - Koji troskovi su potrebni da se ispune zahtevi?
- LOC - ProgLang 16 funkcijskih bodova
### Karakteristike metoda FP-a
1. odnosno precizni
2. subjektivno
3. iskustvo potrebno za metodicnu primenu
4. industrijski standardi u metodi proceni troskova
5. preduslov: komercijalne primene, ali ne i sistemske programe
- Prednosti :
  1. Odmah primenljiv - zasnovan na zahtevu proizvoda
  2. Bilo kad primenljiv - iterativan
  3. Sto ranje primenljiv
  4. Lako ucljiv
  5. Dobra procena
  6. Alat podrske dostupan
- Mane :
  - Rade samo za komercijalu
  - 14:30 - BITNO! TEMA 2 - Tezi da obesmisljava, ponizava (nekompletnost zahteva onda je i procena losa)
### Principi FP
- 5 kategorija **funkcija podataka!**
- 3 slozenosti
- Procena troskova - beztezinski - sirovi bodovi
- Faktori uticanja -> prepravljena procena troskova - tezinski FP
  - ovo utice na ↕30%
- tabela
- MM
- azuriranje tabele i MM-a
## 24:00 - Kategorije zahteva proizvoda
- unos u ovaj proces je funkcionalnost za zahtev i izlaz je podatak

## Klasifikacija i kategorizacija
- Instinktivno se vrsi klasifikacija
- formal(syntax, matematicki), logic(semanthic), DB access
- 38:20 - ILEGALNA SPECIFIKACIJA ZAHTEVA ponudjena
- 43:50 - odvaljivanje je srednje kompleksnosti
---
## Tema 7 3. video - Modeliranje i proizvodni modeli 
- Plan projekta - mozda na kraju ili ne uopste prelazimo
- U definicionom modelu 
  - nakon konacne specifikacije(koja moze biti dvosmisleno) ide izrada proizvodnih modela
    - formal, matematicari
    - formalizacija - karakteristike
### Modeli 
- Model <-- (Apstrakcija) -- original
  - Idealizovan - lakse za izradu prezentacije za razne primene uz apstrakciju
  - Znacajna primena; izbegava redudantne primene
  - Odrziv u poredjenju na originalan oblik
- Primer : 
  - elektronsko inzinjerstvo, sema elektricnog kola
  - arhitektura, maketa - tehnicko crtanje
- Dalja korist od modela:
  - mogu biti opis sistema
  - korisceni za UML (koji se koristi za implementaciju direktno)
  - BITNO! Sta je starije model ili original? 
    - 15:00 BITNO! TEST! Zavisi od potrebe, u ovom primeru original nastaje posle modela (waterfall-a, elektro kolo pcb `->` izrada), ali ima i drugacije od ovoga (kada opisajemo nesto postojece)
- 16:30 - Slicnost pogleda i modela - u zavisnosti sta nas zanima(funkcionalnost,...) moramo da menjamo tacku gledista - naocari
- 18:00 - ne postoji samo jedan model, vec kombinacija vise modela
- 21:00 - BITNO! Softverski sistem --(apstrakcija)--> Product model 
  - Softverski sistem <--(**inzinjerstvo unapred**)-- Product model 
  - Softverski sistem --(**Reverzno inzinjerstvo**)--> Product model 
### BITNO! 2 nacina za izradu modela
- Strukturirana analiza
- Objektno-orjentisana analiza (u istom momentu)
#### 24:00 - seme kako dalje i izrada pri implementaciji SW-development-a
- kako vec ime kaze:
  - Strukturirana - proceduralno
  - OOA - OOP
### Model zasnovano RS
- Model-Driven RS/Arch/Software
- 28:00 - MDSD idealni principi (slucaj rev. inzinjer.)
  - profinjavanje slojeva proizvodnih modela sve do realizacije softverskog sistema 
    - svrha automatsko generisanje koda
---
# 5. nedelja - zvrkanje+obnavljanje
## Funkcionalni pogledi
  - Funkcijska hijerarhija - drvo
  - Usecase-dijagram - biznis proces
  - djagram toka podataka - informacijski tok
- Zelimo da preciziramo nas model.
- primer:
  - specifikacija zahteva - linearna lista proizvodnih funkcija
  - funkcijsko drvo - proizvodne funkcije organizovane hijerarhijski
### 5:40 - strukturna analiza SA
- funkcijsko drvo, je implicitno umetnuto u SA
- dijagram toka podataka - glavni za odredjivanje SA
- ostali pomocni alati
### 8:00 - Osnovni koncepti i RS faze
- povezanosti izmedju faza i pojava alata koji se u njima koriste
- 8:20 - klasifikacija po notaciji
### 3 koncepta za Orijentiski funkcionalan pogled
- Function trees
- dijagram toka podataka
- Usecase
### Function trees
- Zadaci softvera, proizvodna funkcija (spec zahteva) - Analysis&Def faza
- Funkcija, procedura, metod - Dizajn i implementacija faza
- funkcijsko drvo = funckijska hijerarhija : funckija `->` potfunkcija `->` ...
- 11:00 - BITNO ! - Graficka reprezentacija
  ````
  A -> B
    -> C
  A,B,C - funkcijska imena
  ````
  - osnova hijerarhije:
    - definicijska faza : 
      - A se sadrzi od B i C
      - FT = Hijerarhija zadataka
    - faza dizajna:
      - A zove B i C
      - FT = Hijerarhija poziva
    - oprez: Hijerarhija zadataka ne mora nuzno da sledi hijerarhiju poziva!
      - ako smo zadatke podelili u podzadatke to ne mora da znaci da cemo u funkcije, metode ili procedure umetnuti isto resenje
- 14:00 - primer: seminar organizacija funkcijsko drvo
- Procena sta mislimo o funcijskom drvetu
  - dosledan koncept sistematicnog razvijanja i dekompozicije funkcija - linerarno listanje - hijerarhijski poredak
### dijagram toka podataka DFD - primaran proces u SA od svih
- 4 koncepta:
  - protok,
  - funkcija
  - skladiste
  - Spoljasnja pojava (Interface)
    - okruzenje gde podaci izlaze i/ili ulaze 
- Ideje:
  - sistem radi prilikom razvijanja
  - informacijski tokovi radno sistema su reprezentabilni (opisljivi)
  - opisnost putanje podataka izmedju
    - funkcija
    - skladista
    - Spoljasnjih pojava
- 24:00 - Primer : organizacija seminara sa DFD-om
#### 25:50 - Syntactic(syntax) pravila DFDa
- formalizacija, ali ne formalna, notacija
- svaki dfd ima bar 1 Spoljasnju pojavu (interface)
- svaka spoljasnja pojava se sadrzi u dfd-u
  - ako je nejasan DFD, onda se ponavlja njeno umetanje
- Svaki tok podataka
- 28:00 - nedozvoljene radnje:
  - direktna veza izmedju dve spoljasnje pojave
  - direktna veza izmedju dva skladista
  - direktna veza izmedju spoljasnje pojave i skladista
- funkcije su uvek izmedju
- opis unutar DFD-a za funkcije proizvodnje
#### Semantic pravila DFDa
1. BITNO! 30:00 - za interface naznacujemo odakle i od koga **originalno** dolaze ili odakle i kome cemo ih pruzati kome pruzati, bez obzira na posrednika (npr. menadzera) 
2. za izbor interfejsa sledi apstrakcija za konkretan ulaz(npr. tastatura), izlaz(npr. stampac)  
3. imenovanje toka podataka, za strelicu - (sa pridevom) imenica 
4. izbegavanje topoloskih imena: 'data', 'information',...
5. imenovanje funkcija - glagol imperativ uz pravi objekat ili imenica uz glagol imperativa
6. izbegavanje topoloskih imena: 'manage', 'process',...
#### Prednosti DFDa
- lak za podesavanje i citljiv
- dobra notacija za dijalog izmedju diskutora
- Vise informacija od funkcijskog drveta
- MANA: vremenom moze postati glomazne, necitljive forme za citav sistem
  - solucija : strukturna analiza po novoima hijerarhija
#### 35:00 - Pregled DFD-a - rezime
- moj zakljucak: FT je povrsinski, na siroko, posvecena funkcionalnostima, dok za DFD je to obrnuto
### Usecase (Biznis proces dijagram)
- Notacioni elementi: akteri, sistem, funkcionalnosti, odnosi
- levo klijenti
  - desno su uposlenici u nasoj firmi
- uloga usecasea u UML-u
  - fundamentalna podfunkcija, usluga sistema
  - sa vrednoscu, vaznosti za korisnika
  - realizacija izvrsena nakon niza interakcija korisnika i sistema
  - opisuje funkcijske zahteve
  - funkcionalni opis sistema = skup svih use case-ova
#### Tehnike opisa Usecasova
- **textom**, saradnje dijagram, dijagrami veze, aktivnosti, konacni automati, petri nets
- tekstualni primer header... predjen ranije
- Use case UML
  - `<--extend--` - klijent trazi informaciju
  - `--include-->` - klijent unosi
  - generalize - puna strelica - vazi za aktere i funkcionalnosti!
- use case vs uobicajena proizvodjacka funkcija
  - specijalna u smislu fundamentalna
  - korisnik je njih svestan zato sto su fundamentalne
- primer
  - levo : izdvajanje male funkcije koje se ticu ovih povrsinskih sto su desno
    - desno : izdvajanje konkretnih funkcija
    - povezivanje
- elementarna funkcija (obratno od neke slicnosti bijekcije)
  - nije ~1-1 funkcija
  - moze samo da ima vrednost ako je unutar use-casea
- nije mu servis kako sortira nesto, vec kako izracunava platu
#### 56:00 - Prirucnik za pozeljnu velicinu usecasova
- primer XCTL (rentgen) usecase dijagram
#### Prednosti:
- koncentracija je na centralnom radnom toku, a ne na elementrarnim funkcijama
- koncentracija na standardni radni tok
- lako razumljiv i za musteriju
- MANA: opasnost odlazenja u detalje 
- DOMACI razlika izmedju interfejsa i aktera
- Unified RS Process USDP, UML - Use-case driven
  - nisu samo alatka za opis zahteva, vec i za pomocno sredstvo za implementaciju i test koje usmerava ceo RS
  - BITNO! Zasto povezanost OOA sa ovim? zasto je ovo OOA koncept?
    - nije!
---
# 5. nedelja - 2. deo
## Orjentisani pogledi na podatke
- Data dict - data structures (BITNO! u svim slojevima: definition, design, impl.)
- ER model - Entity types and relations (samo unutar definition)
## formalni su oba, ER graficki, DD je tekstualni
## Data dictionary
- sintaksna struktura podataka sa korisnickog stanovista
  - kako ide regex, batou!
  - nema impl. data struktura : arrays, fields, trees
- Opis:
  - EBNF - extended Backus Naur forme,
  - constraint - nema rekurzija?  
- Korist: preciziranje informacija sadrzane u dijagramima toka podataka ili dijagrama klasa
- kasnije koristimo DD
- 7:30 - primer: Seminar organizacija (interface)
- 10:00 - primer : BNF
  - javlja se potreba prosirenja BNF
- Domaci: Kako bi prosirili ime prezime?
- Prednost : razvijanje i preciziranje struktura podataka je formalno i kompaktno opisano, kao sintaksa u modernim PLang (EBNFom)
- Pocev od toga da je DD nije graficki javlja se necitkost
  - delimicna solucija: dijagrami sintakse
- John Warner Backus - Fortran
## ER
- DB teorija
  - elementi klasnih dijagrama uzeti iz ER dijagrama
- kao sto je za DD sintaksnog opisa, dok ovde je cilj da opise trajno skladistene podatke i njihove povezanosti
- Entitet primer
- Skup entiteta = entiteti sa istim osobinama
- Kljuc - identitet entiteta
- Poveznici
- kardinalnosti
  - njima ne opisujemo realan zivot, prilagodjavamo nase potrebe
- matematicka paralela sa terminima
- primer : agregacija - deo necega (0,1)
- primer : uloge poveznika
- 47:00 - BITNO! notacioni element: generalizacija IS_A
  - imali smo usecase-ovima generalizacija, 
  - generalizacija nije specijalnost nasledjivanja
  - BITNO! generalizacija = realizacija poznatog koncepta
  - primer : er na robotu'
    - Slucaj rekurzije
- poredjenje ER i DD
  - syntax DD namena za bilo koje podatke (unutrasnji, spoljasnji)
  - er je za spoljasnje podatke
    - osnovni podaci, relacije
    - jaci DD (ima relacije)
### Ugao gledanja za waterfall izradu DB modela
- AiD - ER
- Design - Relational data model (logical schema)
- Impl. - DDL
- Test
- Odrzavanje - DML
---
# 5. nedelja - 3. deo
## Tema 10 - Osnovni koncepti pogleda orjentisanog na **pravila**
- 3 pristupa:
  - tabela odluka (textualni formalan)
  - pravila (textualni)
  - drvo odluga (graficki)
- cilj: uslovno zavisne akcije - tokovi komandi, funkcija, zadataka
- faza: AiD:
  - preciziranje syntax i semantic verbal desc. u specifikacijama zahteva
- primer : zahtev "isplata cekova"
  - regularno u dozvoljenom minusu, anexi na zadate, neisplaceno na neregularno, regularna isplata
  - pitanje : sta je problem?
    - uslov 3 i 4 vode ka kontradikciji
## Pravila
- implikacije
- cista sintaksa i semantika za preciziranje zahtevima specifikacija
- podesavanje pravila, odvajanje elementarnih uslova, akcija iz verbalnih recenica
- primeri sa if-then
- kombinacije itd...
- 13:50 - rezime
- 14:30 - upoptunjavanje uslova
- MANE: Problemi sa pravilima : citkost, potpunost...
## 16:00 - Tabele odlucivanja - primer
- 22:30 - Dusica videla nelogicnost
- 3 domaci na forumu
- 4 domaci
- DecisionTable rezime
  - Domaci : kako se prirodno izrazavaju petlje u implementaciji?
    - dt1.2 ako je ovo ispunjeno opet idemo na istu tu tabelu, ako su isti uslovi uspunjeni vracamo se na istu tabelu, a onda ako su jos neki uslovi ispunjeni onda teramo dalje!...
- 30:00 - primer: citanje iz funkcionalnosti i ispitujemo uslove i elementarnih uslova(zeleno, ali su izostavljeni)
  - odatle izvodimo akcije A1-A5 (normalne aktivnosti) 
    - elementarne uslove
  - 35:00 - centralni DT - profinjenje DTova
  - 38:00 - rukovanja sa normalnim slucajevima DT
  - 45:00 - pitanje: kako bre more da nismo se pitali da li smo uknjizili majmuna? 
    - odg: tek smo ga uneli nemoguce je da je u zaostatku sa placanjem.
## Drvo odlucivanja
- kao tabela samo smo rotirali za 90dgr nalevo
---
# 6. predavanja - zvrkanje
- Detaljnije u product model
  - strukturna analiza
  - objektno-orjentisana analiza
- Strukturni metodi
  - strukturna analiza
  - strukturni dizajn
  - primena na citav sistem
  - funkc. ojentisano - 3 neke stvari...
      1. nezavisnost jedinica
      2. protok promenljivih ponasanja
      3. Cetralizacija nad dijagramom toka odataka
    - sve ovo ubaceno u proceduralni programski jezici 
- ObjOr Metode
    - objekat(ili apstraktni tipovi), 
    - centralizacija nad klasama
  - sve u OOP
- strukturna analiza - zakljucivanje **zastarelosti** metoda i njihov relevantnost danas
  - tom neki lik, albanija, knjgu nudi neku
- varijante i istorija SA
  - 4 bitne knjige - SA,sysSA, esencijalneSysA, modernSA
- CIlj - **formalizovani oblik modela**
- kombinacija osnovnih koncepata SA
  - 15:21 - funkcijsko drvo neisprekidanom linijom, jer je implicitno sadrzano
- 14:55 - potrebne alatke od prethodnog
  - modern ukljucuje i ER posle...
- ideja : 
  - trazi se hijerarhijska struktura => strukturiran product model => strukturiran opis zadataka
  - promenljivo ponasanje => ili za ceo sistem ili za podsisteme
- DFDovi(glavni za hijerarhije) i DD-ovi
  - dvosmislen razlog
    1. limit zbog previse funkcionalnosti unutar DFD-a, gomila strelica i krugova, pa se razvrstava hijerarhijski
    2. metodoloski - vodi nas ka top-down resavanju prema specificnijim funkcijama
       - **MiniSpec** (DecTab, DecTr, Rules, PseudoCode)
       - DD - opisuje skladista i data flowove u DFDu
- primer : DFD-a
- Sta je karakteristike DFDa...
- kontekst dijagram...
  - Syntaxna pravila : case study 
    - jedna jedina funkcija, proces numerisan 0 i njome opisan ceo sistem 
    - i oko nje interfejsi - akteri, eksterni entiteti
    - crtice - sta se desava izmedju
    - nema data storages
  - promenljiva ponasanja: Crna kutija, cist IO, promena sadrzaja interfejsa 
- profinjavanje... - otvaramo proces 0
  - ovde se uvodimo data storage! i ne mogu se vise profinjavati
  - javlja se da se vracamo generalizacija - profinjavanje zarad zakljucivanja medjusobnih komunikacija
  - vise funkcija
    - BITNO: nema profinjavanja interface-a, moze zarad boljeg razumevanja samo moze njihovo ponavljanje
  - otvaramo funkciju,opet...
  - ne mogu se interfejsi profinjavati
  - broj procesa max 7 , profinjavanja max 4
  - DFD mora da bude balansirano!
  - numeracija po nivoima i po poprecnosti
- 29:00 rezime
- razna profinjenja po nivoima se zavrsavanjem se zatvaraju uz povratne rezultate
- 34:00 - mogućnoost profinjenja
- neki od 9 celina
  - Mini-Specifikacije
    - mora imati opis za ulazne i izlazne
    - nema "KAKO?" samo STA? u opisu funkcije
    - sadrzaj DecTab, DecTree,Pseudo,Rules
    - opis pseudokoda primer!
  - implicitno funkcijsko drvo pregled ishoda odozgo
    - samo opisi funkcija hijerarhijski poredjano
  - DD
    - opisi sintaksu podataka i strelica (dataflowova) do podataka
    - DD entries (unosi) opisi sintaksa
      - od cega se sastoje dataflowovima, tabelama - detaljisanje
      - visi nivo apstrakcija opisujemo nizim nivoom apstrakcija
        - primeri profinjavanja protoka ulaza i izlaza
        - (ime dflowa) - oznacava da je strani protok ulaz/izlaz
- EVALUACIJA SA
  - hijerahijski
  - lakse ucljiv
  - kompaktna kombinacija koncepata
  - topdown
  - storage i interfejs(zbog pravljenja problema sa visestrukim brojem interfejsa) **nema profinjavanje**
  - pretvaranje SA modela u pogodan strucDesign konceptima, koji se ostavljaju u stranu i pravi se nov u sledecoj fazi
## 6. predavanja - 2. deo - tema 12
- Stanje-orjentisani pogledi
- naocare, konacni automat i konkurencija 
- mapa alata graficki, tekstualni, formalni ili formalizovan
- Konacni automati
  - cilj... ponasanje
  - mogu se koristiti za 3 stvari
    -  opis definicija tokom izvrsavanja 
    - usecaseova interakcijom korsnik/sistem i promena stanja
    - dinamican pogled objekata
  - 2 matematicka modela
  - primer: Alarm
  - pocetna, kranja stanja, tranzicija
  - primer Alarma: pitanje: Sta je krajnje stanje? Koja streliza nas vodi ka tome? - sve
  - 29:00 - Tabela stanja 
  - Mealy i Moore automat
    - DOMACI: Kako se prebacuje izmedju ova dva automata? 
      - ocekuje graficko resenje https://www.tutorialspoint.com/automata_theory/moore_and_mealy_machines.htm
- 33:00 - grananje DKA sa izlazom
  - Harel zajedno sa Mealy i Moore
    - to je njihova kombinacija
- Automati stanja u OO svetu 5 karakteristika:
  - isti automat stanja imaju svi objekti
  - dinamicno
- zivotni ciklus objekta 
  - 43:00 - primer za seminar
  - 54:00 - vrisak
    - pitanje: dodavanje stanja
  - pitanje: menjanje neko potrebno?
  - dogadjaji
- 1:05:00 - dijagram aktivnosti
  - 1:11:00 - ... njegov razlog je kranji
  - primer na otkazivanja kursa
    - gledamo na sta da se oslonimo sto je slicno

# 7. tema 13.
- scenario based view
- Messages i scenario 
  - [Sender]->[Reciever]
  - sadrzane informacije senders, receiver, 4 messages
  - BITNO! scenario = sekvenca poredjanih poruka
- dijagram saradnje
  - placeholder of an arbitary object
  - constr, destr, transient, trigger
- VREMENSKI DIJAGRAM sekvencni
  - vec postojani objekti iznad
  - kolone paralela
  - red vreme
# bruh - tema 14

# 9. nedelja - zvrkanje - 
- OOA
- UML Rumbauch, Booch, Jacobson
- Graficki jezik - skup razlicitih dijagrama tipova za razlicite poglede na SW-sistemu
- UML mix of methods, syntax-based, but not semanthics
- UML = kombinacija 12 notacija
- 3 knjgie
- cilj OOA - nisam ispratio
- kombinacija
- Izvor ideja za OOA - uzeli su sve osnovne stvari (spoilovali):
  - oop
  > retroaktovno prave apstrakciju, 
  >  - nesto je ponavljao 3-4. put nesto
  - ER modeli!!!
  - konacni automati
  - vremenski dijagrami
    - dijagram sekvenci
  - biznis proces
    - use case
- nema posedovanja doprinosa
- OO paradigma - osnovna ideja
  - dekompozicija sw sistem u objekte, pa klase kao apstrakciju
  - OOA definicija - je metod analize koji odredjeni zahtevi iz perspetive klasa koji se nalaze u recniku domen problema
  - Case study: primenljiva delatnost sadrzi objekte
    - primer : meteoroloska stanica
- Sta je objekat:   - paket, kombinacija
  - data - stanje
  - operacija - menjanje stanjea
- objekti kombinacija ova gore dva
- objekat str. pod. i ponasaanje u pojavi
- kao getter getter - access to the private memory
- instanca...hehe nije nesto mnogo rekao A IMATE I VOZOVE TUTUT
- podmodeli u modelu
  - staticki [26.slajd] - izvorni kod - RECEPAT
  - dinamicki - modelira kada krene da se izvrsava
    - ali operacija moze da bude staticki model
      - moze da se vidi sta moze da se uradi
        - pre mu spada u dinamicki, ali bi metno u oba 
  - 27. slajd - use -case je vise staticki
  - ako gledamo ovo sve po fazama
  - 29. slajd - PROŽETO POJAŠNJENJE - jasno sa svim notacijama
  - primer statickog modela UML - organizacija seminara
    - a i DFD 
  - relacija izmedju 2 nacina produktnog modela za requierments specifikacija
    - malo odonud, malo odonud
  - [34] da li jedan ima vise informacija od drugih
  - staticki OOPA - prikaz notacija na primeru
  - [37] stanje da procitamo , doteramo, izvedemo proracun
- primecivanje operacija u zahtevu
  - 3 generalizacija (neki entitet, a ne glagolska imenica)
  - prica o planarni graf
  - asocijacija
  - kardinalnost
  - DOMACI: klijent participant 1:*, booking *:1. da li je moguce 1:1? - utorak 23:55
  - 2. domaci : *** da li je ok i zasto?
  - i <3 domaci
  - primena DD(opis atributa) i pseudocode-a(opis operacija/koda)
- paketi - poslednji metod OOA
  - paket viseg nivoa i nizeg
  - prica o kaplingu - izvan firme i unutar firme definise 
  - DUSAN NOVAKOVIC SLUSA UNAPRED. BUDI KAO DULE.
  - [53] hint
  - regulacija populacije ljudskih bica
- Dinamicki model
- usecase paketi model staticki
- dinamicki model fokus
  - povezanost svih alata iz notacija
- kraj 14.a)
- USDP OOA
- 6. slajd UML po fazama
- izvod svih modela OOA
- CITATI... WOW
  - [8]ON CITIRA SEBE AUTOBIOGRAFIJA: BITNO! do ovog trenutka moze predvidivo nacin moze da se ponovi iz preth. iskustva, nije recpet, algoritam
  - [9]poslovne procese spakujemo u pakete
  - gradi OOA stat i dyn model
  - profinjavanja
- ako je sistem jako veliki pakete mozemo praviti i od use-casova, ali inace je uz klase
  - 7 koraka:
  1. identifikacija - dijagram klasa
  2. identifikacija - ciste povezanosti
  3. potpuna identifikacija atributa
  4. identifikacija medjusobnih nasledjivanja
  5. potpuna identifikacija povezanosti -> izlaz precizniji dijagram klasa
  6. Specifikacija atributa - meta
  7. identifikacija obrazaca(design pattern), mustrama!!!
  - 3 koraka u dinamickom modleu: 
    1. Scenario(dijagram sekvenci, kolaboracija), 
    2. KA - objasnjenje citavog zivotnog ciklusa izvrsavanja
    3. Opis operacija - dijagram aktivnosti
 - Checklist po Balcertu (kontrolni i konstruktivni)
    - savet
    - 5kontrolnih pitanja
  - Kako pravimo dijagram klasa?
    - pocetni korak : imenovanje klasa i naznacujemo kolicinu atributa
    - reinzinjering gledanjem
    - u tehnickim sistemima moguce oslikavanje problema
      - [27] plavi stikl
    - citanje specifikacija zahteva i trazimo im klase
      - pamcenje u vezi aktera su potencijalne klase
    - operacije
    - 5. kategorije spisak
  - primeri za osobe uloge, organizacije, kataloge, informacije o akcijama
  6. analiticki koraci: smislenost! - ime klasa: imenica u jednini
  7. ciljevi nisu da:
    - pravimo klase sto vise
    - i omanjene kompleksnosti
- checklist asocijacije
  - eliminisanje
  - uocavanje kvalitetnosti eliminisanjea (katagorisenja)
  - ogranicenja
  - uloge (ja sam komunista, volim pare, eto to je **objasnjenje**)
- molim lepo, jako ste krotki
- i gost, duh boo!
- ja sam komunista bespaltno (ne)obrazovanje
- ja sam entuzijasticni isplacivac poreza
- 1:* korisno za DOMACI
  - posaljem mejlom ovo [44]
- 3, DOMACI ZADATAK - BIVSE KLASE U PRETHODNIM SLAJDOVIMA I IZBACILI SMO KLASU JER JE SUVISE OCIGLEDNA i pretvorili je u asocijaciju
- slogove pravimo umesto preprostih tipova podataka
- Checklist nasledjivanja: 
  - analiticki **dobro** nasledjivanje strukture
    - ja sam mentalno zaostao 1. mozak mi ne radi
    - da li je moguce nasledjivanje... - ako da onda je ok.
    - 3 do 5 nivoa u hijerarhiji
  - da li se razlikuje od superclass po tipu?
    - umesto da razvijamo ciavu strukturu redudantno...
  - Primer sa JESTE.
  - CHECKLIST za KA
    - konstruktivni koraci
      - smisleni zivotni ciklusi
      - ...
  - Checklist operacija - 7 koraka
    - opis operacija
    - klas dijag. sa operacijama ugradjenim
  - LALA je pojam koji su sebi vojvodjani udelili, da bi prekrili to da su sve nas nemci zvali PACOVIMA.
  - REZIME!!! AAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAA
    - bitno : klase iz analize dokumenata, UI, atributima definisemo i prosirivanje nasledjivanjem i operacijama
    - otkud onome ko je ovo sto je ovo pravio, BAS OVO?! - evo ga zasto.
    - bar 1x jos.
- pisao sam -- pis pauza 
- MUSTRE - Design Patterns u OOA
  - OOA mustre
  - mora objasnjenje dodatno gledanje koje protrcava, covek
  - objasnjenje po UML primeru: 
  1. lista 1:*
  2. tip primeraka 1:*, za potrebe testiranja TEST...
  3. sklapanje
  4. lista delova
     - dijagram objekata se prvi put pojavljuje
     1. nije ovo djoka dok ne izlupas glavu u realnom vremenu, to je teorija
  5. Kordinator
     - uproscavanje kompleksnih asocijacija u klasu, 
     - korisno za 1. domaci zadataka
   6. Uloge
   7. izmenljive uloge.
   8. ISTORIJA
   9. grupa
   10. 9. i 8.
       - ako zelimo nesto sacuvano
       - `*..*`
       bravo. celovito. i z ovoga dela. 
- problem u pasusu i jednostavan prepoznavanje patterna.
  - po osobini paterna moze da se objasni, ali ne po imenu. <3
- volimo zorana
---
# 9. nedelja - za vreme vezbi
## Tema 15
- stack operacije 3 i 3.5 za izuzetke
- DOMACI do nedelje na slajdu 18. dao javi DO NEDELJE
- horova logika - malo zahtevnija
  - Pitanje : sortiranjem pravimo skroz novi niz 
  - pre/postcondition na primerima programskih jezika
  - axiome
    - **ojacanje preduslova** - dedukcije
    - invarijante - modus ponens, tanens, ...
    - petlje
    - parcijalna/potpuna tacnost - teorija relacije
    - ciljani dokaz
  - Opravdavanje tacnosti dokaza 41.
  - 12 koraci alaize dokazivanja - blok(telo) unutar ciklusa
  - pokvarili smo preduslov za x unutar invarijanti - pokvarili smo racunanje, sta sa time?
    - formalne specifikacije - namlatili bi smo se para, ali nema takvih firama
  - mogucnost automatizovanja
  - Nije snimao
    - fokus na Z
    - 3. i 4. korak su spojeni (verifikacija , semantika)
- Pogled i pristup **Z alata**
  - zasnovan na teoriji skupova
  - po stanjima
- primer nad benzinskim Rezervoarima 
  - opisi stanja
  - opercaije
    - neizmenljiva stanja
    - izlazi
    - preduslovi
    - postuslovi
    - normalni uslovi i explicit uslovi... u trecu situaciju
    - 61. slajd projakat - originalna postavka 
    - 64. stek u Z po svim njegovim operacijama
      - trougao oznacava izmenljivost
      - ???razmislimo da li je ovo uopste za projekat
    - Primer IRL
      - evropska svemirska stanica "Kolumbus" 
      - ne mora se znati 67.
      - DaimlerChrysler: primena Z-a
      - recnik Z-a pretrcao
- Formalna specifikacija
  - Praksa : tesko korisceno, manje njih to rade, ~sta je svrha onda?

# 10 nedelja - tema 16
# Dizajn
- spoljasnji ponasanje
- info vezane za program
  -  dizajn arhitekture  
  -  dizajn implementacija 
-  slabe tacke
  - sw arh je katastrofa
  - nepregledno
  - gomila parametara
  - 60% redudatnost
  - mesavine
  - zavisnosti
- proces
  - ulazi
    - glosar
    - spec zahteva
    - prod model
    - UI demo
    - manual
  - akteri
    - proj.lead, sysanal, designer,implementer
  - alat 
    - template
  - izlazi
    - soft.arch (components+connectors)
    - spec. of sys components (components as black boxes - extbehavior, applied in already A&D)
- soft.arch (
  - components - atomic : function,module, class
  - connectors: call, aggregation, association
- spec. of sys components 
  -  funkcije, ponasanje, potpis informal formal spec
  - klase , klasni dijagrami verbal + formal spec
- arh pascal
  - userdef - rektangle
  - krug - clib
  - strelice - korist elemenata --> druge komponente
  - Koja je glavni? PARSER - koristi sve ostale
- atributi, operacije
- kvalitet dobre Soft arch
  - weak coupling (izmedju komonenata odnosi)
  - strong cohesion (unutar komponenete odnosi)
- coupling
  - cilj - jednostavnije moguce
  - rezultat - razumljiv, modifikabilan, iskoristljiv
    - slabiji - da ima sto manje strelica
- kohezija
  - cilj - svi elementi resavaju zajednicki zadatak
  - rezultat 
    - usmeren-problemu komponentalno izgradjivanje
    - razumljiv
  - lose: ne moze se ponoviti iskoricavanje komponenata koje su unutar komponente
- Kapling vs kohezija: frontend, backend
  - slab kapling, slaba kohezija vezanost
  - moze se takodje javiti kombinacija jak kapling, jaka kohezija
- kako odlucujemo jaku koheziju?
  - za delove mozemo znati sta sve unutar njega se desava, bez detaljnog pregelda
  - dosledno opisivanje strelica
  - nisu babe i zabe 
  - mozemo mu dati ime koje je deskriptivno
- primetiti slab kapling?
  - moraju biti u istom podsistemu nadklasa i podklasa
  - agregacija unutar istog podsistema, 
  - sto manje asocijacija
- radimo odozdo nagore ili odozgo nadole(za velike)
  - 10-15 klasa
  - A4 papir
- OOA -(extended, modified, optimized, adapted to env)-> OOD model
  - klasa dijagram
  - Strukturna analiza -> Dizajn
  - DFD -> Str. chart
  - redosled A&D i Design-a
- 5 tokova dizajna Prog Langa
- Uticaj na softversku arhitekturu
  - prod def -(arch desing)-<> sot arch :-(impl. design)- impl lang
  - prod use - nonsequential - sequential
  - kvaliteta zahtevi - pouzadnost, efikasnost, izmenljivost
  - ciljane platforme - gui: helpsys, data man: expert sys
    - strelice ne menjamo za svaku platformu
  - ovde je pauzirao i pricao im o zasnivanju na servisima koje nude platforme zarad manjeg dodatnog petljanja
  - funkcioalna specifikacija
    - definicija - dizajn - implementacja
- SLOJEVI
  - okruzenje
  - veliki sistemi
  - korisnicki
  - konkretna aplikacija
  - menadzment podataka
  - podela slojeva:
    - linearan poredak
      - pristup dole sloju
    - striktan poredak
      - pristup svim donjim slojevima 
    - drveni poredak
      - nema poprecnih komunikacija
    - zajednicki slog - komunikacija unutar sloja, ali smeju unutar komponente
- slojevita arhitektura
  - slojevi upotrebljivi u istom apstrakcijskom sloju
  - ili poredjan nadole
- prednost : jasna strukt. , jaka hijerarhija i sloboda uredjivanja unutar slojeva, podrska na ponovna koriscenja, izmenjivost, odrzavanje, portabilnost, testiranje
- mana: gubitak efikasnost, deljive apstrakcije podlozne neopisanosti, unutrasnji haos
- logicki sloj arch - 6 slojeva
  - ui, app, datamanag
- fizicke slojevi - vorkstation computer, department server
- disturibuirani server bruh
  - logicki mapiran na fizicki
- karakteristike web/client server
  - permanentna konekcija
  - ogranicen kapacitet korisnika
  - uticaj na komunikaciono okruzenje imaju os, db,..
  - programeri i servere i klijemte programrijau
  - lako nadziranje klijenata od admina
  - max user olaksava dizajna
  - mana: 
    - skalabilno tesko, tesko podesivo za promenu max user
    - klijent softver, klijent masina
    - izmene zahtevaju dodatne izmene
- web arhitektura
  - 1-4 slojni
  - karakteristike: 
    - TCP i http mama? - kratkotrajna veza - response, request
    - kratak vremenski period
    - nema uticaja na browser
    - vise korisnike
    - skalabilnost
    - nema prosirivanje problema
    - mana: browseri izmedju mogu da nemaju univerzalizam mamam

## 17 tema
- Strukturni dizajn
- hijerarhija funkcionalnih komponenti
- structure chart
  - funkcionalna apstrakcija
  - call structure, dataflow - strelice 
- DFD rasturanje
- nemojte da menjate kanal

# 18.tema - OOA -> OOD
1. faza - arch dizajn
2. faza : implementacija - modifikacija
   - konekcija
   - iskoristanvavnjae
   - designe model
   - increase in efficeerenfe
   - aplasikciona kategorisja
- treba svesni uzeri aplikacije
- brisemo nepotrebne atribute jer imamo nasledjene klase koje imaju iste
- poboljsavanje efikasnosti
  - celina klasa zarad intenzivne komunikacije (bez medjuoperacija)
  - direktan pristup atributima, umesto klasama
  - nema izracunavanja, rezultni atribut napravljen!
- implementacioni dizajn
  - modifikacija OOA
  - uoceni propusteni koncepti
    - razresavanje visestrukih nasledjivnja
    - jednstruko nasledjivanje
  - bez nasledjivanja
- frameworkovi
  - dobro orgranizavija koristi softvera
  - nema dodatno ogranicavanje
  - iskoristljivo
  - prilagodljive
  - odluke na osnovu primenljivog domena
- delovi svega uzeti kao 
- kompiler framvrok
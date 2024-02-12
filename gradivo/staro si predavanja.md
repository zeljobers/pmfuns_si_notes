# staro si predavanja
# 1. nedelja - zvrkopis
## googlaj : "daad project joint course on software engineering"
## dodatak prvog dela
- 3:50 - Uz SI postoje i compile construction i databases kao teme,
  - 20:00 - BITNO!!! ali one su povezane unutar SI-a, ali nisu u njemu u potpunosti
- 5:30 - programiranje je deo SI, a ne naopako
- 6:00 - oblasti SI-a
- 7:40 - definicije
- neke određene statistike
- 14:00 - neki oglasi za posao i potrazivanja
- 20:00 - softverske potrebe- slabija potrosnja - ekoloski pristup trosenja struje
- 23:00 - kompleksnost - nemogucnost potpunog shvatanja posebnosti proizvoda
  - 24:00 - grafikon
- 26:00 - preciznost softvera
- 27:00 - problemi koji ukazuju zasto je razlog SI-a
  - venera nije skrenula raketa u orbitu
  - obrnuo se naglavacke avion
  - zdravstveno osiguranje nije na vreme zavedeno...
  - 33:00 Windows gine
- 32:00 - BITNO!!! kolicina potrebna za:
  - razvijanje softvera **12-24 meseca**
  - izradu osrednje velicine softvera u **10 linija** izvornog koda po danu po osobi.
  - u svakih 1000 linija izv. koda se nadje oko **50-60 gresaka** tokom razvijanja.
  - u svakih 1000 linija izv. koda se nadje oko **ispod 4 gresaka** nakon razvijanaj.
  - procenat uspesno zavrsenih projekata : **70-80%**
  - naplata odrzavanja je **skuplja 2x** od razvijanja
  - nadjene greske od strane korisnika u softveru je ishod **problema u opisu problema, nerazumevanja opisa problema.**
  - koji procenat uzima programiranje tokom razvijanja softvera? **-50%** 
  - Veliki softverski projekat ima u sebi 100k LinesOfsourceCode.
- 46:00 - Defect rate = #ofErr / 1000LOC
- defect rate se za 18 godina pogorsao za +0.01x
## 2. video
- 2:00 - Velicina softvera
  - mali do 2000LOC
  - osrednji do 2000LOC
  - veliki do 100k LOC
  - veoma vise od 1M LOC
- top 100 US companies contains projects with 35M LOC
- DoDefence 1,4*10^9 LOC - 1700 dataCentres - najvise koda
- 5:30 - tabela zarade/vremena/LOC
- 6:30 - razlog za *besmrtnost* COBOL-a
- 7:30 - istorijat
- 11:30 - softver i hardver troskovi (softver prevazisao)
- 13:00 - definicija SI-a opet, IEEE
  - sistematicna primena
  - disciplinovanog pristupa
  - merljivog pristupa
  - razvoja softvera
  - operacija nad softverom
  - odrzavanja softvera
- 14:55 - nova def
  - definisan
  - korak-po-korak process definisanja
    - spec.
    - dizajn
    - impl
    - test
  - resenja za skup zahteva vernih ocekivanjima i jeftinijim ulaganjima
- 21:00 - zasto SI nije jednostavno? 
  - nije fokusirano na problem studentskog napora, 
  - vec programa
  - Nema mogucnosti u srednjim skolama:
    - realni musterija
    - simulacija timskog
    - pregovaranja
    - vremenski glomazno
    - troskovi simulacije su veci
- 36:00 - svi dokumenti u toku razvijanja softvera
- 37:00 - sta dobijes
- 2. 38:00 - ishodi kursa
- 40:00 - primeri alatki
- 2. 44:00 - knjige
## 3. video
- 5:00 - 2 kriterijuma najjacih? - odrzivost i efikasnost, cost effective i quality
- 7:20 - kriterijumi kvlaiteta 
  > _**Vazni**_
  - Korektnost - usaglasenost programa sa zadatim zahtevima
    - mana? - moze da bude korektan, ali nije po zamisljenom
  - **Naklonjenost** - retke greske sa nevaznim efekte
  - **Robust** 
    - opsti : suocavanja sa posledicama u pogresnim okolinama
    - negativne prosledice nekih faktora dole su obrnuto proporcionalne verovatnoci pojavljivanja gresaka u aplikaciji
      - operacija na ulazu ili 
      - delovanja hardvera nad aplikacijom 
  - **Skalabilnost**
  - Portabilnost
  - **Reusability**
  - Maintainability
  - **user-friendly**
  - podrazumevano: **Functionality**
- 25:30 - Klasifikacija
  - eksterni (vidljivi korisnicima) - kvalititivnih
  - interni (nisu)
- 3. 33:00 - bitna tabela koja pokazuje uticaj i potraznju naspram svih mogucih koncepata
- 34:00 - 4. Learnability moze da pita  TEST !!! - sve zavisi
- 3. 39:00 **DOMACI u vezi efikasnosti** - 47:00 do utorka u 23:55 profesorov mejl
- 3. 42:30 - kriterijumi kvaliteta za proizvod ISO 9126(nece biti potrebno za kolokvijume) 
  - vs ISO 9000 razvojnog procesa je bolji (kontinualno)
- 3. 51:00 - u privredi sta kazu ljudi da je bitno

---
# 2. Nedelja - zvrkanje
- Dao je nalik definiciji pojam na pocetku
- Pojmovi
  - SoftProcessModels
  - PhaseModels
  - LifeCycleModl
  - SoftwareDevModl
  - ProjModels
  
## SoftProcessModels
- SE application systematic, disciplined, quantifiable approach to dev, opetaion, maintenance of software

## ProcessModels
  - ProjOgr
  - TimeAndCostPlanning - o
  - Analiza projekta - losa analiza : zeznuo sam se sto sam zaposlio ovoga-onoga
  - QualitativeAssesmentOfSWmodels
### a) sta je
- Sta je specificno za softver?
  - !!!PUNCHLINE: Nista od onoga u preciznoj definiciji nije specificno. (NA TESTU MOZDA) Jer je softver je ukrao od procesa poslovanja te koncepte. 
- Uloga
- Activity scheme
- Artifact - cesce proizvodjen od ljudi
- Proizvod - skup softverski atifakata
### b) Pogled na postojece modele
- Proces modeli
  - -V model
  - Classical phase - waterfall
  - Iterative
  - Incremental
  - Sprial
  - Prototyping
#### Napomena
- opste prihvaceni modeli - idealizovani - nikad ne kazu konkretno sta je cija uloga (fleksibilnost radnog mesta)
- razlicita klasa - razliciti pogodni modeli
#### Vodopad
  - Prvobitan model proces softdev-a do '70.
  - za predmet OS1 ovo je standard programskog koda OS360
  - Dalje koristi nakon '70. ? - Da, ako je hitno izradjivanje ili kratkotrajno...
  - Department of Defence '70. - zasnovan americke vojske
  - Ovaj je zastareo, ali koristimo ga kao **metodoloski** redosled
      - prica o analizi i def
        - analiza problem, definicija zahteva (komunikacija : musterija <-> zaposleni)
        - pisanje SPECIFIKACIJA ZAHTEVA, produkt model!
      - dizajn
        - specifikacija strukture (dijagrami, sabloni)
      - impl
        - blokovi dijagrama su popunjeni izvornim kodom
      - testiranj
        - blokova
      - koriscenje i odrzavanje
  > ovo je metodoloski vodic, centralizovan
  - **svi uslovi za obavljanje faze za prelazak na drugu fazu**
  - gubi se svaki trazen koncept kroz svaku fazu
  ## nema ga 15 minuta -> raus
  - Problem ?
    - strog rad u fazi, ni u jednoj drugoj
    - nema povrataka - otezana komunikacija sa musterijom
    - nema paralelizovnog
    - nema inkremental
- Rizik / vreme графикон kritican
## 10:59 - Proces model nije tvorevina SI-a
## Iterativni
- Rizik / vreme графикон kritican (RUP je primer koji je prosirenje DSDM-a)
- vodopadni je rigidan
- Troskovi
- Statistika gresaka tokom faza
  - 
- Problem ?
  - Nepotrebno prolazenje kroz fazu zarad vracanja u prethodnim fazama
  - Nije izvodljivo ako ljudi rade pod ugovorima

---
## Alternnativne faze NE PITA!
- grafikon specijalne faze modeliranja - baci pogled na manje testiranje
  - brod
  - padobran
---
CASE (Computer Assitent System E)
- faze pitanja proces modela zakljucak na kraju: "znacaj primene modela je uticajan na izradi softvera**
- grafikon risk/time za waterfall

## Inkrementalni
- deo po deo se odradi celina do kraja
- Incremental - iterative dev - naslednik DSDMa, a prethodnik RUP(Rational Unified Process-a)
## V-model - waterfall++ 
    - Requirement def --- Appl scenarios (predvidjanje slucaja)---> Acceptance test 
    - Architectural --- Test cases(sta se testira???) ---> System test
    - opet sta se testira
    - -||-
  - Nemacka drzavna firma trazi V-model

- Potrebno vreme za razvijanje
## Iterativno **prototipiziranje**
- DSDM - UK ima standardizaciju kao sto Nemacka ima fazon

## Prototipiziranje
- koristi se kada je specifikacija nezavisna
  - ne zna se koje zahteve trazi, ali ipak sve faze nagovestavaju
- primer : AI - ne zna se kakav je zahtev, pa u hodu se vrsi prilagodjavanje
- **Rapidno Prototipiziranje** 
  - izbacivanje i dodavanje i izmena specifikacija
- **Evoluciono softdev** - prilagodjavanje prototipa

## Spiralni model
- Metamodel
- !!! TEST - Zasto je spiralni model je metamodel?
    - Svaki okret u spirali, moze da ishodi modela sto vec postoji kao koncept nekog primene izrade prototipa - opisuje drugih modela pomocu njega
      - Svaki okret predstavlja fazu : Pripreme, Dizajna, Implementacija, Testiranja
- Prolazi se kroz nekoliko procesa strogo, ali vraca se ukrug.
- Sve dok se ne suzi skroz kruzenje.
- 5 faza uglavnom : problema, rizika analiza, realizacija, planiranje, pregled 
- Fleksibilan
## Razime
- Tema 3a - Agilni na vezbama, kao dodatna tema na vezbama
- 1 - do nekle reci ce asistentkinja koje teme, kada(u naredne dve nedelje)?
  - online, ili uzivo na osnovu preporuka sporednih lica

## Tema 4 - nije tema za prvi test - obnova - NOTACIJE DOKUMENATA! [**OVO SAM PROTRCAO**]
- nacini da opises softver
- 1:07:00 drugi video - BITNO ! celi pristup notacija!
- osnovni koncepti 
  - sema se gleda po redovima odozdo-nagore 
  - i sve navise vide se finese("naocare")
  - ---
- nisam nesto pratio, neko delovanja nad fazama...
  ---
- notacije koje su zgodne za projektovanje softvera
### Metod-interakcija koncept
- kombinacija osnovnih koncepta u ObjOrientAnalysis
- kombinacija osnovni koncepata u StructAnalysis
# 2. Nedelja - obnavljanje tema 3 proces modeli softvera
- 5 termina koriscenih
  - model zivotnog ciklusa: razvoj i odrzavanje
    - vs. model razvijanja softvera : bez odrzavanja
  - zasto? jedna od 4 definicija ! BITNO za test!!! SI je primena sistematicnih, disciplinovanih pristupa nad razvojem, operacijama i odrzavanjima softvera
    - izucavanje modela zarad sistematicnog razvijanja softvera
  - Za sta je potreban?
    - Organizacija : nema svojevoljnog delovanja, vec dogovorenog
    - Planiranje vremena i troskova - nema planiranja ovoga ako nema modela
    - Analiza projekta : Bez modela odgovor na pitanje: "Koje su slabe tacke procesa razvijanja?" ne moze da se dobro analiza uspostavi. 
    - Ocenjivanje od strane jacih sofverskih kompanija : nase prikazivanje njima postovanja std. ISO9000
  - 11:00 - BITNO !!! Proces model definicija i preciziranje njeno
    - definicija koja ustanovljava 
      - koje aktivnosti,
      - od koje osobe,
      - u kojoj ulozi;
      - u kom redosledu aktivnosti se desavaju
      - koji proizvodi
      - ce se razvijato
      - i ko/kako ih ocenjuje?
      - PITANJE: sta je ovde bitno za softver? - ništa
  - Ostvarivanja aktivnosti
    - artifakti (npr. model ili dokument - prozvod coveka)
    - metode
    - uloge
    - alati
  - Softverski proizvod skup artifakata
  - Napomena u vezi modela
    - moraju biti fleksibilni (ne mora tacno neko da radi jedan posao i do odredjenog vremena da zavrsi)
    - za svaku klasu posebno ce mozda morati da se upotrebljavaju drugi modeli 
  ---
  2.35:19 -
# 3. Nedelja Tema 5
## Waterfall analiza i definicija
- Sta radi spolja i kakvi su zahtevi "od spolja"?
  - Balzert 2001 2 podfaze Analiza i definicija - 8 fajlova
    - Planiranje
      - 4 fajlova
    - Definisanje
      - 4 fajlova    
  ### Naznacenja
    - 9:45 Zasto podeljeno? - Druga faza (definisanja) se mozda ne desi
    - Faza planiranja se radi dobrovoljno - volonterski
      - osnova ugovora koji se naknadno potpisuje
    - Dizajn modela (uml-like)
    - fleksibilnost dokumentacije
## 14:00 - Planiranje vizuelizacija ...
## 17:30 - Uloga : Odgovornost i saradnja raspodela izmedju musterije, project leader-a i application specialist-e
- 34:30 -  

## 21:00 - Case-study : primer za izradu
- Glossary 1.postupak planiranja - vokabularnik koriscen u daljem poslovanju:
    - specifikacija zahteva
    - UI
    - online tehnicka podrska
    - korisnicka dokumentacija
  - Ovaj primer ima 12 termina
  - XCTL (neki drugi) ima 110
  - na primeru objasnjavaju se uloge ko sve koristi projekat
  - 34:30 - Aplication specialist - zaduzen za njegovo ostvarivanje
## 36:00 - Specifikacija zahteva
- U planiranju se zove preliminarna specifikacija zahteva
- A konacna(obicna) je u definisanju - mozda ne bude napravljenja

## 38:25 - Faza definicije
- 39:50 - Unosimo u proces definisanja proizvodnje glossary i na kraju opet ide glossary
- 40:30 - -||- preliminarnu spec. i na kraju izlazi konacna
- 40:40 - Templatovi se uvazavaju
- 41:00 - Uloge u izradi proizvoda
- 44:00 - Jedan od nas, Application specialist, has 4 tasks, but system analyst has 1 out of 5 (product model)
- 52:00 - Za konacnu specifikaciju zavisnosti : funkcionalna zavisnost je vazna za sve ostale zavisnosti koje trazimo od korisnika (1 od 7 zavisnosti)
- 53:00 - Realizacije preliminarne specifikacije zavisnosti
  - 53:50 - zarad procena troskova i izrada plana
## 57:00 - poseban nacin izrade IEEE 830-1993
- 3 dela
  - Uvod
  - Opsirni opis
  - Specificni zahtevi
    - 59:50 - Bez obzira od kakav je template nece te ograniciti da ne pises nesto, vec govori samo ono sto treba da se ispuni
# 3. nedelja 2 deo
##  Rezultati faze analize i definicije
- 2:38 - Struktura
- 2:40 - ONo sta treba biti navedeno bice navedeno.
- 4:00 - Funk. zahtevi vs. use case-ovima
- 7:25 - Specifikacija zasnovana use-casovima koji su bitni na RUP i DSDM (tema 3)
## 9:20 - Ciljevi na 3 podsekcije
- 9:30 - Obavezni uslovi (razlike seminari i kursevi)
  - poslovi za odredjene kategorisane grupacije ljudi
  - 11:00 - Spremanja informaciona pitanja koja nudi softver
- 11:50 - Opcioni uslov
  - Oslobadjamo se fizicko-mentalne podrske i automatizujemo sistem
  - Automatizujemo sporedne potrebe
  - Dostavljanje statistickih podataka ishoda koriscenja proizvoda
  - Osiguravanje privatnosti podataka
- 13:20 - Izuzeti (odbaceni) uslovi
## 14:50 - Koriscenje proizvoda - sfere i ciljane grupe
- 15:40 - Vazno! Dve vrste klijenata. 
  1. Nasi klijenti(uloge unutar kompanije) 
  2. njihovi klijenti koji ce da koriste nas softver za svrhu nabavljanja usluge 1. klijenta
## 17:00 - Pregledanje proizovda uz pomoc UseCase dijagrama
- [Use case-ovi su sada bitni, pa je dobro da znas sta je. (UML)](https://sparxsystems.com/enterprise_architect_user_guide/14.0/guidebooks/tech_ea_use_cases_and_scenarios.html)
- 19:00 - desno su 1., a levo su 2. iz 15:40
- 20:50 - use case-ovi
### 24:00 - neformalno objasnjenje usecasova
  - obrazlaganja osnovnih fja (opsirno i ne jako precizan)
  - jasni svakom korisniku
  - mogucnost komunikacije izmedju 1. sistema i 2. korisnika
### Akteri i akteri sa privilegijama
## 27:00 Funkcije proizvoda  (zavirujemo u detalje)
- 27:50 - Opisujemo tekstualno usecasove; moglo je na 5-6 mogucih nacina
- Treba da struktuiraano dovoljno precizno na sekcije...
- 30:15 - F10 i F20,... Zasto? - 32:30 - Postoje medjuslucajevi i motivacija za detaljisanje (bojimo se da mogu da dodju novi use-case-ovi)
- 35:00 - Bitno! Preliminary Function - PF, a F - doradjen PF
- 37:00 - ime useCase-a i za primer sta je ulaz i izlaz : info dostavljen na korisnicko pitanje
- 37:50 - Tip Hint Notifications
- 38:00 - Kategorija - prioritet
- 38:20 - Preduslovi i okidajuca zbivanja su uzajamno uticajna
  - 38:50 - Preduslovi (uopsten uslov) - Opste stanje unutar softverskog sistema koje treba da bude ostvareno da bi useCase bio izvrsen
  - 39:00 - Okidajuca zbivanja (okida na konkretan dogadjaj)
- 39:50 - Post(naknadni )uslov - ~Kod nas : nikog ne boli uvo sta je bilo posle;~ 
- 42:00 - Okidac - klijent kontaktira kompaniju 1.
### funkcionalnosti
- 43:10 - Zakljucivanje postojanje klijenta i dostavljanje informacija - **normalna sekv. aktivnosti (*default ponasanje*)**
- 44:00 - **Posirivanje** aktivnosti sa do broja dopisivanje slova redom alfabetom
  - 44:30 -  48:30 - klijent naznacava da je doslo do promene, i daje nove podatke kuda da se dostavi usluga
- 51:00 - **Alternativa** - umesto 1 realizuje se 1a, jer je drugi slucaj u pitanju (npr. ne postoji u sistemu)
## 54:00 - F20
## 1:00:00 - Liste - medjustanje i krajnji ishod koriscenja proizvoda
## 1:02:00 - Zahtevi za drzanje podataka D10
## 1:05:00 - zahtevane Performanse
## 1:05:30 - Uslovljavanje kvaliteta
## 1:07:00 - Korisnicki intefejs U10
- sekcija sa zahtevima(useCase)
- 1:08:00 - privilegije u nasem timu ko kojim useCasovima sme da pristupa
## 1:10:00 - Nefunkcionalni zahtevi
- 1:11:00 - Okruzenje - faktori koji smaraju
## 1:11:30 - Tehnicki proizvodno okruzenje - gde se prisupa nasem proizvodu
## 1:12:00 - Softver
- ServerOS
- ClientOS
## Hardver
- Server device
- Client device and app
## 1:13:30 - Struktura dela projekta
- opis donje tabele
- Potrebna sredstva po verzijama
## Dopunjavanje - naznaka
- 1:16:00 - neka interesantna mudrost iz iskustva od 1. kompanije
  ---
## 1:19:30 - Ljudi dobijaju uvek sta su trazili (tema 3-4 ima ovo) 
- Ovo se tice: Nezadovoljstvo izradjenom specifikacijom
## 1:20:30 - Pregled
- Pozadina - uzimamo nesto da ispreciziramo
- Metod - uzimamo nesto fiksno za **citanje**(jedini alat je citanje)
- 1:22:50 - Ucesnici, razmatranja pregledanja, osvrtanje na sve ovo
- 1:23:30 - Kontrola dokumenata kontrolama kontrolno
- IEEE 1028-1988
## 1:24:00 - Primer
- zaglavlje informacije o pregledanju
- zakljucci, problemi, naznake zabrinutosti po pitanju dokumenta, naznake o samim sastancima oko razmatranja pregledanja
- 1:25:50 - kritika, objektivan, bezobrazan (ne saosecaj)
## 1:26:30 - Greske tok
## 1:27:50 - Izmenjivost spec. zahteva
- 1:28:50 - 3 razloga BITNO! TEST!!!
  - greske
  - vremensko trosenje
  - drugacija struktura potrebna
- 1:31:00 - BITNO! Specifikacija zahteva
- 1:32:00 - Iz 40 funkcija pravimo 9 useCasova!
- 1:33:00 - Razlike medju verzijama(manje bitno)
- 1:36:00 - SKIP :... XCTL 5 preskacemo do :
- 1:38:10 - Use case dijagrami ce po
- Tema 5E NE dolazi na test. Samo Tema 5A - 5D.

## 1:40:30 Prica za projekat
- kritikovanje -> protokol + \< opciono> audit (dovodjenje nekog iz tima koji radi u firmi)
## 1:44:00 - System analitycs vs Appl. specialist (isti su - po terminologiji)

## Grupa6-PogrebnoDrustvo
# Tema: Aplikacija za upravljanje pogrebnim društvom

![](https://i.imgur.com/3muk3Hd.jpg)

##### Članovi tima:
- [Kokić Elmir](https://github.com/ekokic98)
- [Sekulić Davor](https://github.com/dsekulic1)
- [Japalak Tarik](https://github.com/tjapalak1)

### Opis projekta:
Aplikacija je namjenjena da olakša proceduru pri organizaciji sahrane. Ona daje mogućnost da se rezerviše grobno mjesto, odredi vrijeme sahrane, organizira prevoz umrle osobe, odrede detalji oko vjerskih obreda, izradi smrtovnica i ista pošalje u novine i na portale ukoliko korisnik to zahtjeva od nas.
Također aplikacija omogućava i organizaciju i raspodjelu posla zaposlenim osobama u pogrebnom društvu za što je zadužen poseban korisnik aplikacije. 
Ova aplikacija trebala bi služiti kao pomoć korisnicima koji žele unaprijed rezervisati grobno mjesto i odrediti detalje oko sahrane kao i korisnicima koji organiziraju sahranu za člana porodice.

### Procesi:

#### Korisnik
Korisnik ima opciju registracije ili prijavljivanja na sistem u ovisnosti da li je novi korisnik ili već ima svoj korisnicki račun. Ukoliko se korisnik prvi put registruje, on mora ispuniti formular u kojem unosi neke od osnovnih ličnih podataka. Nakon unosa podataka klijent može da pogleda neku od ponuda firme i odabire uslugu za koju je zainteresian. Ukoliko korisnik ima profil može da provjerava stanje usluga koje koristi (članarina za rezervaciju i godišnje održavanje grobnog mjesta).

#### OWNER
OWNER je vlasnik firme/aplikacije koji ima najveći stepen privilegija (mogućnosti). On upravlja firmom i dodjeljuje privilegije ostalim korisnicima ove aplikacije tj. Administratoru uposlenih i Administratoru aplikacije. 

#### Administrator uposlenih
Korisnik koji se direktno prijavljuje na aplikaciju sa podacima koje mu je dostavio OWNER. Njegov zadatak je da organizira zaposlene i dodjeljuje im njehove poslove za određeni vremenski period (kreira i štampa radne naloge). Pored toga on nakon što mu Administrator aplikacije proslijedi zahtjeve iste odobrava ili odbija u skladu sa trenutno raspoloživim resursima u firmi. 

#### Administrator aplikacije
Korisnik koji se direktno prijavljuje na aplikaciju sa podacima koje mu je dostavio OWNER. On također može izvršiti registraciju klijenta ukoliko je klijent došao direktno u poslovnicu. Komunicira sa krajnjim korisnicima, obrađuje zahtjeve i šalje ih Administratoru uposlenik. Ima mogućnost da briše korisničke naloge kao i odobravanje promjena u korisničkom računu. Vodi evidenciju o obavezama Korisnika prema firmi te ih obavještava o eventualnim dugovanjima.

### Funkcionalnosti:
+ Mogućnost registracije novog korisnika  
+ Mogućnost prijave na sistem korisnika ili uposlenika sa već napravljenim računom  
+ Rezervacija grobnog mjesta unaprijed
+ Organizacija sahrane
+ Organizacija prevoza umrle osobe
+ Organizacija vjerskog obreda
+ Komunikacija i slanje smrtovnice novinama i portalima
+ Unutarnja organizacija firme i poslova u istoj
+ Mogućnost potvrde ili odbijanja zahtjeva
+ Mogućnost pregleda svih klijenata i uposlenika (mogućnost OWNER-a)
+ Mogućnost birsanja korisničkog računa klijenta  

### Akteri:
+ OWNER – određuje Administratore i daje im privilegije za upravljanje aplikacijom
+ Administrator  aplikacije - zadužen je za upravljanje programom, odobravanje korisničkih zahtjeva i kontaktiranje sa klijentom te slanje zahtjeva ka Administratoru uposlenik
+ Administrator uposlenih - zadužen je za organizaciju uposlenih i izradu naloga 
+ Korisnik - krajnji korisnik usloga, registruje se na aplikaciju i šalje zahtjeve za usloge koje želi na odobravanje Administratoru aplikacije


# football-match-betting-predictions

Informazioni sulle chiavi del Dataset
Chiave per i dati dei risultati:
- Div = Divisione League
- Date = Data della partita (gg/mm/aa)
- Time = Momento del calcio d'inizio della partita
- HomeTeam = Squadra di casa
- AwayTeam = Squadra ospite
- FTHG and HG = Obiettivi della squadra di casa a tempo pieno
- FTAG and AG = Obiettivi di squadra in trasferta a tempo pieno
- FTR and Res = Risultato a tempo pieno (h=vittoria in casa, D=pareggio, a=vittoria in trasferta)
- HTHG = Gol della squadra di casa a metà tempo
- HTAG = Gol di squadra in trasferta a metà tempo
- HTR = Risultato del primo tempo (h=vittoria in casa, D=pareggio, a=vittoria in trasferta)
Statistiche delle partite (ove disponibili)
- Attendance = Affluenza alla folla
- Referee = Arbitro della partita
- HS = Colpi della squadra di casa
- AS = Tiri in trasferta
- HST = Colpi della squadra di casa sul bersaglio
- AST = Tiri in trasferta sul bersaglio
- HHW = Home Team Hit Woodwork
- AHW = Squadra in trasferta Hit Woodwork
- HC = Corner della squadra di casa
- AC = Angoli della squadra in trasferta
- HF = Fallo commesso dalla squadra di casa
- AF = Falli commessi in trasferta
- HFKC = Calci di punizione concessi dalla squadra di casa
- AFKC = Calci di punizione concessi dalla squadra ospite
- HO = Fuorigioco della squadra di casa
- AO = Fuorigioco della squadra in trasferta
- HY = Cartellini gialli della squadra di casa
- AY = Cartellini gialli della squadra ospite
- HR = Cartellini rossi della squadra di casa
- AR = Cartellini rossi della squadra in trasferta
- HBP = Home Team Bookings Points (10 = giallo, 25 = rosso)
- ABP = Punti Prenotazioni Squadre Away (10 = giallo, 25 = rosso)

Si noti che i calci di punizione conceeded includono falli, fuorigioco e qualsiasi altra offesa commessa e saranno sempre uguali o superiori al numero di falli. I falli costituiscono la stragrande maggioranza dei calci di punizione concessi. I calci di punizione concessi vengono mostrati quando non sono disponibili dati specifici sui falli (Francia 2a, Belgio 1a e Grecia 1a divisione).
Si noti inoltre che i cartellini gialli inglesi e scozzesi non includono il cartellino giallo iniziale quando un secondo viene mostrato a un giocatore che lo converte in rosso, ma questo è incluso come giallo (più rosso) per le partite europee.
Chiave per i dati sulle quote di scommessa 1X2 (partita):
- B365H = Bet365 quote vittoria in casa
- B365D = Quote di estrazione Bet365
- B365A = Bet365 quote vittoria in trasferta
- BSH = Blue Square quote di vittoria in casa
- BSD = Quote di estrazione Blue Square
- BSA = Blue Square quote di vittoria in trasferta
- BWH = Quote di vincita in casa Bet&Win
- BWD = Quote di estrazione Bet&Win
- BWA = Quote di vincita in trasferta Bet&Win
- GBH = Quote di vincita in casa di Gamebookers
- GBD = Quote di sorteggio Gamebookers
- GBA = Quote di vincita in trasferta dei Gamebookers
- IWH = Quote di vittoria in casa Interwetten
- IWD = Quote di pareggio Interwetten
- IWA = Quote di vittoria in trasferta interwetten
- LBH = Ladbrokes quote di vittoria in casa
- LBD = Quote di estrazione di Ladbrokes
- LBA = Ladbrokes in trasferta quote di vittoria
- PSH e PH = Pinnacle quote di vittoria in casa
- PSD e PD = Quote di pareggio Pinnacle
- PSA e PA = Pinnacle quote di vittoria in trasferta
- SOH = Sporting Odds quote vittoria in casa
- SOD = Quote sportive quote di estrazione
- SOA = Quote Sportive quote vittoria in trasferta
- SBH = Sportingbet quote di vittoria in casa
- SBD = Quote di pareggio Sportingbet
- SBA = Sportingbet quote vittoria in trasferta
- SJH = Stan James quote di vittoria in casa
- SJD = Stan James pareggio quote
- SJA = Stan James in trasferta quote vittoria
- SYH = Stanleybet quote di vittoria in casa
- SYD = Stanleybet quote di pareggio
- SYA = Stanleybet in trasferta quote di vittoria
- VCH = VC Bet quote di vincita in casa
- VCD = Vc Bet quote di estrazione
- VCA = VC Bet quote di vincita in trasferta
- WHH = William Hill quote vittoria in casa
- WHD = William Hill quote di pareggio
- WHA = William Hill in trasferta quote vittoria
- Bb1X2 = Numero di bookmaker BetBrain utilizzati per calcolare le medie e i massimi delle quote delle partite
- BbMxH = Betbrain massimo di vincita in casa
- BbAvH = Betbrain probabilità medie di vittoria in casa
- BbMxD = Betbrain quote di pareggio massimo
- BbAvD = Betbrain media delle quote di vincita
- BbMxA = Betbrain massimo di vittorie in trasferta
- BbAvA = Betbrain media di vittorie in trasferta
- MaxH = Quote di vincita in casa massime del mercato
- MaxD = Quote di vincita massima del pareggio di mercato
- MaxA = Quote di vincita in trasferta massime del mercato
- AvgH = Probabilità di vincita in casa medie di mercato
- AvgD = Quote di vincita medie del mercato
- AvgA = Quote di vincita in trasferta medie di mercato

Chiave per le quote totali di scommessa sugli obiettivi:
- BbOU = Numero di bookmaker BetBrain utilizzati per calcolare medie e massimi di over/under 2,5 goal (goal totali)
- BbMx>2.5 = Betbrain massimo oltre 2.5 goal
- BbAv>2.5 = Betbrain media oltre 2.5 gol
- BbMx<2.5 = Betbrain massimo sotto i 2.5 gol
- BbAv<2.5 = Betbrain media sotto i 2.5 gol
- GB>2.5 = Gamebookers oltre 2.5 gol
- GB<2.5 = Gamebookers sotto i 2,5 gol
- B365>2.5 = Bet365 oltre 2.5 gol
- B365<2.5 = Bet365 sotto i 2,5 gol
- P>2.5 = Pinnacle oltre 2.5 gol
- P<2.5 = Pinnacle sotto i 2,5 gol
- Max>2.5 = Massimo di mercato oltre 2,5 obiettivi
- Max<2.5 = Massimo di mercato sotto i 2,5 obiettivi
- Avg>2.5 = Media di mercato superiore a 2,5 gol
- Avg <2,5 = Media di mercato inferiore a 2,5 gol


Chiave per le quote di scommesse con handicap asiatico:
- BbAH = Numero di bookmaker BetBrain utilizzati per medie e massimi di handicap asiatici
- BbAHh = Betbrain dimensione dell'handicap (squadra di casa)
- AHh = Dimensione del mercato dell'handicap (squadra di casa) (dal 2019/2020)
- BbMxAHH = Betbrain massimo asiatico handicap squadra di casa quote
- BbAvAHH = Betbrain media asiatica handicap squadra di casa quote
- BbMxAHA = Betbrain massimo handicap asiatico in trasferta quote squadra
- BbAvAHA = Betbrain media asiatica handicap in trasferta quote squadra
- GBAHH = Quote della squadra di casa con handicap asiatico gamebookers
- GBAHA = Quote squadra in trasferta handicap asiatico Gamebookers
- GBAH = Gamebookers dimensione dell'handicap (squadra di casa)
- LBAHH = Ladbrokes Asian handicap squadra di casa quote
- LBAHA = Ladbrokes Asian handicap away team odds
- LBAH = Ladbrokes dimensione dell'handicap (squadra di casa)
- B365AHH = Bet365 Asian handicap home team quote
- B365AHA = Bet365 Asian handicap quote squadra in trasferta
- B365AH = Bet365 dimensione dell'handicap (squadra di casa)
- PAHH = Pinnacle Asian handicap squadra di casa quote
- PAHA = Pinnacle Asian handicap quote squadra in trasferta
- MaxAHH = Quote di squadra di casa con handicap asiatico massimo di mercato
- MaxAHA = Quote di squadra in trasferta con handicap asiatico massimo di mercato	
- AvgAHH = Quote medie di mercato della squadra di casa asiatica
- AvgAHA = Quote medie di mercato della squadra asiatica handicap in trasferta

Quote di chiusura (ultime quote prima dell'inizio della partita)
Come sopra ma con un carattere "C" aggiuntivo che segue l'abbreviazione del bookmaker / Max / Avg
Football-Data desidera riconoscere le seguenti fonti che sono state utilizzate nella compilazione dei risultati e dei file delle quote di Football-Data.

Risultati attuali (tempo pieno, metà tempo)
XScores - http://www.xscores .com
Statistiche delle partite
BBC, ESPN Soccer, Bundesliga.de, Gazzetta.it e Football.fr
Quote scommesse bookmakers
Bookmaker individuali
Le quote di scommessa per le partite del fine settimana vengono raccolte il venerdì pomeriggio e il martedì pomeriggio per le partite infrasettimanali.
Ulteriori statistiche delle partite (corner, tiri, prenotazioni, arbitro, ecc.) per le stagioni 2000/01 e 2001/02 per i campionati inglese, scozzese e tedesco sono state fornite da Sports.com (ora sotto nuova proprietà e non più disponibile).

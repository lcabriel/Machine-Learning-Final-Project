#games.csv

#LEGENDA

GAME_DATE_EST: data quando è stata disputata la partita

GAME_ID: codice identificativo partita

GAME_STATUS_TEXT: stato della partita (FINAL significa che è conclusa) ma non ce né nessuna che non lo sia

HOME_TEAM_ID: codice identificativo del team che ha giocato in casa

VISITOR_TEAM_ID: codice identificativo del team che ha giocato ospite

SEASON: stagione

TEAM_ID_home: DUPLICATO DI HOME_TEAM_ID

PTS_home: Numero dei punti segnati dal team in casa

FG_PCT_home: Field Goal Percentage del team in casa 

####################

Field goal percentage is used to measure how well a player or team shoots the ball during a game. To calculate field goal percentage, divide the number of made shots by the total number of shot attempts

####################

FT_PCT_home: Free Throw Percentage del team in casa

####################

Calculating your Free Throw Percentage is pretty straight forward. You simply take the number of free throws made and divide it by the total number of attempts.

####################

FG3_PCT_home: Three Point Percentage del team in casa

####################

You simply take the number of 3 Pointers made and divide it by the total number of attempts. 

####################


AST_home: assist dell'home team

REB_home: rimesse dell'home team

TEAM_ID_away: DUPLICATO DI VISITOR_TEAM_ID

PTS_away: punti del team ospite

FG_PCT_away: field goal percentage del team ospite

FT_PCT_away: free throw percentage del team ospite

FG3_PCT_away: three point percentage del team ospite

AST_away: assist del team ospite

REB_away: rimesse del team ospite

HOME_TEAM_WINS: se il team in casa vince il parametro è 1 mentre se perde è 0


################################################################################################################################

#games_details.csv

#LEGENDA


GAME_ID: VEDI SOPRA

TEAM_ID: VEDI SOPRA

TEAM_ABBREVIATION: Abbreviazione del nome del team

TEAM_CITY: Città dove la partita è stata giocata

PLAYER_ID: codice identificativo del giocatore

PLAYER_NAME: nome del giocatore

NICKNAME: nickname del giocatore 

START_POSITION: Posizione di partenza. Se non c'è nulla vuol dire che era in panchina

COMMENT: eventuali commenti

MIN: minuti giocati

FGM: field goal svolti

FGA: field goal tentati

FG_PCT: percentuale field goal

FG3M: tiri da tre punti svolti

FG3A: tiri da tre punti tentati

FG3_PCT: percentuali tiri da tre punti

FTM: free throw svolti

FTA: free throw tentati

FT_PCT: percentuale free throw

OREB: rimesse offensive

DREB: rimesse difensive

AST: assist

STL: steal

BLK: blocked shot

TO: turnover

PF: personal foul

PTS: punti segnati dal giocatore

PLUS_MINUS: Plus-Minus


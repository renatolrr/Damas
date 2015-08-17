La anotación es por etiquetas y se utiliza [ ] 
  
Los archivos pdn necesitan tener las siete siguientes eqtiquetas: 
 
Event: el nombre del torneo o la partida.  
Site: la ciudad del evento.  
Date: dia del comienzo del evento en formato yyyy/mm/dd.  
Round: ronda del evento.  
White: nombre del jugador de blancas ( apellido,nombre).  
Black: nombre del jugador de negras.  
Result: resultado. ("1-0","0-1","1/2-1/2","*").  

Posiciones de juego: 
  
[FEN "[Turn]:[Color 1]K[Square number][,]...]:[Color 2]K[Square number]
[,]...]"]

Turn
    the side to move, B for Black, W for White
Color 1 and Color 2
    the color for the Square numbers that follow B for Black, W, and the sequence is unimportant.
K
    optional before square number, indicates the piece on that square is a king, otherwise it is a man.
Square number
    indicates the square number occupied by a piece. The square number must be at least a "1". On an 8×8 board, it has a range from 1-32. These are comma separated, and the sequence is unimportant.
  
  
Variantes:  
 
[GameType "Type-number [,Start color (W/B),Board width, Board height,Notation ,Invert-flag"]  
  
  Type-number: this is one of the following type-numbers:

0: Chess
1: Chinese chess
2-19: future chess expansion
20: 10x10 draughts (international)
21: English draughts (kings only move 1 step at a time)
22: Italian draughts (as English, Men cannot take kings, must capture max)
23: American pool draughts (as 10x10, not obliged to take max)
24: Spanish pool  draughts (as 10x10 rules, but men cannot capture backwards)
25: Russian draughts
26: Brazilian 8x8  draughts (same as 10x10 rules)
27: Canadian 12x12  draughts (same as 10x10 rules)
28: Portuguese draughts
29: Czech draughts
30: Turkish draughts
31: Thai draughts
40: Frisian draughts
41: Spantsiretti (Russian draughts 10x8)
32-39, 42-49: Future draughts expansion
50: Othello
51..  Future expansion.

Start-color
    B for Black, W for White
Board-width
    board width
Board-height
    board height
Notation

    A - alpha/numeric like chess
    N - numeric like draughts
    S - SAN - short-form chess notation. Then follows a number 0-4 telling where square A1 or 1 is for the side who starts the game (White or Black), 0 = Bottom left, 1=Bottom right, 2=Top left, 3=Top right.

Invert-flag

    0 - pieces on dark squares
    1 - pieces on light squares


  
Fuente: https://en.m.wikipedia.org/wiki/Portable_Draughts_Notation.  

# Progetto_PSE
Progetto per l'esame di progettazione dei sistemi elettronici
- ideale_v2:Circuito di v_stabile con in ingresso una perfetta onda quadra generata via software (guadagno estremamente basso).
- 555_variabili_v1: Onda generata da un circuito 555 astabile (Non funzionante, divergente).
- v_stabile: Verione non shiftata e stabile del circuito.
- v_reale: Versione che utilizza opAmp ideali (tra parentesi viene indicata la unit-gain bandwith di ogni opamp):
	* LT1818 non funziona (400MHz)
	* LTC6244 Funzionante, minimo shift up della sinusoidale (50MHz)
	* LT1208 non funziona (45MHz)
	* AD823 Funzionante (16MHz)
	* AD8067 non funziona (54MHz)
	* AD549 Onde distorte (1MHz)
	* AD744 Onde molto distorte (13MHz)
	* LT6234 Bassa banda, onde molto shiftate (60 MHz)
	* OP27 Riduce il guadagno delle onde (8 MHz)
	* RH1814 non funziona, modifica la forma delle onde quadre (100 MHz)
	* LT1055 Shifta verso il basso la triangolare (6.5MHz)
	* LTC7652 Chopper stabilizer (Senza pulse non starta) (1.2MHz?)

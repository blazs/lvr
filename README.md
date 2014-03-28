lvr
===

Logika v racunalnistvu --- koda iz vaj.

# Dokumentacija 

## Struktura projekta 
 * `doc/` vsebuje opis nekaterih prevedb odlocitvenih problemov na SAT. 
 * `src/` vsebuje izvorno kodo:
   * `src/main.py` glavna datoteka s primeri uporabe.
   * `src/prop.py` osnovne podatkovne strukture. 
   * `src/simplify.py` poenostavljanje izrazov. 
   * `src/sat.py` naiven SAT solver, ki iterativno preisce vseh 2^n prireditev vrednosti izrazu. (Nedokoncan.)
   * `src/freser_sat.py` naiven bruteforce SAT solver in DPLL SAT solver [[2](#literatura)], predpostavlja, da je vhodna formula v CNF.
   * `src/generate_tests.py` preprost generator testnih instanc.

## Primer uporabe 
 V delu.

## Literatura 
 * [1] Huth and Ryan, [Logic in Computer Science: Modelling and Reasoning about Systems](http://www.amazon.com/Logic-Computer-Science-Modelling-Reasoning/dp/052154310X), second edition, 2004.
 * [2] Wikipedia, [DPLL algorithm](http://en.wikipedia.org/wiki/DPLL_algorithm), Wikipedia, accessed 28-Mar-2014.

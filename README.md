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
   * `src/sat.py` naiven bruteforce SAT solver in DPLL SAT solver [[2](#literatura)], predpostavlja, da je vhodna formula v CNF. (Vsebuje tudi naiven SAT solver, ki iterativno preisce vseh 2^n prireditev vrednosti izrazu, a je nedokoncan.)
   * `src/generate_tests.py` preprost generator testnih instanc.

## Primer uporabe 
 V delu.

## Komentar
 Uporabili smo seznam``benchmark'' sudokujev [4].
## Literatura 
 * [1] Huth and Ryan. [Logic in Computer Science: Modelling and Reasoning about Systems](http://www.amazon.com/Logic-Computer-Science-Modelling-Reasoning/dp/052154310X), second edition, 2004.
 * [2] Wikipedia. [DPLL algorithm](http://en.wikipedia.org/wiki/DPLL_algorithm), Wikipedia, accessed 28 March 2014.
 * [3] Boris Konev and Alex Lisista. [A SAT Attack on the Erdos Discrepancy Conjecture](http://arxiv.org/abs/1402.2184). arXiv preprint, Feburary 2014.
 * [4] Timo Mantere and Janne Koljonen. [Sudoku research page](http://lipas.uwasa.fi/~timan/sudoku/). 

QNF Code: Program that puts the Hamiltonian, for any finite-dimensional mechanical system, in classical (or quantum) normal form.
          There is a version that (v1) that words near a minimum and one that that works near a saddle (v2).
          This second version of the program also computes the rate over the saddle by assuming that the minimum is completely harmonic (no interactions).
          It is also possible to use both program versions together to compute the rate for any system precisely.

Adjustments made to the code include plot generation and all the specifics associated with that, as well as a quick fix to the v26 notebooks, that ensures the notebook runs for any even value of QNF order
(you will see "QNFOrd/2" in the code). AHO Modes was cloned from v26.2 just to have a separate notebook where one can test the effects of mode couplings.
# OpenBioSim Summary Talk

The [slides](slides/index.html) are [revealjs](https://revealjs.com) and can be viewed by opening `slides/index.html` in your browser.

They are designed to go with the demos in the `demo` directory

To run the presentation, make sure that [sire](https://sire.openbiosim.org) and 
[BioSimSpace](https://biosimspace.openbiosim.org) are installed, and are at least 
version `2023.3.0`. Activate the conda environment, then `cd` into the 
`demo` directory and run `jupyter lab`.

This should open in the same browser as your slides, so that you can easily switch
between them.

There are four demos:

* `demo/sire_demo/sire_demo.ipynb` - simple "show the features" overview of `sire`.
* `demo/sire_demo/information_demo.ipynb` - goes into how `sire` works, including 
  how information is stored, searched for and retrieved.
* `demo/bss_demo/bss_demo.ipynb` - simple "show the features" overview of `BioSimSpace`,
  focussing on setting up a minimisation simulation.
* `demo/bss_demo/bss_freenrg.ipynb` - goes more into how `BioSimSpace` works, 
  particularly focussed on setting up and running a relative free energy 
  calculation. This is sized so that it can mostly run live and can be analysed
  to give reasonably good results.

Note that all input files have been downloaded already, so this demo *should*
run without needing access to the internet...


---
layout: page
title: Photoionisation modelling with cloudy
---


<div class="media" markdown="1">
![A linear combination of different stellar populations with BPASS](/public/images/stellar_pops.png)
<div markdown="1">
I am producing a set of python routines that integrate with [cloudy](https://gitlab.nublado.org/cloudy/cloudy) to fit the code into a typical pythonic workspace. In combination with [BPASS](https://warwick.ac.uk/fac/sci/physics/research/astro/research/catalogues/bpass/), these routines can produce a custom ionising spectrum consisting of multiple stellar populations. Current [examples](https://github.com/ra-cooper/cloudy_tools) also show how to build a working cloudy input file with python.
</div>
</div>

{: .clear}

<div class="media reverse" markdown="1">
![An emission line ratio diagnostic vs gas-phase metallicity.](/public/images/o3hb.png)
<div markdown="1">
As well as producing cloudy ready inputs, I am developing routines that produce machine readable, python friendly outputs from cloudy results. These outputs overcome cloudy's typical format to work directlty with your favourite, ascii table reading, python packages. The most up-to-date progress on this work can be found [here](https://github.com/ra-cooper/cloudy_tools).
</div>
</div>

{: .clear}

---
---

### To do:
- Improve flexibility for filename handling.
- More user friendly translations of cloudy's output headers.
- Save information on non-varied parameters.
- Improve stellar population building routines.
- Package everything.




emergent design
===============
article - "what is software design"
traditional engineering not same as software engineering (stamping hours vs bits)
software - manufacturing is cheap \ toerance for error much more sever \ expensive to design
traditional - manufacturing is the most expensive

can't have emergent architecture, only design -> have as few architecture as possible

> the last responsible moment
accidental complexity vs essential complexity

implement 2x (second time will be great, no more unknown unknowns)
cyclomatic complexity / per lines of code
increased tech debt and complexity -> lower velocity
*demonstration trumps discussion*
* java ncss

sonar has a tech debt calculator
adding "generics" up front gives you technical debt until you start using it
you should _harvest_ idiomatic patterns, not create them up front
tool - ckgm
* blank lines area a call for help -- make a new method

accelerators
------------
* tests (wrong abstraction (list v set) -> accidental complexity example)

packman - use "pacman smell" like swarm (ant rout finding, but only pac leaves trace)

architects need to be part over time (not all up front design) \
only purpose of a spike is knowledge acquisition 

capture
-------
* ?
* write annotations

don't know what we don't know
``` buy the fanciest (in the way until you start using it - tech debt)```
putting some architecture items behind interface to make into a design element
```trying to predict the future leads to over-engineering```
```prefer pro/re-active to predictive (easy to replace)```
rotating pairs to address technical debt

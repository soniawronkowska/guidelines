---
sectionid: harmonyTablatureGrids
title: "Chord Tablature Grids"
version: "v3"
---

The **@pos** attribute on {% include link elem="chorddef" %}, the **@fing** and
**@fret** attributes on {% include link elem="chordmember" %}, and the {% include link elem="barre" %} element child of {% include link elem="chorddef" %} are provided in order to
create displayable and performable chord tablature grids for guitar and other fretted
string
instruments. The fret at which a finger should be placed is recorded in the **@fret**
attribute, while **@fing** indicates which finger, if any, should be used to play an
individual string. The values <span class="q">x</span> and <span class="q">o</span> are used to indicate muffled and open
strings, respectively.

The {% include link elem="chorddef" %} element may contain {% include link elem="barre" %}
sub-elements when a single finger is used to stop multiple strings. Here the **@fret**
attribute gives the fret position at which the barre should be created, while the
**@startid** and **@endid** attributes are used to indicate the {% include link elem="chordmember" %} elements on which the barre starts and finishes.

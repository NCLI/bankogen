bankogen
========

DIKU Banko-bankoplade-flyer-generator.  Fo' realyo.

**Vigtigt**: BANKOPLADERNE ER IKKE NUL-INDEKSEREDE!  Bare fordi.


Brug
====

Kør:

    ./gen_n_banko.sh $N

hvor N er antallet af bankoplader.  Bankopladerne vil blive gemt som
`gen/bankoplade_i.pdf` for alle 0 <= i < N og endeligt samlet som en N-sidet
pdf-fil `bankoplader.pdf`.


Afhængigheder
=============

* Inkscape
* pdfjam


Ophavsret
=========

Copyright (c) 2013, 2020 Niels G. W. Serup

Modificeret og ported til Python 3 af Nicholas Ipsen 2022

Licens: AGPLv3+

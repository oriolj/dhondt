##########################################################
Clase de Python para realizar el cálculo de la ley d'Hondt
##########################################################

:autor: Pedro-Juan Ferrer
:autor: Silvia Fuentes
:fecha: 2015-03-13
:version: v1.0

Realiza el cálculo de distribución de escaños dada un reparto de votos.

Por ejemplo::

    $ python dhondt.py 21 3.0 "{'a': 100, 'b': 200, 'c': 50}"

nos devuelve::

    <dhondt nseats:21 minper:3.0 candi:[('b', 200), ('a', 100), ('c', 50)]>
    <seats: [('b', 12), ('a', 6), ('c', 3)]>


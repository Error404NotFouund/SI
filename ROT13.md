# ROT13

ROT13 és una variant del Xifratge de Cèsar. Reemplaça cada lletra per la lletra situada a 13 posicions després d'aquesta. Si s'aplica aquest xifratge a un text ja encriptat amb ROT13, s'aconsegueix el text pla.

Exemple: A <-> N 

A **B C D E F G H I J  K  L  M  N**  O  P  Q  R  S  T  U  V  W  X  Y  Z

1 **2 3 4 5 6 7 8 9 10 11 12 13 14** 15 16 17 18 19 20 21 22 23 24 25 26


## LINUX
**Encriptar:**

~# echo "Aixo es una prova" | tr 'A-Za-z' 'N-ZA-Mn-za-m'

Nvkb rf han cebin

**Desencriptar:**

~# echo "Nvkb rf han cebin" | tr 'A-Za-z' 'N-ZA-Mn-za-m'

Aixo es una prova

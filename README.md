# Wordlist Hashcat

Esta una wordlist generada por hashcat proposito es para poder hacer fuerza bruta a directorios

Nombre de archivos estan de la siguiente manera:

```
 ? | Charset
 ===+=========
  l | abcdefghijklmnopqrstuvwxyz [a-z]
  u | ABCDEFGHIJKLMNOPQRSTUVWXYZ [A-Z]
  d | 0123456789                 [0-9]
  h | 0123456789abcdef           [0-9a-f]
  H | 0123456789ABCDEF           [0-9A-F]
  s |  !"#$%&'()*+,-./:;<=>?@[\]^_`{|}~
  a | ?l?u?d?s
  b | 0x00 - 0xff
```

segun la letra es el nombre del archivo por ejemplo: `l.txt` contiene solamente `[a-z]`.



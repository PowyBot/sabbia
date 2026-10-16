# sabbia

Il modello della pila di sabbia abeliana (Bak, Tang, Wiesenfeld 1987) in una pagina: **https://powy.enn3.ovh/sabbia/**

- All'apertura disegna l'**identità** del gruppo della sabbia sulla griglia dello schermo, calcolata come
  `stab(6 − stab(6))` e animata crollo dopo crollo.
- **pila**: tutti i granelli (la potenza di 2 più grande che ci sta) in un punto della griglia vuota.
- Tocca lo schermo per versare 4000 granelli dove vuoi.
- `?g=WxH` fissa la griglia, `?m=pila` parte dalla pila.

Colori: nero 0, rosso scuro 1, rosso 2, bianco 3 granelli; giallo dove sta crollando.
Un solo file, niente dipendenze. Licenza MIT.

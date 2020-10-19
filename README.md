# Anorectic Trunk

Tiny 400 bytes SID music (player+data) - compile with [64tass](https://sourceforge.net/projects/tass64/)

[Tune](https://csdb.dk/release/?id=186219) is used in [Sideborder 4K](https://csdb.dk/release/?id=186010)

```assembly
;
; Anorectic Trunk by freQvibez / Offence!
; last change: 2019-12-16
;
; player based upon the code
; of Laxity's "Repeat Me"
;
; so most of the credits should go to him!
;
; player limitations galore:
;   - release must be short, because
;     'off' sets note value to $00 (c7)
;   - arpeggio only for voice 2
;   - arpeggio can only go up to the next
;     octave
;   - no hard restart
;
```

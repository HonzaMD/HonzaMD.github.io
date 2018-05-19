---
layout: maincs
title: KRKAL 1 Nastavení DosBoxu
lang: cs
submenu: krkal1
---
# Nastavení DosBoxu

Zde uvádím doporučené změny v nastavení [DosBoxu](http://www.dosbox.com/) (verze 0.74).

output=ddraw  
aspect=TRUE  
scaler=normal2x  
cycles=fixed 10000  

Nastavení *output*, *aspect* a *scaler* umožní zvětšit a správně přeškálovat původní nízké rozlišení 320x200. Také si zvolte, zda chcete hrát v okně či ve fullscreenu, můžete upravit rozlišení.  
Nejdůležitější je nastavení *cycles*. Aby se Krkal plynule hýbal je potřeba nastavit fixní cykly v rozmezí 10000 až 15000.  
A nakonec upravte sekci *\[autoexec\]* a přidejte si tam příkaz *mount*. Například:

mount c d:\dosgames  
c:
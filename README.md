# ENGETO-uloha-2

Na základe druhej lekcie ENGETO kurzu som vytvoril dve jednoduché produktové karty pre čižmy na leto s vetraním + perpeetum mobile krhlu, čiže o hlúpostiach. Hlavne som si to chcel odznova spraviť bez tej nápovedy z lekcie, nech viem, že niečo také dokážem spraviť aj sám. 

Pardon za prvú nekvalitnú foto, no moc ma bavila, tak som ju tam dal. 

Chcel som dať tie produkty vedľa seba, ale cez display: flex mi to nejak nešlo spraviť, aby som tam mal celý content, ešte v tom plávam... EDIT 29.9: Zahliadol som niekde "float", na ten som úplne zabudol, tak som ho využil a už to vypadá jakš-takš, akurát teda jeden left a druhý right je fajn pri dvoch produktoch, pri viacerých budem v prdeli, musím doučiť :)

Rovnako mi robilo problém spraviť peknú border-radius (vždy mi to zkosí nejak divne), tak som ju tam ani nedával... 

Tiež som sa dlho hral s ".boots-ship-info-container", keďže mi nejak nešlo to spraviť responzívne, tak som to vyriešil cez padding v % a margin s fixnými px, čož však nie je ideálne v každom zobrazení...

Dlho som sa babral aj s "boots-discount-label" a Bestsellerom(Výpredajom) aby mi to responzívne ukazovalo stále border-radius 50% ako pekný kruh, čož mi moc nešlo, tak som to nakoniec vyriešil aspoň takto cez fixný width a height a k tomu som to napozicoval jak u containera, tak u textu vnútri, vôbec neviem, či je to dobre... EDIT: namiesto vloženia spanu do divu som si dal len span do inline-blocku a text vyrovnal cez padding fixný, ide to pekne.

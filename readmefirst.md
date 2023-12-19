### HVORDAN DETTE EKSEMPEL FUNGERER ###

Der er en ydre kasse kaldet "container outer-container",
som er det element med den røde kant. Indeni er der et element
kaldet "container inner-container", som er det element med den blå kant.
Indeni den er der er en grøn kasse kaldet "box".

For at lære mest af dette eksempel er det bedst, at du starter med at kigge på ".inner-container" i CSS-filen,
inden du begynder at pille ved ".outer-container".

Som I kan se, placerer boksen sig efter den nærmeste forælder, der ikke har "position: static;".
Dette er en lille, men **virkelig** vigtig detalje, som mange forklaringer på nettet og fra lærere desværre mangler,
og som kun skaber mere forvirring, end det gavner.


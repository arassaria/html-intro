### Fragen
- Wann `aside` innerhalb von `article`, wann außerhalb?
- Was kommt in `main` rein? Wie oft darf man `main` pro Seite verwenden?
- Wann ist `div` geeigneter als `section`?
- Wann verwendet man `b` und wann `strong`? Wann `i` und wann `em`?
- Wie baut man eine `figure` mit einem Bild und Text auf?
- Wofür steht `dl`, `dd` und `dt`
- Was sind 3 void Elemente, die du kennst?
- Wofür wird `small` verwendet?
- Was ist der Unterschied zwischen dem `img`- und dem `picture`-Element?
- Welche 5 `input`-types kennst du neben `<input type="text">`?
- Was macht man mit `select` und `option`?

## Anworten

1. `aside` kommt immer dann in den `article` wenn es Zusatzinformationen dazu bietet. Außerhalb eines `article` wird es benutzt um Zusatzinformationen zu seinem aktuellen Parent-Element zu geben.

2. In `main` kommt der Hauptinhalt der Seite rein. `main` darf nur einmal pro Dokument verwendet werden darf.

3. `div` keine konkrete Vorgabe für den Inhalt. Kann alles beinhalten. `section` sollte nicht als allgemeines Containerelement benutzt werden. Ein `section` Abschnitt sollte auch immer in der Gliederung des Dokumentes erscheinen.

4. `b` ist ein Tag für bold, keine Bedeutung. `strong` macht das Wort auch fett, wird vom Browser als wichtig eingestuft. 
`i` ist rein optisch für italic. `em` für Emphasis, hebt die Wichtigkeit des Wortes hervor.

5. `figure` wenn man ein Bild mit einem Text verbinden will. Dadurch lässt sich beides zusammen verschieben.

6. `dl` description list. 2 Elemente. Ein fettes `dt` description title und ein eingerücktes `dd` description description. 

7.  Void-Elemente sind Elemente, zwischen denen kein Text stehen kann. Also Tags, die kein Closing Tag benötigen. Wie bspw:
    `<img>`
    `<br>`
    `<hr>` 
    `<input>`
    `<meta>`

8. `small` wird für Randnotizen oder stil-ungebundene Elemente wie Copyright oder rechtliche Hinweise benutzt. Oder quasi auch für das "kleingedruckte".

9. `picture` wird benutzt wenn man responsive Web Development betreiben möchte, um ein `img` so einzubinden, dass der Browser für das entsprechende Gerät die beste Version des Bilders nehmen kann. Entsprechend enthält ein `picture` auch immer ein  `img` und mehrere `sources`.

10. `<input type="email">`
    `<input type="number">`
    `<input type="password">`
    `<input type="tel">`
    `<input type="url">`

    for more go to <a href="https://developer.mozilla.org/en-US/docs/Web/HTML/Element/input">MDN Network</a>

11. `select` wird für die Erstellung einer Drop-Down-Menüs in `html` verwendet. Mit `option` können dann Auswahlmöglichkeiten in dieses Drop-Down-Menü hinzugefügt werden.
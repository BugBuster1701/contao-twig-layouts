# Contao Twig-Layouts
Beispiele von Page Layouts (Varianten) für Twig-Layout mit Slots.

## Verzeichnis contao-demo
Speziell für Migration von Contao 4.13 nach 5.7 und Slots gedacht. (die auf die Demo basieren)

Im mitgelieferten Page Layout von Contao 5.7 sind einige DIV Tags nicht mehr vorhanden.
Um nun nicht das CSS anpassen zu müssen werden hier die fehlenden DIVs und IDs wieder eingefügt.

Außerdem werden notwendige JS und CSS Dateien eingebunden für Contao Componenten die verwendet werden.

Die TWIG Layout Varianten liegen im Verzeichnis /templates/page/layout, angelegt durch das Template Studio.

Siehe: [Readme](contao-demo/templates/page/layout/README.md)

## Verzeichnis contao-layout-3x3
Layout Header-Main-Left-Right-Footer

Es bildet das 3-Zeilen - 3 Spalten Layout nach als statisches Layout mit fester Breite und Ausrichtung.
Dazu benutzt es, wie im Standard Layout, zusätzliche DIV Tags (wrapper, container, inside).

Siehe: [Readme](contao-layout-3x3/layout-3x3.html.md)

## Verzeichnis contao-layout-3x3-grid-areas
Layout Header-Main-Left-Right-Footer

Es bildet das 3-Zeilen - 3 Spalten Layout nach als statisches Layout mit fester Breite und Ausrichtung.

Der Unterschied zu contao-layout-3x3 ist, es kommt ohne die zusätzlichen DIV Tags aus (wrapper, container, inside).
Dazu benutzt es grid-area Definitionen und arbeitet mit grid-template-columns, grid-template-rows usw.

Siehe: [Readme](contao-layout-3x3-grid-areas/layout-3x3-grid-areas.html.md)


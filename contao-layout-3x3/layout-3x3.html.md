# Layout Header-Main-Left-Right-Footer
Es bildet das 3-Zeilen - 3 Spalten Layout nach als statisches Layout mit fester Breite und Ausrichtung.

Die "layout.css" stammt von Contao und ist auf GitHub im Verzeichnis contao-css zu finden.

Im Twig sind einige Zeilen auskommentiert. Wer was davon braucht kann das dann aktivieren, einfach `{#` und `#}` entfernen.

**Hinweis:** Noch nicht getestet und auch noch nicht ganz fertig.
```
<html>
<head>

    <style nonce="caoaZySVGzitgueWfpUXBWFQ">
        #wrapper {
            width: 1024px;
            margin: 0 auto
        }

        #header {
            height: 100px
        }

        #left {
            width: 200px;
            right: 200px
        }

        #right {
            width: 150px
        }

        #container {
            padding-left: 200px;
            padding-right: 150px
        }

        #footer {
            height: 50px
        }
    </style>

    <link rel="stylesheet" href="layout.css">
    <link rel="stylesheet" href="your_own.css">

</head>

<body id="top">

    <div id="wrapper">

        <header id="header">
            <div class="inside">
            </div>
        </header>

        <div id="container">
            <main id="main">
                <div class="inside">
                </div>
            </main>

            <aside id="left">
                <div class="inside">
                </div>
            </aside>

            <aside id="right">
                <div class="inside">
                </div>
            </aside>
        </div>

        <footer id="footer">
            <div class="inside">
            </div>
        </footer>
    </div>

</body>

</html>
```
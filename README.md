Markdown
# E-Commerce Logistik- und Kundenzufriedenheitsanalyse (Magist)

## Projektübersicht
Dieses Projekt untersucht für das E-Commerce-Unternehmen Magist (Brasilien), inwiefern logistische Probleme (wie Lieferverzögerungen) die Kundenzufriedenheit negativ beeinflussen und als Brandbeschleuniger für schlechte Bewertungen wirken. Mithilfe von Tableau wurden Lieferstatus und Review-Scores analysiert, um Optimierungspotenziale aufzuzeigen.

## Datensatz & Quellen
- **Quelle:** Magist (Brazilian E-Commerce Public Dataset)
- **Kern-Tabellen:** `orders`, `order_reviews`, `order_items`
- **Kern-Metriken:** Lieferpünktlichkeit (Vergleich von tatsächlichem und geschätztem Lieferdatum), Review-Scores (1 bis 5 Sterne), Produktkategorien und Preissegmente.

## Wichtigste Erkenntnisse und Ergebnisse
- **Pünktlichkeit schützt, ist aber kein Garant:** Über 82 % der pünktlich gelieferten Bestellungen erhalten 4 oder 5 Sterne. Dennoch vergeben rund 6,7 % trotz pünktlicher Lieferung 1 Stern (Hinweis auf Produkt- oder Servicefehler).
- **Logistik als Brandbeschleuniger:** Fast die Hälfte aller verspäteten Lieferungen (46,67 %) führt sofort zu einer harten 1-Sterne-Bewertung.
- **Handlungsempfehlung für Eniac:** Neben schnellen Logistikpartnern ist eine strenge Qualitätskontrolle der Produkte essenziell, um negative Bewertungen drastisch zu reduzieren.

## Verwendete Technologien
- **Tool:** Tableau Desktop (für Datenanalyse und Visualisierungen)
- **Methoden:** Berechnete Felder (`lieferstatus`), Prozentuale Tabellenberechnungen (*Percent of Total*), Kreuztabellen und Balkendiagramme.

## Persönliche Erkenntnisse & Herausforderungen (Reflektion)
- **Herausforderung:** Eine der größten Hürden in diesem Projekt war es, komplexe logistische Verknüpfungen (wie die Differenz zwischen geschätztem und tatsächlichem Lieferdatum) komplett ohne SQL, rein über native Tableau-Funktionen und berechnete Felder (`lieferstatus`), abzubilden. 
- **Lösung & Wachstum:** Durch das gezielte Arbeiten mit Tabellenberechnungen (*Percent of Total*) und dem sauberen Strukturieren von Kreuztabellen habe ich gelernt, wie man Daten visuell so aufbereitet, dass geschäftliche Kernprobleme (wie der Zusammenhang von Verspätung und 1-Sterne-Reviews) sofort für das Management sichtbar werden. Dieses Projekt hat meinen Blick dafür geschärft, Datenanalysen immer aus der Perspektive des Geschäftsnutzens zu betrachten.

## Wie man dieses Projekt nutzt
1. **Tableau-Arbeitsmappe:** Öffnen Sie die im Repository hinterlegte Tableau-Datei, um die interaktiven Visualisierungen zu sehen.
2. **Berechnetes Feld:** Prüfen Sie das Feld `lieferstatus` zur Unterscheidung von pünktlichen und verspäteten Lieferungen.
3. **Präsentation:** Die vollständige Projektpräsentation finden Sie als PDF im Repository.

## Kontakt
- **Name:** Walter Edgard Correa Román
- **GitHub:** [Walcor2306](https://github.com/Walcor2306)

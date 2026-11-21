# Armored Canyon 2

Wersja 2.0 (numer widać w menu i w górnym pasku gry).

Izometryczna gra artyleryjska z czołgami, działająca w przeglądarce. Cała gra to jeden plik `index.html`, bez instalacji i bez serwera.

## Jak grać

Ustaw kierunek wieży, kąt lufy i moc, weź poprawkę na wiatr i trafiaj przeciwnika. Wybuchy kopią leje w terenie i w drodze, a czołg, któremu zabierzesz grunt spod gąsienic, spada i traci życie.

- **Tryby:** Gracz vs Komputer albo 2 graczy na jednym ekranie
- **Pole walki:** siatka heksagonalna, 4 ruchy na turę
- **Bronie:** pocisk (bez limitu), ciężki (×3), kasetowy (×2)
- **Mapa:** losowa w każdej rundzie, do wyboru mała, średnia, duża albo losowa wielkość
- **Klimaty:** umiarkowany, zima (śnieg na drzewach, losowo zamarznięte stawy), Antarktyda (lód i kry), pustynia, skały z rzekami, góry z gęstymi lasami i rwącą rzeką
- **Pogoda:** utrzymuje się przez 3–5 rund, potem się zmienia – deszcz, burza z piorunami, mgła, śnieżyca, zamieć, upał, burza piaskowa; silniejszy i porywisty wiatr oraz gorsza widoczność toru lotu
- **Mieszkańcy:** od czasu do czasu z krawędzi mapy nadciąga grupka (3–6 sztuk). Kolejna pojawia się dopiero 2–3 rundy po tym, jak poprzednia zniknie z mapy. Są to dwie wrogie sobie frakcje pasujące do klimatu (wilki oraz yeti z bałwanami zimą, pingwiny-komandosi i lodowe golemy na Antarktydzie, skorpiony i czerwie na pustyni, kryształowe kraby i sępy w skałach, niedźwiedzie i leśne enty w górach, robo-pająki i dzikie drony w klimacie umiarkowanym). Atakują oba czołgi i walczą między sobą; da się je trafiać pociskami
- **Złoto i przekupstwo:** złoto za każdą turę, za trafienia przeciwnika i za zabitych mieszkańców. Klawisz B lub przycisk „Przekup” – za złoto albo 1 ciężki + 1 kasetowy pocisk frakcja przez 3 rundy nie atakuje ciebie i rzuca się na przeciwnika. Komputer też potrafi przekupywać
- **Woda:** rwący nurt porywa czołg, który wjedzie do rzeki (może go wynieść za mapę), lód pęka od wybuchów
- **Garaż:** w menu każdy gracz wybiera model czołgu (lekki, średni, ciężki, superciężki), jeden z 9 kolorów i oznaczenie na wieży (numer, gwiazda, krzyż, szewron, tarcza albo brak). Wybór zapamiętuje przeglądarka
- **Grafika:** trójwymiarowa low-poly (WebGL, three.js): cienie liczone na bieżąco, płynny obrót i zbliżenie kamery, czołgi jako modele 3D z dowódcą we włazie, czołgi z dowódcą we włazie, kolorowe miasteczka (domy z dachówką i kominem, sklepy z markizami, kamienice, fabryki z kominem), pikselowi mieszkańcy we wszystkich klimatach
- **Otoczenie:** budynki z drobnych klocków rozpadają się piksel po pikselu w miejscu trafienia, a niepodparte części osuwają się w dół; drzewa łamią się i padają

## Sterowanie

| Klawisz | Akcja |
|---|---|
| ← → | obrót wieży (z Shift wolniej) |
| ↑ ↓ | kąt lufy |
| Z / X | moc strzału (albo Shift + kółko myszy) |
| kółko myszy, + / − | zbliżenie i oddalenie (0 wraca do całej mapy) |
| prawy przycisk + ruch | przesuwanie widoku |
| Spacja | ogień |
| Q W E A S D | jazda o jeden heks w 6 kierunkach |
| Klik | w sąsiedni heks: jazda; w dalszy heks: obrót wieży |
| R / Shift+R | obrót kamery o 90° w prawo / w lewo |
| wciśnięta rolka + ruch myszy | płynny obrót kamery o dowolny kąt |
| 1 / 2 / 3 lub Tab | wybór broni |
| F | pełny ekran |
| B | przekupienie frakcji mieszkańców |
| M | dźwięk wł./wył. |
| Esc | menu |

Na telefonie i tablecie działa dotyk i przyciski pod mapą; dwa palce przybliżają, a przeciągnięcie palcem przesuwa widok.

## Uruchomienie lokalnie

Grafika 3D wczytuje bibliotekę three.js z cdnjs, więc za pierwszym razem potrzebny jest internet. Bez niej gra przełącza się na starszą grafikę 2D.


Pobierz `index.html` i otwórz go w przeglądarce (Chrome, Edge, Firefox, Safari).

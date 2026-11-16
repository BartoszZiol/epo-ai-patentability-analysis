# Analiza prawna: Zdolność patentowa oprogramowania i sztucznej inteligencji w Europie


*Art. 52 EPC \| metoda COMVIK \| AI \| sprawa T 2401/22*

| **AUTOR** Bartosz Ziółkowski                      | **DATA** 16 listopada 2026 r.     |
|---------------------------------------------------|-----------------------------------|
| **PODSTAWA** Europejska konwencja patentowa (EPC) | **CEL** Analiza prawa patentowego |

# Streszczenie

Program komputerowy lub rozwiązanie wykorzystujące AI może zostać opatentowane w Europie, ale musi spełnić wymagania EPC. Najważniejsze jest wykazanie, że wynalazek rozwiązuje konkretny problem techniczny. Samo zastosowanie komputera, nowego algorytmu albo sieci neuronowej nie wystarcza do wykazania poziomu wynalazczego.[^1]

Decyzja T 2401/22 dotycząca rozwiązania firmy SAP pokazuje tę różnicę. Zastosowano tam model AI do oceny ważności słów w dokumentach, lecz Izba Odwoławcza nie dopatrzyła się nieoczywistego wkładu technicznego. Z tego powodu odwołanie zostało oddalone.[^2]

# 1. Kiedy oprogramowanie może być wynalazkiem?

Zgodnie z art. 52 EPC patent można uzyskać na wynalazek, który jest nowy, ma poziom wynalazczy i nadaje się do przemysłowego stosowania. Programy komputerowe i metody matematyczne są wyłączone z patentowania tylko „jako takie”. Nie oznacza to więc zakazu patentowania wszystkich wynalazków wykorzystujących oprogramowanie.

Nowość i poziom wynalazczy to odrębne wymagania. Rozwiązanie jest nowe, gdy nie zostało wcześniej ujawnione w stanie techniki. Przy ocenie poziomu wynalazczego sprawdza się natomiast, czy dla specjalisty wynikało ono w sposób oczywisty z wcześniejszej wiedzy. Dlatego nawet nowa metoda obliczeniowa nie musi nadawać się do opatentowania. Każdy przypadek wymaga porównania z konkretnym stanem techniki.[^3]

Trzeba odróżnić dwa pytania. Pierwsze: czy rozwiązanie ma charakter techniczny? Metoda wykorzystująca komputer zwykle spełnia ten wstępny warunek. Drugie: czy nowe cechy rozwiązania wnoszą nieoczywisty wkład techniczny? To drugie pytanie decyduje o poziomie wynalazczym. W odniesieniu do programu komputerowego ocenianego jako takiego EPO bada też, czy jego wykonanie powoduje dalszy efekt techniczny, wykraczający poza zwykłą pracę sprzętu.[^4]

Przykład: program, który wyłącznie automatycznie oblicza wysokość rabatu, realizuje przede wszystkim regułę handlową. Inaczej można ocenić rozwiązanie, którego specyficzne instrukcje sterują maszyną lub wyraźnie poprawiają techniczne działanie pamięci komputera. Nie oznacza to jednak automatycznego przyznania patentu: także w takim przypadku trzeba wykazać nowość i nieoczywistość konkretnej implementacji.[^5]

# 2. Metoda COMVIK – prosty sposób oceny

W sprawie T 641/00 (COMVIK) analizowano system telefonii GSM pozwalający rozdzielać koszty rozmów. Sam pomysł podziału opłat miał charakter organizacyjny i finansowy. Nie dawał więc podstawy do uznania poziomu wynalazczego. Liczyły się tylko te cechy, które wnosiły wkład techniczny.[^6]

W praktyce metodę COMVIK można przedstawić w czterech krokach:

**Krok 1.** Ustalić, jakie cechy wynalazku różnią się od znanych rozwiązań.

**Krok 2.** Sprawdzić, które z tych cech rzeczywiście rozwiązują problem techniczny.

**Krok 3.** Określić ten problem, np. ograniczenie zużycia pamięci lub poprawę pracy czujnika.

**Krok 4.** Ocenić, czy zaproponowane rozwiązanie byłoby oczywiste dla specjalisty.

Cel biznesowy lub językowy może być częścią założeń projektu, ale sam nie uzasadnia poziomu wynalazczego. Cechy pozornie nietechniczne mogą jednak mieć znaczenie, jeśli w połączeniu z innymi cechami powodują konkretny efekt techniczny.[^7]

Ważny szczegół: punkt wyjścia oceny stanowi odpowiednie wcześniejsze rozwiązanie techniczne. Dopiero po jego wskazaniu można ustalić cechy odróżniające oraz wynikający z nich obiektywny problem techniczny. Wymagania nietechniczne, np. sposób naliczania opłat, mogą zostać potraktowane jako założenia przekazane specjaliście; ich pomysłowość sama nie zapewnia poziomu wynalazczego.[^8]

# 3. Sztuczna inteligencja – co może mieć charakter techniczny?

EPO traktuje modele AI i uczenia maszynowego jako metody matematyczne, gdy ocenia je w oderwaniu od zastosowania. Mogą jednak wnosić wkład techniczny, jeśli służą konkretnemu zadaniu technicznemu albo są szczególnie dostosowane do działania sprzętu komputerowego.[^9]

**Przykłady zastosowań technicznych:** analiza sygnału EKG w celu wykrywania nieprawidłowego rytmu serca; przetwarzanie obrazu na poziomie pikseli; szacowanie genotypu na podstawie wyników analizy DNA.

**Przykłady celów nietechnicznych:** sortowanie artykułów wyłącznie według znaczenia tekstu; przewidywanie preferencji zakupowych; ustalanie, które informacje użytkownik uważa za najciekawsze.

O rozróżnieniu nie decyduje sama nazwa dziedziny. System przetwarzający dane biologiczne również może realizować wyłącznie abstrakcyjne obliczenia. Z drugiej strony sieć neuronowa służąca do analizy rzeczywistych pomiarów EKG może być częścią technicznego rozwiązania. Trzeba sprawdzić, jaki efekt wynika z zastrzeganych cech, a nie jedynie z rodzaju wejściowych danych.[^10]

Techniczny efekt może też wynikać ze sposobu wykonania obliczeń, np. z konkretnego podziału pracy między procesor CPU i układ GPU. Nie wystarczy jednak ogólna deklaracja, że algorytm działa szybciej. Trzeba wskazać, które cechy powodują poprawę i jak wpływają na działanie urządzenia.[^11]

Podobnie sama wyższa trafność klasyfikacji nie zawsze wystarcza. Jeżeli AI jedynie lepiej ocenia wartość tekstu dla czytelnika, korzyść może mieć charakter nietechniczny. Jeżeli natomiast określony model wykrywa właściwości sygnału z urządzenia pomiarowego albo steruje procesem technicznym, jego wynik może być elementem wkładu technicznego. Nadal konieczne jest ustalenie, czy rozwiązanie było nieoczywiste.[^12]

Opis wynalazku musi umożliwiać jego odtworzenie przez specjalistę. Gdy wynik zależy od treningu modelu, należy ujawnić odpowiednio ważne cechy danych i procesu uczenia. EPO co do zasady nie wymaga udostępnienia całego, konkretnego zbioru danych treningowych.[^13]

# 4. Studium przypadku: T 2401/22 (SAP)

## Co próbowała opatentować firma SAP?

Zgłoszenie EP 18204942.9 dotyczyło oceny ważności słów w dokumentach. System analizował dokument główny i drugi dokument zawierający do niego odnośnik. Wykorzystywał sieć neuronową z elementami kodera, dekodera i mechanizmu uwagi, aby obliczyć wagi słów i użyć ich przy wyszukiwaniu dokumentów.[^14]

## Co rzeczywiście różniło rozwiązanie od wcześniejszych metod?

Izba przyjęła jako punkt wyjścia znany system wyszukiwania dokumentów na podstawie przypisanych im wartości ważności słów. Nowość przedstawianych rozwiązań dotyczyła między innymi wykorzystania drugiego dokumentu z odnośnikiem do pierwszego oraz sposobu obliczania wag za pomocą architektury koder–dekoder i mechanizmu uwagi. Kluczowe było zatem nie samo istnienie wyszukiwarki, ale znaczenie tych dodatkowych cech dla jej technicznego działania.[^15]

## Jakie były argumenty zgłaszającego?

SAP twierdził, że metoda poprawia trafność wyszukiwania, uczy się zależności z danych i wykorzystuje techniczne mechanizmy wyszukiwarki. W dodatkowym zestawie zastrzeżeń powoływał się również na możliwą oszczędność zasobów obliczeniowych.

## Dlaczego EPO odmówiło?

Izba uznała, że oceniane nowe cechy dotyczyły przede wszystkim znaczenia słów i zainteresowań użytkowników, a nie usprawnienia technicznego działania wyszukiwarki. Samo użycie zaawansowanej sieci neuronowej nie zmieniało tej oceny. Również argument o mniejszym zużyciu zasobów nie został przyjęty, ponieważ zastrzeżenia nie wskazywały dostatecznie cech niezbędnych do osiągnięcia tej korzyści. Oba końcowe zestawy zastrzeżeń uznano za pozbawione poziomu wynalazczego; odwołanie oddalono.[^16]

W dodatkowym zestawie zastrzeżeń SAP dokładniej określił sposób wyznaczania wektorów kontekstowych. Argumentował, że może to zmniejszyć koszty obliczeń. Izba nie przyjęła tego wyjaśnienia: zastrzeżenia nie definiowały wszystkich warunków koniecznych do uzyskania wskazywanej oszczędności. Jest to przykład sytuacji, w której powołanie się na wydajność wymaga precyzyjnego opisania mechanizmu technicznego.[^17]

Wniosek ze sprawy: nie wystarczy powiedzieć, że AI lepiej ocenia dokumenty albo wykorzystuje nowoczesną architekturę. Trzeba wykazać, co konkretnie poprawia się w technicznym działaniu systemu. Nie oznacza to, że AI lub wyszukiwarki są z zasady wyłączone z patentowania.

# 5. Przykład praktyczny: AI w urządzeniu medycznym

Rozważmy hipotetyczny czujnik noszony na nadgarstku, który analizuje sygnał fizjologiczny przy użyciu sieci neuronowej. Wynalazca twierdzi, że nowy sposób wykonywania obliczeń zmniejsza pobór energii urządzenia bez pogorszenia jakości wykrywania zakłóceń sygnału. Jest to tylko przykład metody analizy, a nie ocena patentowalności rzeczywistego zgłoszenia.

**Problem techniczny:** ograniczenie zużycia energii podczas lokalnej analizy sygnału przez urządzenie zasilane baterią.

**Możliwa cecha techniczna:** szczególny sposób rozdzielania obliczeń, zarządzania pamięcią lub wykonywania wnioskowania w układzie urządzenia — opisany na tyle dokładnie, by wyjaśnić jego działanie.

**Potrzebne uzasadnienie:** porównanie z wcześniejszą metodą przy zbliżonych warunkach pomiaru; np. zużycie energii, czas odpowiedzi oraz jakość analizy sygnału.

Takie informacje mogą pomóc zidentyfikować techniczny wkład i sformułować odpowiednie zastrzeżenia. Nadal trzeba jednak przeprowadzić badanie stanu techniki i ocenić, czy konkretne rozwiązanie byłoby oczywiste. Nie wystarczy ogólny zapis, że „AI oszczędza energię”.[^18]

# 6. Co powinien zrobić zgłaszający?

**1. Nazwać problem techniczny.** Przykładowo: nadmierne zużycie pamięci, opóźnienie działania czujnika lub niewydajne wykorzystanie procesora.

**2. Opisać rozwiązanie w zastrzeżeniach.** Wskazać te cechy urządzenia, oprogramowania lub sposobu przetwarzania, które faktycznie powodują deklarowaną poprawę.

**3. Przygotować dowody.** Porównać rozwiązanie ze stanem techniki, np. pod względem czasu działania, pamięci albo zużycia energii. Sam test nie gwarantuje patentu.

**4. Odpowiednio ujawnić wynalazek.** Podać informacje potrzebne do jego odtworzenia, również dotyczące danych i treningu modelu, jeśli są istotne dla wyniku.

**5. Zadbać o treść już przy zgłoszeniu.** Opisać dostępne warianty i efekty techniczne. Późniejsze dowody mogą wspierać efekt związany z pierwotnym ujawnieniem, lecz nie pozwalają dodać nowej treści do zgłoszenia.[^19]

Przed zgłoszeniem warto też zadbać o poufność rozwiązania. Publiczne opublikowanie szczegółów w repozytorium lub podczas prezentacji może mieć znaczenie dla nowości. Gdy wynalazek ma kilka wariantów wykonania, dobrze opisać je w zgłoszeniu od początku, ponieważ późniejsze zmiany nie mogą wykraczać poza pierwotnie ujawnioną treść.[^20]

Jeżeli urząd po zgłoszeniu zakwestionuje efekt techniczny, dodatkowe wyniki testów mogą w określonych warunkach posłużyć jako dowód. Zgodnie z G 2/21 nie można ich odrzucić tylko dlatego, że przedstawiono je później. Efekt musi jednak pozostawać objęty nauczaniem technicznym pierwotnego zgłoszenia i dotyczyć tego samego ujawnionego wynalazku.[^21]

# Podsumowanie

W Europie można ubiegać się o patent na wynalazek wykorzystujący oprogramowanie lub AI. O wyniku nie decyduje jednak nowoczesność algorytmu, lecz to, czy zgłoszenie wskazuje nieoczywiste rozwiązanie problemu technicznego. COMVIK pomaga odróżnić cechy techniczne od celów biznesowych lub informacyjnych, a T 2401/22 pokazuje, jak ważne jest precyzyjne opisanie rzeczywistego efektu technicznego.

# Najważniejsze źródła

**\[A\] Art. 52 EPC.** wynalazki podlegające opatentowaniu. [<u>Otwórz źródło</u>](https://www.epo.org/en/legal/epc/2020/a52.html)

**\[B\] Art. 56 EPC.** poziom wynalazczy. [<u>Otwórz źródło</u>](https://www.epo.org/en/legal/epc/2020/a56.html)

**\[C\] Wytyczne EPO (2026), G-II, 3.3.1.** AI i uczenie maszynowe. [<u>Otwórz źródło</u>](https://www.epo.org/en/legal/guidelines-epc/2026/g_ii_3_3_1.html)

**\[D\] Wytyczne EPO (2026), G-VII, 5.4.** ocena cech technicznych i nietechnicznych. [<u>Otwórz źródło</u>](https://www.epo.org/en/legal/guidelines-epc/2026/g_vii_5_4.html)

**\[E\] Decyzja T 641/00 (COMVIK).** 26 września 2002 r.; Dz. Urz. EPO 2003, s. 352. [<u>Otwórz źródło</u>](https://www.epo.org/en/legal/official-journal/2003/07/p352)

**\[F\] Decyzja T 2401/22 (SAP).** 23 września 2024 r. [<u>Otwórz źródło</u>](https://www.epo.org/en/boards-of-appeal/decisions/t222401eu1)

**\[G\] Decyzja G 2/21.** 23 marca 2023 r.; Dz. Urz. EPO 2023, A85. [<u>Otwórz źródło</u>](https://www.epo.org/en/legal/official-journal/2023/09/a85)

**Charakter opracowania:** przykładowa analiza edukacyjna, nie indywidualna porada prawna.

[^1]: Art. 52 i 56 EPC; Wytyczne EPO z kwietnia 2026 r., G-II, 3.3.1 i G-VII, 5.4.

[^2]: Decyzja T 2401/22 z 23 września 2024 r., pkt 3.6–3.11, 5.4 i sentencja.

[^3]: Art. 54 i 56 EPC; Wytyczne EPO (2026), G-VII, 5.4.

[^4]: Wytyczne EPO (2026), G-II, 2 i G-II, 3.6; art. 52 i 56 EPC.

[^5]: Wytyczne EPO (2026), G-II, 3.6 i G-VII, 5.4.

[^6]: T 641/00, 26 września 2002 r., tezy I–II i pkt 5–8 uzasadnienia.

[^7]: Wytyczne EPO (2026), G-VII, 5.4 i 5.4.1.

[^8]: T 641/00, teza II; Wytyczne EPO (2026), G-VII, 5.4, kroki (i)–(iii).

[^9]: Wytyczne EPO (2026), G-II, 3.3 i 3.3.1.

[^10]: Wytyczne EPO (2026), G-II, 3.3 i 3.3.1.

[^11]: Wytyczne EPO (2026), G-II, 3.3, część dotycząca zastosowań i szczególnych implementacji technicznych.

[^12]: Wytyczne EPO (2026), G-II, 3.3.1 oraz G-VII, 5.4.

[^13]: Art. 83 EPC; Wytyczne EPO (2026), G-II, 3.3.1 i F-III, 3.

[^14]: T 2401/22, pkt 1–1.4 i 3.4 uzasadnienia; treść zastrzeżenia 1 w części opisującej stan sprawy.

[^15]: T 2401/22, pkt 3.2–3.4 uzasadnienia.

[^16]: T 2401/22, pkt 3.5–3.11 i 5.2–6 uzasadnienia oraz sentencja.

[^17]: T 2401/22, pkt 5.1–5.4 uzasadnienia.

[^18]: Wytyczne EPO (2026), G-II, 3.3 i G-VII, 5.4.1.

[^19]: Art. 83, 84 i 123(2) EPC; decyzja G 2/21, tezy I–II; Wytyczne EPO (2026), F-IV, 3.9.1 i G-VII, 5.4.

[^20]: Art. 54 ust. 2 i 123 ust. 2 EPC.

[^21]: Decyzja G 2/21, tezy I–II; art. 123 ust. 2 EPC.
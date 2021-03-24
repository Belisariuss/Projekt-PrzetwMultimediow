# Projekt-PrzetwMultimediow
Projekt ma na celu stworzenie aplikacji multimedialnej. Podstawowym założeniem jest możliwość mieszania kilku utworów.
Tworzony jest poprzez stosowanie metodologii Agile oraz rozwijany poprzez FDD (Feature Driven Development).
Framework JUCE umożliwia tworzenie oprogramowania niezależnie od platformy developerskiej (do wyboru jest m.in. Xcode oraz VS).
Dzięki temu unikamy niepotrzebnych konfliktów kompatybilności w tworzeniu oprogramowania. Sam framework dostosowuje poprzez cmake oraz interfejs projucer odpowiednie wartości.
Testy jednostkowe oraz integracyjne będą przeprowadzane wraz z każdym nowo dodanym "featur'em". Umożliwi to w szybki sposób znajdowanie błędów logicznych w oprogramowaniu.
Metodyka TDD(Test Driven Development) w znaczący sposób pomoże w poprawnym rozwoju oprogramowania. Każdy nowy Feature dodawany do Core projektu będzie sprawdzany poprzez testy integracyjne. Ewentualnie przy pomocy Robot Framework możliwe będzie częściowe  stosowanie acceptance test driven development (ATDD), behavior driven development (BDD) and robotic process automation (RPA).
Przy pomocy infrastruktury/designu githuba jesteśmy w stanie w łatwy/prosty sposób rozwijać Projekt stosując ww. metodykę wytwarzania oprogramowania. Analiza postępów następuje poprzez analizę sekcji 'projects' oraz postępów milestone'ów.
(feature opcjonalny) Dzięki bibliotece BOOST języka c++ jesteśmy w stanie wykorzystać framework dolby.io korzystając z api przystosowanego do Pythona. Umożliwi to udoskonalenie dźwięku tworzonego przez program, poprzez redukcję m.in szumów oraz niepożądanych zakłóceń. Działałoby to w sposób proceduralny, niezależny od naszej aplikacji i wywoływany po utworzeniu pliku audio na dysku.

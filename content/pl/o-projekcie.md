+++
title = "O projekcie"
+++

Program pozwala na wcielenie się w rolę maszynisty najpopularniejszych pojazdów szynowych obecnych na polskiej sieci kolejowej. Obecnie użytkownik ma możliwość sterowania ponad 40 modelami lokomotyw elektrycznych i spalinowych, kilkoma elektrycznymi zespołami trakcyjnymi. Dostępne są również drezyny i szynobus, a w bazie pojazdów znajduje się kilkaset wagonów pasażerskich i towarowych. Ponadto zbiór pojazdów dopełniają modele, które są możliwe do sterowania jedynie przez komputer.

Najnowsze wydanie **MaSzyny** to zbiór ponad 150 scenariuszy opracowanych na kilkunastu dostępnych sceneriach, w tym na jednej scenerii realistycznej (linie kolejowe 61 i 144, odcinek Ozimek - Częstochowa). Scenerie przedstawiają różne typy spotykanych w Polsce linii kolejowych. **MaSzyna** daje możliwość jazdy po liniach magistralnych z prędkościami 120-160 km/h czy klimatycznych lokalnych szlakach kolejowych. Dostępne są również scenerie "manewrowe" gdzie zadaniem użytkownika jest obsługa stacji rozrządowej lub bocznicy kolejowej w zakładzie przemysłowym. Stopniowo wprowadzana jest również możliwość wyboru pory roku podczas symulacji.

{{< youtube BqmuKr4MYm8 >}}

#### Zalecane wymagania sprzętowe:
* **System operacyjny**: Microsoft Windows / Linux
* **Procesor**: Intel Core 2 Duo E4700 2.6 GHz / AMD Apu A4-6300 Dual-Core
* **Pamięć RAM**: 16 GB
* **Karta graficzna**: nVidia GeForce GT 730 v2 / Radeon G7 250 v2 **(koniecznie minimum 2 GB pamięci vRAM)**
* **Miejsce na dysku**: ok. 40 GB
* **Kontrolery**: mysz, klawiatura z **wydzieloną sekcją numeryczną**

Wymagania sprzętowe i programowe do uruchomienia symulatora wzrosły względem poprzednich wersji. Ze względu na rozdział pliku exe na wersje x86 i x64 należy zwrócić szczególną uwagę na zgodność poniższych bibliotek ze swoim systemem operacyjnym i używanym plikiem EXE.

Niekiedy może być potrzeba instalacji w systemie pakietu podstawowego Python 2.7.14, zwłaszcza przy systemach x64.
Wskazane jest posiadanie ponad 4 GB pamięci RAM i wielowątkowego procesora. Mała ilość pamięci może nie pozwolić uruchomić większych scenerii bez zmniejszenia rozmiaru tekstur (maxtexturesize w pliku eu07.ini), a brak wolnego wątku procesora może drastycznie zmniejszyć wydajność w lokomotywach z komputerem pokładowym.

Wydanie symulatora planowane na połowę roku 2025 wprowadzi nowy renderer, wymagający karty graficznej obsługującej OpenGL 3+. Obecny renderer będzie dostępny dla użytkowników ze starszym sprzętem, ale jeśli rozważacie zakup nowego komputera, to teraz jest dobry moment, by móc cieszyć się pełnią nowych efektów graficznych w przyszłości.

+++
#### Początki
Pionierem **MaSzyny** jest **Marcin Woźniak**, który latem 2001 r. przedstawił projekt symulatora, częściowo korespondujący z innym programem tego typu - *Mechanik EN57*. [Tutaj](//eu07.pl/jeszczejedensymulatorek/) zamieściliśmy kopię tematu, gdzie przedstawiona była pierwsza wersja Symulatora. Po tym wydarzeniu kilka osób przyłączyło się do pomocy, w tym **Maciej Czapkiewicz**, który stworzył główną fizykę MaSzyny. Z faktu, że jedna z zasłużonych osób tworzących w tym czasie eksploatowała lokomotywę o numerze 424, aplikacja przyjęła nazwę MaSzyna EU07-424. W związku z powstawaniem modeli nowych pojazdów, które aplikacja obsługuje, zmianie uległo Logo oraz nazwa: **MaSzyna - Symulator Pojazdów Szynowych.**

Pod koniec 2003 roku powstało [forum](//eu07.pl/forum/), które pełni kluczową rolę w rozwoju projektu. Jest to kopalnia wiedzy, miejsce dyskusji, testowania i wydawania plików. Wraz z upływem czasu zmieniały się również osoby tworzące dodatki. Od roku 2006 na forum zaczęły się pojawiać obszerne, kompatybilne paczki całościowe, zawierające najnowsze dodatki i rozwiązania. Dziś każde najnowsze wydanie Symulatora wraz z aktualnymi i przetestowanymi dodatkami można pobrać w dziale [,,Do pobrania'']({{< relref "do-pobrania" >}}) na stronie projektu.

Na podstronie [,,Zestawienie wydań'']({{< relref "zestawienie-wydan" >}}) znajduje się spis całościowych wydań Symulatora od 2006 roku wraz z krótkim ich opisem.

![Zrzut ekranu 1](/images/eu07_kabina_rozwoj.png)

#### MaSzyna stawia na jakość
Wysoka jakość to priorytet MaSzyny. Przy tworzeniu scenerii, dźwięków, modeli taboru, infrastruktury oraz scenariuszy autorzy starają się jak najdokładniej odwzorować rzeczywistość. Udało się to osiągnąć poprzez opracowanie i ciągłe modyfikowanie wytycznych, które muszą spełniać dodatki oraz poprzez przyjęcie procedury testowania każdego nowego dodatku. Przy tworzeniu nowych modeli taboru (lokomotywy, wagony) twórcy mają możliwość stworzyć charakterystykę pojazdu niemalże identyczną z rzeczywistością, wówczas lokomotywa czy wagon rozpędza się i hamuje jak w rzeczywistości. Ponadto, przy tworzeniu nowych scenerii i scenariuszy autorzy skupiają się na ich zgodności z obowiązującymi przepisami kolejowymi. Wszystko to sprawia, iż poziom realizmu symulacji w MaSzynie jest niezwykle wysoki.

![Zrzut ekranu 2](/images/main1.png)

#### Każdy może się przyłączyć!
Autorzy dążą do tego, aby MaSzyna była wolna od wad, jednakże Symulator jest ciągle rozwijającym się projektem, w którym zdarzają się błędy i niedociągnięcia. Oczywiście każdy może się dołączyć do ich eliminacji!

#### Jak można pomóc w rozwoju projektu?
Każdy, kto interesuje się transportem kolejowym jest w stanie pomóc w rozwijaniu MaSzyny. Istnieje bardzo wiele płaszczyzn, na których można się wykazać. Wbrew powszechnej opinii, by tworzyć aplikację komputerową tego typu, wcale nie trzeba się znać na zaawansowanej informatyce. Przykładowo, wystarczy posiadać aparat fotograficzny, by móc wspierać modelarzy zdjęciami różnych obiektów, które mogą być wstawiane na sceneriach. Kto nie posiada aparatu, może nagrywać dźwięki różnych urządzeń. Historia społeczności forum zna jednak przypadki, gdzie wiele osób niespecjalnie związanych z programowaniem czy modelowaniem w programach graficznych, było w stanie opanować te narzędzia i wnieść istotny wkład w rozwój.

Jak wspomniano wyżej, forum jest nieodłączonym elementem całego projektu. Można na nim znaleźć mnóstwo porad dotyczących wykonywania różnych modeli, tekstur, scenerii i wielu innych. W razie problemów doświadczeni użytkownicy służą swoją pomocą, dzieląc się wiedzą i spostrzeżeniami. Istnieje też możliwość poszerzenia grona Betatesterów, których zadaniem jest wyszczególnianie błędów w nowych dodatkach, wspieranie twórców nowych dodatków oraz samo ich tworzenie.

Zachęcamy zatem do odwiedzin i rejestracji konta na [forum](//eu07.pl/forum/), gdzie znajduje się więcej informacji i poradników. Lista zagadnień dotyczących wsparcia rozwoju Symulatora znajduje się w [tym wątku](//eu07.pl/forum/index.php/topic,19382.0.html) na forum.

#### Napisali o nas...

Zapraszamy na podstronę, gdzie chronologicznie przedstawiamy różne materiały z prasy, telewizji czy radia w których pojawiła się wzmianka na temat Symulatora ,,MaSzyna''. Strona będzie uzupełniana.

[Przejdź do podstrony ,,Napisali o nas'']({{< relref "napisali-o-nas" >}})

***

* [Pierwsza wersja strony z 2003 r.](//eu07.pl/misc/)
* [Druga wersja strony powstała na przełomie 2003-2004 r.](//eu07.pl/eu07old.html)
* [Trzecia wersja strony używana od 2012 do 2024 r.](//eu07.pl/eu07old2.html)
..::: Testowanie www.google.com :::..

_Środowisko_

Przeglądarka Google Chrome - Wersja 80.0.3987.132 (Oficjalna wersja) (64-bitowa)
System operacyjny - Microsoft Windows 10 Pro Wersja 10.0.18363 Kompilacja 18363

Test Case nr.1

Wyszukiwanie - pozytywny

Kroki:

1) Idź do https://www.google.com.
1) Wyświetla się strona główna google.com.
2) Kliknij w pole wyszukiwania.
2) Kursor jest aktywny. 
3) Wpisz dowolny test i kliknij przycick "Szukaj w Google".
3) Wyświetlają się wątki zawierające wpisaną frazę. 

Test Case nr.2

Wyszukiwanie - negatywny

Kroki:

1) Idź do https://www.google.com.
1) Wyświetla się strona główna google.com.
2) Kliknij w pole wyszukiwania.
2) Kursor jest aktywny.
3) Wpisz ciąg kilku przypadkowych liter,cyfr i kliknij przycick "Szukaj w Google".
3) Wyświetla się komunikat "Podana fraza - "wpisany test" - niezostała znaleziona."

Test Case nr.3

Witualna klawiatura - wyszukiwanie

1) Idź do https://www.google.com.
1) Wyświetla się strona główna google.com.
2) Kliknij w logo klawiatury zlokalizowane z prawej strony wyszukiwarki.
2) Wyświetla się wirtualna klawiatura 
3) Wpisz frazę przy pomocy wirtualnej klawiatury i wybierz "Szukaj w Google".
3) Wyświetlają się wątki zawierające wpisaną frazę.

Test Case nr.4

Wirtualna klawiatura - klawisze

1) Idź do https://www.google.com.
1) Wyświetla się strona główna google.com.
2) Kliknij w logo klawiatury zlokalizowane z prawej strony wyszukiwarki.
2) Wyświetla się wirtualna klawiatura 
3) Klinij przycisk Shift (G) / Ctrl+Alt (ę) / Backspace i wyszukaj
3) Wyświetlają się wątki zawierające wpisaną frazę.

Test Case nr.5

Mikrofon wyszukiwarki - pozytywny (podłączony mikrofon)

1) Idź do https://www.google.com.
1) Wyświetla się strona główna google.com.
2) Kliknij na logo mikrofonu zlokalizowanego z prawej strony wyszukiwarki
2) Wyświetla się komunikat "Mów teraz" oraz logo mikrofonu.
3) Powiedz do mikrofonu szukaną frazę.
3) Wyświetlają się wątki związane z wyszukiwaną frazą.

Test Case nr.6

Mikrofon wyszukiwarki - negatywny (odłączony mikrofon)

1) Idź do https://www.google.com.
1) Wyświetla się strona główna google.com.
2) Kliknij na logo mikrofonu zlokalizowanego z prawej strony wyszukiwarki
2) Wyświetla się komunikat " Wyszukiwanie głosowe zostało wyłączone "

Test Case nr.7

Wyszukiwarka - przyciski - Szczęśliwy traf

1) Idź do https://www.google.com.
1) Wyświetla się strona główna google.com.
2) Kliknij przycisk "Szczęśliwy traf"
2) Wyświetla się okno z wydarzeniami z całego świata, święta, rocznice, ciekawe wydarzenia, imprezy sportowe itp.
3) Wróć do strony głównej, kliknij przycisk wstecz.
3) Wyświetla się strona główna.
4) Wpisz w wyszukiwarce frazę którą chcesz wyszukać i wciśnij przycisk "Szczęśliwy traf".
4) Wyświetla się strona zawierająca szukaną frazę która znalazła się na pierwszym miejscu na liście wyszukiwania 

Test Case nr.8

Menu górne - logowanie Gmail- pozytywne

1) Idź do https://www.google.com.
1) Wyświetla się strona główna google.com.
2) Na stronie głównej kliknij na "Gmail"
2) Wyświetla się formularz logowanie do Gmaila
3) Wypełnij pole "Adres e-mail lub telefon" kliknij "Dalej" (komenda nr.5 wpisz swój e-mail w Value)
3) Wyświetla się formularz logowanie z polem na hasło
4) Wypełnij pole "Wpisz hasło" i kliknij  "Dalej" (komenda nr.8 wpisz swoje hasło w Value)
4) Użytkownik zostaje zalogowany 

Test Case nr.9

Menu górne - logowanie Gmail - negatywne 

1) Idź do https://www.google.com.
1) Wyświetla się strona główna google.com.
2) Na stronie głównej kliknij na "Gmail"
2) Wyświetla się formularz logowanie do Gmaila
3) Wypełnij pole "Adres e-mail lub telefon" błędnym adresem e-mail:  

   a) bez nazwy użytkownika(komenda nr.5 błędny adres e-mail w Value), 
   b) bez "małpy"(komenda nr.7 błędny adres e-mail w Value) 
   c) bez domeny (komenda nr.9 błędny adres e-mail w Value)
   d) bez domeny najwyższego poziomu (komenda nr.11 błędny adres e-mail w Value)

   po każdym przykładzie kliknij "Dalej"

3) Obramowanie pola "Adres e-mail lub telefon" podświetla się na czerwono z komunikatem "Nie możemy znaleźć takiego konta Google".

Test Case nr.10

Menu górne logowanie Gmail - negatywne 2

1) Idź do https://www.google.com.
1) Wyświetla się strona główna google.com.
2) Na stronie głównej kliknij na "Gmail"
2) Wyświetla się formularz logowanie do Gmaila
3) Wypełnij pole "Adres e-mail lub telefon" kliknij "Dalej" (komenda nr.5 wpisz swój e-mail w Value)
3) Wyświetla się formularz logowanie z polem na hasło.
4) Wypełnij pole "Wpisz hasło" błędnymi danymi i kliknij "Dalej"
4) Wyświetla się pole "Wpisz hasło" z czerwoną ramką a pod nią komunikat na czerwono
   "Nieprawidłowe hasło.Spróbuj jeszcze raz lub kliknij "Nie pamiętam hasła", by je zresetować."

Test Case nr.11

Przyciski w formularzu logowania 

1) Idź do https://www.google.com.
1) Wyświetla się strona główna google.com.
2) Na stronie głównej kliknij na "Gmail"
2) Wyświetla się formularz logowanie do Gmaila
3) W formularzu logowania kliknij w lewym dolnym narożniku na język "polski" i wybierz inny język.
3) Wszystkie dane formularza wyświetlają się w wybranym języku.
4) Wybierz ponownie język polski
4) Wszystkie dane formularza wyświetlają się w wybranym języku.
5) W formularzu logowania kliknij w prawym dolnym narożniku na "Pomoc".
5) Wyświetla się nowe okno "Konto Google - Pomoc"
6) Zamknij okno i kliknij w prawym dolnym narożniku "Prywatność".
6) Wyświetla się nowe okno "Prywatność i warunki".
7) Zamknij okno i kliknij w prawym dolnym narożniku "Warunki".
7) Wyświetla się nowe okno "Prywatność i warunki".


Test Case nr.12

Formularz logowania odzyskiwanie adresu e-mail

1) Idź do https://www.google.com.
1) Wyświetla się strona główna google.com.
2) Na stronie głównej kliknij na "Gmail"
2) Wyświetla się formularz logowanie do Gmaila
3) W formularzu logowania kliknij "Nie pamiętasz adresu?"
3) Wyświetla się formularz odzyskiwania adresu e-mail.com
4) Wpisz pomocniczy adres e-mail lub nr.telefonu i kliknij "Dalej"
4) Wyświetla się formularz " Jak się nazywasz ?"
5) Wpisz dane: imię i nazwisko do konta pomocniczego i kliknij "Dalej"
5) Wyświetla się okno "Uzyskiwania kodu weryfikacyjnego" 
6) Kliknij "Wyślij"
6) Wyświetla się pole na kod weryfikacyjny przesłany na maila pomocniczego
7) Wpisz kod weryfikacyjny i kliknij "Dalej"
7) Wyświetla się okno "Wybierz konto" z podpowiedzią zapomnianego maila.

Test Case nr.13

Menu górne - Grafika

1) Idź do https://www.google.com.
1) Wyświetla się strona główna google.com.
2) Na stronie głównej kliknij na "Grafika" w prawym górnym narożniku.
2) Wyświetla się strona główna w większej rozdzielczości z dodatkową opcją wyszukiwania obrazem (ikona aparatu).
3) Kliknij ikonę aparatu.
3) Otwiera się okno wyszukiwania obrazem.
4) Wybierz zakładkę "Wklej adres obrazu" i wklej adres URL zdjęcia kliknij "Wyszukiwanie obrazu".
4) Wyświetlają się wątki związane ze zdjęcie z adresu URL.

Test Case nr.14

Menu górne - Grafika 2

1) Idź do https://www.google.com.
1) Wyświetla się strona główna google.com.
2) Na stronie głównej kliknij na "Grafika" w prawym górnym narożniku.
2) Wyświetla się strona główna w większej rozdzielczości z dodatkową opcją wyszukiwania obrazem (ikona aparatu).
3) Kliknij ikonę aparatu.
3) Otwiera się okno wyszukiwania obrazem.
4) Wybierz zakładkę "Prześlij obraz" i kliknij na "Wybierz plik".( należy wybrać ścieżkę do obrazu którym wyszukujemy )
4) Wyświetlają się wątki związane z przesłanym obrazem.

Test Case nr.15

Formularz logowanie - odzyskiwanie hasła

1) Wpisz adres mailowy w polu "Adres e-mail lub telefon" kliknij "Dalej".
1) Wyświetla się pole "Wpisz hasło" poniżej poniżej przycisk "Nie pamiętasz hasła?"
2) Kliknij "Nie pamiętasz hasła".
2) Wyświetla się formularz odzyskiwania hasła.
3) W polu "Wpisz ostatnio hasło"- wpisz hasło bez ostatniego znaku i kliknij "Dalej".
3) Wyświetla się okno "Odzyskiwania konta" zostaje wysłane powiadomienie na urządzenie które jest połączone z kontem.
4) Potwierdź w urządzeniu (telefon np.) logowanie.
4) Wyświetla się formularz zmiany hasła.
5) Wprowadź nowe hasło oraz potwierdzenie hasła kliknij "Zapisz hasło".
5) Wyświetla się okno "Jesteś zalogowany" oraz informacja odnośnie logowania.
6) Kliknij "Dalej"
6) Użytkownik zostaje zalogowany i przeniesiony do strony głównej.















# Opis Produktu: Narzędzie Admin dla Mikro-Szkół (MVP)


Planuję uruchomić platformę (marketplace) do zapisów na zajęcia pozaszkolne, łączącą rodziców z organizatorami (np. języki, taniec, sport) w jednej lokalizacji. Usługodawcą wobec rodzica jest zawsze organizator lub szkoła, a platforma pełni wyłącznie rolę narzędzia do zapisów i zarządzania listami/grupami (bez świadczenia samych zajęć). System ma umożliwiać publikację ofert, rekrutację do grup, limity miejsc oraz dołączanie uczniów także w trakcie semestru. Dominującym formatem rozliczeń po stronie organizatorów będą abonamenty miesięczne, przy zachowaniu elastyczności zapisów. Płatności będą obsługiwane przez pośrednika płatności - Stripe Connect, aby środki trafiały do właściwego usługodawcy, a platforma pobierała swoją opłatę/prowizję. Model przychodowy platformy zakłada stały abonament miesięczny plus prowizję od płatności.




## 1. Persona: Kasia Nowak – Właścicielka i instruktorka
Kasia prowadzi lokalną szkółkę (np. śpiewu lub tańca) z zespołem 3–5 osób. Obsługuje 8–20 grup tygodniowo w różnych lokalizacjach. Jej głównym problemem jest poczucie „utonięcia” w administracji: ręczne sprawdzanie przelewów (wieczorami), uganianie się za płatnościami i chaos w kalendarzu na WhatsAppie. Jej celem jest profesjonalny wizerunek w oczach rodziców i odzyskanie czasu na nauczanie.

---

## 2. Pokrycie Jobs to be Done (JTBD)

| Funkcja MVP | Adresowane JTBD | Znaczenie | Ryzyko / Luka |
| :--- | :--- | :--- | :--- |
| **1. Cyfrowe Zapisy** | F1, S1, S2 | **Krytyczne** | Musi płynnie obsługiwać dołączanie uczniów w środku semestru. |
| **2. Forma Dokumentowa** | S1, E2, F5 | **Wysokie** | Prawna prostota (brak papieru) to klucz do szybkości wdrożenia. |
| **3. Panel Płatności** | F2, E1 | **Wysokie** | Ręczne oznaczanie to start; automatyzacja (BLIK) będzie szybko niezbędna. |
| **4. Logika Nieobecności** | F3, S2 | **Średnie** | Mechanizm „kredytów” musi być jasny, by uniknąć kłótni o pieniądze. |
| **5. Zestaw Marketingowy** | F4, E4 | **Bardzo Wysokie** | To nasz **lewar**. Zamienia wydatek na narzędzie w maszynkę do zarabiania. |

---

## 3. Główne Funkcje (Specs)
- **Zunifikowany Kalendarz:** Jedno źródło prawdy dla instruktorów i rodziców.
- **Zapisy jednym linkiem:** Automatyczne zbieranie danych, zgód RODO i akceptacji regulaminu (Forma Dokumentowa).
- **Zarządzanie Płatnościami:** Widok „kto zapłacił” i automatyczne przypomnienia o zaległościach.
- **System Odrabiania:** Automatyczne wydawanie kredytów za zgłoszone nieobecności (min. 4h przed).
- **Generator Marketingowy:** Tworzenie postów FB/IG z informacją o wolnych miejscach i linkiem do zapisu.

---

## 4. Harmonogram Wdrożenia (Roadmap)

### Etap 1: Brama Zapisów (Etap 1)
*Cel: Przejęcie startu semestru i profesjonalizacja pierwszego kontaktu.*
- **Funkcje:** Kalendarz wewnętrzny, link do zapisów, zgody RODO, lista uczniów.
- **Efekt:** Kasia rezygnuje z Google Forms/Papieru na rzecz profesjonalnego formularza.

### Etap 2: Spokój Finansowy (Etap 2)
*Cel: Widoczność cashflow i eliminacja niezręcznych rozmów o pieniądzach.*
- **Funkcje:** Dashboard płatności (manualne oznaczanie), automatyczne maile/SMS z przypomnieniem, kalkulator pro-rata.
- **Efekt:** Kasia wie dokładnie, kto zalega, bez wertowania historii konta bankowego.

### Etap 3: Wzrost i Skalowanie (Etap 3)
*Cel: Zapełnienie grup i automatyzacja codziennego tarcia.*
- **Funkcje:** Zestaw Marketingowy (grafiki FB), zgłaszanie nieobecności przez rodziców, automatyczna logika odrabiania.
- **Efekt:** Grupy dobijają do 100% obłożenia; koniec nocnego układania grafiku odrabiań.

---

## 5. Dlaczego to wygra?
System nie jest tylko „kosztem” administracyjnym. Dzięki **Zestawowi Marketingowemu** bezpośrednio zwiększa przychody szkółki, a dzięki **Formie Dokumentowej** i **braku konieczności instalowania apki przez rodziców**, bariera wejścia jest bliska zeru.

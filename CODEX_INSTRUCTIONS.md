# Instrukcje dla Codexa

Projekt: prywatna mobilna strona z 8-tygodniowym planem biegowym.

Pracuj tylko na pliku `index.html`.

Nie zmieniaj treści planu treningowego:
- nie zmieniaj nazw tygodni,
- nie zmieniaj dni treningowych,
- nie zmieniaj opisów treningów,
- nie zmieniaj stref tętna,
- nie zmieniaj temp,
- nie zmieniaj struktury danych WEEKS, chyba że jest to konieczne dla funkcjonalności.

Cel V1:
1. Naprawić wykres objętości.
2. Przerobić stronę na mobile-first.
3. Dodać checkboxy wykonania treningów.
4. Dodać prosty dziennik po treningu:
   - RPE 1–10,
   - czas wykonany,
   - średnie tętno,
   - średnie tempo,
   - notatka.
5. Wszystkie dane użytkownika zapisywać w localStorage.
6. Nie dodawać backendu.
7. Nie dodawać logowania.
8. Nie dodawać Stravy.
9. Nie dodawać importu GPX/FIT/TCX.
10. Nie dodawać AI.
11. Nie robić dużego redesignu wizualnego na tym etapie.

Najważniejszy błąd do naprawy:
Wykres objętości nie może korzystać z ręcznie wpisanego `totalMin`.
Wykres ma liczyć objętość automatycznie jako sumę `sessions[].duration` dla każdego tygodnia.

Oczekiwane sumy tygodni:
- T1: 130 min
- T2: 142 min
- T3: 157 min
- T4: 124 min
- T5: 173 min
- T6: 187 min
- T7: 195 min
- T8: 143 min

Zasady pracy:
- Rób małe zmiany.
- Po każdej zmianie opisz, co zostało zmienione.
- Nie przebudowuj całego pliku bez potrzeby.
- Priorytet: działanie, czytelność na telefonie, brak utraty danych.
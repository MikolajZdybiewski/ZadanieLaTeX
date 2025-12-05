# Wprowadzenie do Sztucznej Inteligencji - Projekt LaTeX

Repozytorium zawiera projekt zaliczeniowy przygotowany w systemie składu tekstu **LaTeX**. Dokument stanowi raport techniczny poruszający tematykę historii, podziału oraz współczesnych zastosowań sztucznej inteligencji (AI).

## 📄 Opis zadania
Projekt został zrealizowany w ramach zaliczenia przedmiotu. Celem było stworzenie złożonego dokumentu z wykorzystaniem klasy `report`, demonstrującego umiejętności takie jak:
* Podział struktury logicznej na osobne pliki (`\input`).
* Automatyczne generowanie spisu treści, tabel i rysunków.
* Obsługa bibliografii i cytowań za pomocą **BibTeX/Biber**.
* Zaawansowana konfiguracja nagłówków i stopek (`fancyhdr`).
* Umieszczanie grafik i tabel.

## 📂 Struktura plików
Projekt zachowuje modułową budowę dla zwiększenia czytelności kodu:

* `main.tex` – Główny plik projektu, łączący wszystkie komponenty.
* `rozdzial1.tex` – Wstęp do problematyki AI.
* `rozdzial2.tex` – Historia i rodzaje sztucznej inteligencji.
* `rozdzial3.tex` – Zastosowania praktyczne (zawiera tabele i wykresy).
* `rozdzial4.tex` – Wnioski i uzasadnienie doboru narzędzi.
* `references.bib` – Baza źródeł bibliograficznych.

## 🚀 Kompilacja
Aby zbudować plik PDF z kodu źródłowego, wymagany jest kompilator LaTeX (np. TeX Live, MiKTeX) oraz silnik bibliografii Biber.

Zalecana kolejność poleceń:
1.  `pdflatex main.tex`
2.  `biber main`
3.  `pdflatex main.tex`
4.  `pdflatex main.tex`

## 👤 Autor
**Mikołaj Zdybiewski**
Politechnika Wrocławska

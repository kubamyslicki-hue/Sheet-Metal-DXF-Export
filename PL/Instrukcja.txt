# Eksport blach do DXF – Autodesk Inventor

**Wersja:** 1.0  
**Autor:** Kuba Myślicki  
**Środowisko:** Autodesk Inventor 2026  
**Język:** Polski

## Opis projektu

Eksport blach do DXF to makro VBA dla Autodesk Inventor, które automatyzuje eksport rozwinięć elementów blaszanych z aktywnego złożenia do plików DXF.

Narzędzie ogranicza ręczną pracę i przyspiesza przygotowanie dokumentacji produkcyjnej.

## Funkcjonalności

Makro automatycznie wyszukuje elementy blaszane w złożeniu i podzłożeniach, tworzy brakujące rozwinięcia oraz eksportuje unikalne części do plików DXF. Umożliwia wybór folderu docelowego, obsługę istniejących plików, konfigurację widoczności linii gięcia oraz monitorowanie i przerywanie eksportu.

## Wymagania

- Autodesk Inventor 2026.
- Obsługa makr VBA w Inventorze.

## Instalacja

1. Pobierz plik `Sheet.Metal.DXF.Export.v1.0_PL.ivb` z sekcji [Releases](../../releases).
2. Otwórz Autodesk Inventor i naciśnij `Alt + F11`.
3. Wybierz **Plik → Wczytaj projekt** i wskaż pobrany plik `.ivb`.
4. Zamknij edytor VBA.
5. W Inventorze otwórz **Narzędzia → Makra**.
6. Wybierz `Eksport_blach_do_DXF` i kliknij **Uruchom**.

## Użytkowanie

Otwórz złożenie `.iam`, wybierz opcje eksportu i kliknij **Eksportuj**. Pliki DXF zostaną zapisane w wybranym folderze.

## Kontakt

Potrzebujesz innych narzędzi automatyzujących pracę w Autodesk Inventor?

**Kuba Myślicki**  
kuba.myslicki@gmail.com

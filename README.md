# Projekt_AP_153847

Strona internetowa wykonana w workflowr.

## Jak uruchomic projekt

1. Zainstaluj R i RStudio
2. Zainstaluj Quarto: https://quarto.org/docs/get-started/
3. Otworz plik .Rproj w RStudio
4. Wykonaj w konsoli:
   source("setup.R")
   quarto::quarto_render("analysis/Moje_Zainteresowania.qmd")
   rmarkdown::render("analysis/Moje_Zainteresowania.Rmd")
5. Zbuduj strone:
   workflowr::wflow_build()

## Struktura projektu
- analysis - pliki .Rmd i .qmd
- docs - wygenerowane pliki HTML
- data - dane
- graphical_assets - zdjęcia
- setup.R - skrypt instalacyjny

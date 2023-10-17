# Lekce 5 – HTML formuláře

Zatím jsme jen zobrazovali data, dnes je konečně začneme také upravovat. Použijeme k tomu HTML formuláře. 

1. Udělej fork zdrojového repository do svého účtu na GitHubu.
1. Naklonuj si repository **ze svého účtu** na GitHubu na lokální počítač.

## Cvičení
1. Pod tabulku na úvodní stránce přidej nadpis *Append new person* a pod něj přidej formulář pro zadání nové osoby. Fomrulář můžeš zkopírovat z editačního fomruláře na stránce s detailem.
1. Formulář bude mít akci `/` a metoda bude `post`.
1. Vytvoř v controlleru metodu `append`. Metoda bude mapována na metodu `POST` a jako parametr bude přijímat entitu `Person`.
1. V metodě controlleru `append` použij metodu `append` ze služby `service` pro přidání nové osoby do seznamu osob.
1. Na konci controlleru proveď přesměrování zpět na úvodní stránku aplikace (POST-redirect-GET), aby se zobrazil seznam osob. Seznam se zobrazí už s nově přidanou osobou.

## Odkazy
* [Lekce 5](https://java.czechitas.cz/2023-podzim/java-2-online/lekce-5.html)


# Projekt Internetové Bankovniství
## Patrik Smuda

### Krátké Info
Tento projekt je zmenšená a osekaná verze bankovnictví, které se dnes používají

Projekt je postavený na dvou uživatelských pohledech User a Banker.

### Použité Gemy
 **Devise** - Autentizace uživatelů

 **Ransack** - Filtrování nad tabulkami

 **Pagy** - Stránování

 ### Stylování
 **Tailwind** (u designu jsem si pomáhal AI)

### Funkcionalita
##### Po spuštení se objeví devise rozscestník pro oba pohledy 
#### User
Má všechny devise možnosti(registrace, přihlášení, pass recovery atd.)
Po registraci se automaticky vytvoří a přiřadí účet.
Uživatel má k dispozici tyto views:
* **Root:** Přehled ůčtu.
* **Transactions:** Zobrazení všech transakcí, celková vybraná částka.
* **New Transactions:** Vytvoření transakce, výběr mezi Vkladem/Výběr/Převod. Při převodu druhá strana vidí, kdo peníze poslal.
* **Loans:** Zobrazení půjček, vytvoření žádností o nové.
#### Banker
Nelze změnit heslo/registrovat, je zadán natvrdo v seedu.
Má kompletní přístup ke všem datům 
* **Root:** Domovská stránka.
* **Accounts:** Přehled všech účtu, možnost smazat účet(s ním automaticky uživatele). Možnost filtrování na základě dat
* **Transactions:**  Přehled všech transakcí všech uživatelů
* **Users:** Přehled všech uživatelů

Rozcestník:
/// IMG

### Body v projektu
**1.**

**2.**
**3.**
**4.**
**5.**
**6.**
**7.**
**8.**
**9.**
**10.**







### Základní pojmy
- **Entita** => třída objektů stejného typu (zaměstnanec, zvíře)
- **Atributy** => vlastnosti objektů dané entity (jméno, příjmení)
- **Instance** => konkrétní objekt dané entity (Jan, Klus)
 
- Vazby (relace) => vztahy mezi entitami, které popisujeme pomocí:
	- Kardinality => četnost (M:N, 1:N, 1:1)
	- Parcialita => povinnost ve vztahu (může, musí)
	- Stupně vazby => kolik entit je ve vztahu
		- Stupeň 1 = 1 entita ve vazbě `self reference`
		- Stupeň 2 = 2 entity ve vazbě
		- Stupeň 3 a více = 3 a více ve vazbě

### Logické (konceptuální) schéma
Obsahuje:
- Entity
- Vazby => různé typy notace
- (Nepovinné) Uživatelské atributy => Nikoliv klíče!!!
Je určeno: 
- Pro klienta, jako prvotní návrh (koncept)

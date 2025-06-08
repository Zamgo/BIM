---
tags:
  - Permanent
aliases:
  - Příloha B
  - Příklady metod pro stanovení úrovně informačních potřeb
  - Examples of methods to specify level of information need
topics:
  - "[[BIM normy]]"
resource: "[[ČSN EN ISO 7817-1 2024 - Informační modelování staveb úroveň informačních potřeb - Část 1 Pojmy a principy]]"
time stamp/page: "18"
---
# Příloha B
## Příklady metod pro stanovení úrovně informačních potřeb
## B.1 Obecně  
Tato příloha popisuje některé příklady, jak stanovit úroveň informačních potřeb. 
Příloha využívá jeden scénář, který je ilustrován dvěma příklady.

Stejnou metodu nebo metody uvedené v této příloze lze použít pro každý projektový milník předání informací a pro všechny účely. Další příklady lze nalézt v dalších částech řady ISO 7817.

Každý příklad vychází z předpokladů uvedených v tomto dokumentu, zejména z diagramu vztahů úrovně informačních potřeb.

![[ČSN EN ISO 7817-1 2024 - Obrázek B.1 – Předpoklady tak, jak jsou zobrazeny v části Obrázku 8.png]]
**Obrázek B.1 – Předpoklady tak, jak jsou zobrazeny v části Obrázku 8**  

**Poznámka:** Pořadí, v jakém jsou předpoklady uvedeny, může být flexibilní. Například účel nemusí vždy předcházet informace a může být zohledněn až po určení milníku pro předání informací.

---
## B.2 Příklady

### B.2.1 Obecně 
Následující dva příklady používají stejné předpoklady, ale ukazují různé možné způsoby prezentace informací. První příklad využívá tabulkový přístup, zatímco druhý využívá jiný přístup.

Předpoklady jsou uvedeny v pořadí, jak je znázorněno na Obrázku B.1:

- účel **(proč**),

- milník pro předání informací (**kdy**),

- aktér (**kdo**),
	**Poznámka 1:**  
	Podle [[ČSN EN ISO 7817-1 2024 5 Rámec pro určení úrovně informačních potřeb|5.1]] jsou uvedeny dva typy aktérů: 
	- aktéři, kteří informace přijímají, 
	- aktéři, kteří informace poskytují. 
	Je umožněno zaznamenat jak příjemce, tak poskytovatele informací.

- objekt (**co**).
	**Poznámka 2:**  
	Podle [[ČSN EN ISO 7817-1 2024 5.5 Zohlednění objektů ve struktuře členění|5.5]] platí, že „objekty ve struktuře členění určené pro předání informací musí být zohledněny.“ Je umožněno zaznamenat jak samotný objekt, tak i jeho pozici ve struktuře členění.

![[ČSN EN ISO 7817-1 2024 - Obrázek B.2 – Předpoklady použité v obou příkladech.png]]
**Obrázek B.2 – Předpoklady použité v obou příkladech**

---
### B.2.2 Příklad 1 - Tabulka
Jednoduchou tabulku lze vytvořit pro opakované použití nebo průběžný vývoj v průběhu projektu, kde lze definovat předpoklady a následně stanovit úroveň informačních potřeb.

**Poznámka:**  
Formát tabulky je pouze orientační a může být upraven.

Nezaplněná (prázdná) tabulka může vypadat například jako na Obrázku B.3.

![[ČSN EN ISO 7817-1 2024 - Obrázek B.3 – Příklad 1 – prázdná tabulka.png]]
**Obrázek B.3 – Příklad 1 – prázdná tabulka**

Pro vyplnění tabulky lze doplnit předpoklady spolu s geometrickými informacemi, alfanumerickými informacemi a dokumentací, jak je ukázáno pro objekt „stěna“ na Obrázku B.4.  

**Tabulku lze vyplnit pro všechny požadované objekty pro stejný účel ve stejném milníku pro předání informací.**

![[ČSN EN ISO 7817-1 2024 - Obrázek B.4 – Příklad 1 – vyplněná tabulka pro objekt stěna.png]]
**Obrázek B.4 – Příklad 1 – vyplněná tabulka pro objekt "stěna"**

---
### B.2.3 Příklad 2 - Odstavec
Lze použít strukturu založenou na odstavcích, jak je uvedeno níže, do které se doplní konkrétní předpoklady:

- **Účel** (proč): xxx
    
- **Milník pro předání informací** (kdy): xxx
    
- **Příjemce informací** (kdo): xxx
    
- **Poskytovatel informací** (kdo): xxx
    
- **Objekt** (co): xxx
    
- **Struktura členění** (co): xxx
    
- **Úroveň informačních potřeb** (jak):  
	- **Geometrické informace:**  
		- (detail)  
		- (dimenzionalita)  
		- (umístění)  
		- (vzhled/zobrazení)  
		- (parametrické chování)

	- **Alfanumerické informace:**  
		- (identifikace)  
		- (obsah informací)

	- **Dokumentace:**  
		- (sada dokumentů)
---
#### Vyplněný příklad

Pro vyplnění této struktury lze doplnit předpoklady spolu s geometrickými informacemi, alfanumerickými informacemi a dokumentací. Například:

- **Účel** (proč): vizualizace
    
- **Milník pro předání informací** (kdy): předběžný návrh
    
- **Příjemce informací** (kdo): projektant
    
- **Poskytovatel informací** (kdo): geodet
    
- **Objekt** (co): stěna
    
- **Struktura členění** (co): klasifikace xxx

	**Výše uvedené předpoklady (prerekvizity) lze také vyjádřit jako větu:**  
	_Za účelem vizualizace prací na předběžném návrhu je geodet požádán, aby poskytl projektantovi následující informace o stěně podle klasifikace xxx._

- **Úroveň informačních potřeb (jak):**  

	- **Geometrické informace:**
		- (detail) Zjednodušené objemové zobrazení včetně otvorů
		- (dimenzionalita) 3D
		- (umístění) Absolutní
		- (vzhled/zobrazení) Realistický s texturou materiálů
		- (parametrické chování) Nevyžaduje se

	- **Alfanumerické informace:**
		- (identifikace) Typ stěny  
		    _(dále by mohlo následovat např. obsah informací atd.)_
		- (obsah informací): Typ, …

	- **Dokumentace:**  
		- (sada dokumentů): Nevyžaduje se

**Poznámka 2:**  
Text v závorkách lze při stanovení předpokladů a úrovně informačních potřeb vynechat. V textu je uveden pouze pro vysvětlení.

---
# Annex B
## Examples of methods to specify level of information need

## B.1 General
This annex describes some examples to specify the level of information need. This annex does so through the use of a single scenario, shown in two examples.

The same method or methods included in this annex can be applied for -every project information delivery milestone for all purposes, Further examples can be found in other parts Of the ISO 7817 series.

Each example has been created from the prerequisites detailed in this document, particularly the relationship diagram on level of information need.

![[ČSN EN ISO 7817-1 2024 - Obrázek B.1 – Předpoklady tak, jak jsou zobrazeny v části Obrázku 8.png]]
**Figure B.1 - Prerequisites as shown in a section of Figure 8**

**NOTE** 
The order in which prerequisites are listed can be flexible. For example, the purpose does not always precede information and it can be considered after the information delivery milestone has been determined.
## B.2 Examples
### B.2.1 General

The following two examples use the same prerequisites but demonstrate different possible ways of presenting the information. The first example uses a table approach whilst the second uses approach.

The prerequisites are listed in the order as shown in Figure Bel, being:
-  purpose (why);
- information delivery milestone (when);
-  actor (who);
	**NOTE 1**
	 According to [[ČSN EN ISO 7817-1 2024 5 Rámec pro určení úrovně informačních potřeb|5.1]] two types of actors are presented: actors who receive information and actors who provide information. Provision has been provided for both information receiver and information provider.
- object (what).
	NOTE 2 
	[[ČSN EN ISO 7817-1 2024 5.5 Zohlednění objektů ve struktuře členění|5.5]] states the objects within a breakdown structure for the information delivery shall be-considered. Provision has been provided for both object and breakdown structure.

See Figure B.2 for the project information for the examples.

![[ČSN EN ISO 7817-1 2024 - Obrázek B.2 – Předpoklady použité v obou příkladech.png]]
**Figure B.2 — Prerequisites used across the two examples**

### B.2.2 Example 1
A simple table can be produced for either re-use or iterative development throughout a project where the prerequisites can be defined, and the level of information need can subsequently be specified.

**NOTE**
The format of the table is indicative and can be modified.
An unpopulated table can be as indicated in Figure B.3.

![[ČSN EN ISO 7817-1 2024 - Obrázek B.3 – Příklad 1 – prázdná tabulka.png]]
**Figure B.3 Example 1- blank table**

To populate the table, the prerequisites can be added, along with the geometrical in formation, alphanumerical information and documentation as shown for the object "wall" in Figure B.4. The table can be populated for all required objects for the same purpose at the same information delivery milestone.

![[ČSN EN ISO 7817-1 2024 - Obrázek B.4 – Příklad 1 – vyplněná tabulka pro objekt stěna.png]]**Figure B.4 — Example - populated table for "wall" object**

### B.2.3 Example 2
A clause-based structure can be used as indicated below which requires the addition of the specific prerequisites:
Purpose (why): xxx; information delivery milestone (when): xxx; information receiver (who): xxx; information provider (who): xxx; object (what): xxx; breakdown structure (what): xxx.

Level of information need (how)
- geometrical information:
	- (detail)
	- (dimensionality)
	- (location)
	- (appearance)
	- (parametric behaviour)
- alphanumerical information:
	- (identification)
	- (information content)
- documentation:
	- (set of documents)

To populate the clause-based structure, the prerequisites can be added, along with the geometrical information, alphanumerical information and documentation:
Purpose (why): visualization; information delivery milestone (when): preliminary design; information receiver (who): designer; information provider (who): surveyor; object (what): wall; breakdown structure (what): classification xxx.

The prerequisites above can also be expressed as a sentence.

To enable the visualization of the preliminary design works, the surveyor is requested to provide the following information relating to the wall to the designer using classification xxx.

Level of information need (how)
- geometrical information:
	- (detail) Simplified volume representation including openings
	- (dimensionality) 3D
	- (location) Absolute
	- (appearance) Realistic with texture of materials
	- (parametric behaviour) Not requested
- alphanumerical information:
	- (identification) Wall type
	- (information content) Type, ...
- documentation:
	- (set of documents) Not requested

**NOTE 2** 
The text in brackets can be omitted when specifying the prerequisites and the level of information need.

The text in brackets has been included for explanation.
# Connections

- [[ČSN EN ISO 7817-1 2024 5 Rámec pro určení úrovně informačních potřeb|Rámec pro určení úrovně informačních potřeb]]
- [[ČSN EN ISO 7817-1 2024 6 Definice úrovně informačních potřeb a její členění|Definice úrovně informačních potřeb a její členění]]

- [[ČSN EN ISO 7817-1 2024 - Informační modelování staveb úroveň informačních potřeb - Část 1 Pojmy a principy]]
- [[ČSN EN ISO 19650-1 2018 - Organizace a digitalizace informací o budovách a inženýrských stavbách včetně informačního modelování staveb (BIM) - Management informaci s využitím informačního modelování staveb - Část 1 - Pojmy a principy]]
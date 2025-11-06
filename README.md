# Strojní dílna – Firemní webové stránky

**Strojní dílna** je firemní webová stránka vytvořená pro malou rodinnou firmu zabývající se obráběním kovů a zámečnickými pracemi.  
Web byl navržen a naprogramován jako kompletní systém s administrací, databází, responzivním designem a vícejazyčnou podporou.

## Autor projektu
**Autor:** Patrik Poklop  
**Vedoucí práce:** Bc. Jakub Pokorný  
**Škola:** Střední průmyslová škola, Resslova 5, Ústí nad Labem  
**Třída:** 4ITB  
**Rok:** 2022/2023  

## Popis projektu
Cílem projektu bylo vytvořit moderní a responzivní web pro dílnu, která se zabývá kovovýrobou.  
Web slouží k prezentaci firmy, zobrazení nabízených služeb, přehledu strojů a umožňuje zákazníkům zadávat zakázky online.

Hlavní funkce:
- Firemní prezentace a popis služeb  
- Galerie strojů s možností zvětšení obrázků  
- Formulář pro odeslání zakázky  
- Novinky a správa obsahu (admin rozhraní)  
- Systém registrace a přihlášení uživatelů  
- Přepínání jazyků (CZ/EN)  
- Cookies oznámení  
- Responzivní design pro mobilní zařízení  

## Použité technologie
| Technologie | Popis |
|--------------|--------|
| **HTML5** | Struktura a obsah webu. |
| **CSS3 / Bootstrap** | Stylování, rozložení prvků, responzivní design. |
| **JavaScript (ES6)** | Interaktivní funkce (slider, menu, fetch API). |
| **PHP** | Serverová logika, přihlášení, registrace, práce s databází. |
| **MySQL** | Databáze pro ukládání uživatelů, novinek a zakázek. |
| **jQuery / AJAX** | Dynamické načítání a mazání dat bez reloadu. |

## Klíčové funkce
- **Responzivní navigace** – automatické přizpůsobení zobrazení na PC i mobilu  
- **Automatický slider** – JavaScript přepínání obrázků pomocí šipek nebo automaticky  
- **Registrace a přihlášení** – kontrola vstupů, šifrování hesla, kontrola duplicity  
- **Přepínání jazyků** – pomocí PHP session a přepínače  
- **Novinky** – správa obsahu adminem, načítání přes `fetch API`  
- **Formulář zakázky** – odesílání požadavků na e-mail a zápis do databáze  
- **Cookies lišta** – oznámení o souhlasu s cookies  
- **Admin rozhraní** – správa zakázek a uživatelů pomocí PHP, jQuery a AJAXu  

## Databázový návrh
**ERD model:**\  
Databáze uchovává tabulky:
- `users` – uživatelské účty  
- `orders` – zakázky  
- `news` – novinky  

Každý účet má propojení přes `user_id` na své zakázky a případné novinky.

## Návrh a struktura webu
Hlavní sekce webu:
1. **Úvodní stránka** - Nadpis, popis firmy, automatický slider obrázků
2. **Služby** - Přehled činností firmy v barevných boxech (flexbox / grid)
3. **Formulář pro zakázky** - Odesílání požadavků přes PHP a zápis do DB
4. **Ceník a materiály** - Tabulka s materiály, se kterými dílna pracuje
5. **Galerie strojů** - Obrázky se zvětšením pomocí `zoom.js`
6. **Novinky** - Načítání a mazání přes `fetch API` a `Ajax`
7. **Kontakty** - Základní údaje (e-mail, telefon, provozní doba, mapa s poloho firmy)

## Responzivita
- Kompletní přizpůsobení pro mobilní zařízení (Android/iOS)  
- Rozbalovací menu ovládané přes JavaScript  
- Optimalizované rozložení pro malé displeje  

## Admin rozhraní
- **Přihlášený uživatel** má přístup k informacím o svém účtu  
- **Admin** může:
  - Mazat a spravovat zakázky  
  - Přidávat a mazat novinky  
  - Vidět všechny uživatele  
- Vše probíhá pomocí `AJAX` a `jQuery`, bez reloadu stránky  

## Shrnutí a přínosy
Na projektu jsem se naučil:
- efektivně používat **HTML, CSS, PHP a JavaScript** společně,  
- navrhnout a implementovat **databázovou logiku v MySQL**,  
- používat **Bootstrap** pro responzivní layout,  
- a používat **AJAX a fetch API** pro interaktivní webové funkce.  

## Obrázky

**Hlavní stránka:**
<img width="907" height="458" alt="image" src="https://github.com/user-attachments/assets/0293c4d4-72ed-4bbb-aa1a-504504ce0e99" />

**Správa účtu:**
<img width="905" height="443" alt="image" src="https://github.com/user-attachments/assets/f374d3e5-6882-4565-bf86-d72f637ea827" />

**Správa objednávek:**
<img width="902" height="476" alt="image" src="https://github.com/user-attachments/assets/701f59d1-9f09-4343-a73c-3782aaa0f542" />

**Správa novinek:**
<img width="907" height="451" alt="image" src="https://github.com/user-attachments/assets/119e0d89-fef6-49c6-9af7-22a9523f99ea" />

**Responzivita:**
<img width="294" height="555" alt="image" src="https://github.com/user-attachments/assets/1d247b76-9baa-47eb-9dc4-205d76a3e9e2" />

## Použitá literatura
_1. cs.wikipedia.org: Hypertext Markup Language_ [online]. 1990 [cit. 202 3 - 01 - 14 ]. Dostupné z:
https://cs.wikipedia.org/wiki/Hypertext_Markup_Language
_2. cs.wikipedia.org: Kaskádové styly (CSS)_ [online]. 1996 - 12 - 17 [cit. 202 3 - 01 - 14 ]. Dostupné z:
https://cs.wikipedia.org/wiki/Kask%C3%A1dov%C3%A9_styly
_3. cs.wikipedia.org: MySQL_ [online]. 1995 - 05 - 23 [cit. 202 3 - 03 - 09 ]. Dostupné z:
https://cs.wikipedia.org/wiki/MySQL
_4. cs.wikipedia.org: PHP_ [online]. 1995 - 06 - 08 [cit. 202 3 - 01 - 14 ]. Dostupné z:
https://cs.wikipedia.org/wiki/PHP
_5. php.net: PHP_ [online]. 1995 - 06 - 08 [cit. 202 3 - 01 - 14 ]. Dostupné z:
https://www.php.net
_6. cs.wikipedia.org: JavaScript_ [online]. 1995 [cit. 202 3 - 01 - 14 ]. Dostupné z:
https://cs.wikipedia.org/wiki/JavaScript
_7. cs.wikipedia.org: Bootstrap_ [online]. 2002 - 11 - 22 [cit. 202 3 - 03 - 09 ]. Dostupné z:
https://cs.wikipedia.org/wiki/Bootstrap


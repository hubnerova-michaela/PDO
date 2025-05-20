# 🌞 Aplikace pro monitorování solární elektrárny  

## O projektu  
Tato aplikace slouží k **monitorování výkonu solární elektrárny a spotřeby elektřiny** v domácím prostředí. Data jsou získávána z **elektroměru a dvou BMS zařízení** a zobrazována v **tabulkách** nebo **grafech** podle času.  

Aplikace **nenabízí notifikace ani tipy na úsporu energie**, ale umožňuje uživatelům sledovat produkci a spotřebu elektřiny v reálném čase. Původně byla vytvořena pro potřeby konkrétní rodinné solární elektrárny, ale může ji využít i kdokoliv s podobným systémem.  

Aplikace je postavena na **ASP .NET Core Razor Pages** a používá **Microsoft SQL Server** pro ukládání dat. Je nasazena na **Intel NUC** s možností vzdáleného přístupu přes **TailScale**.  

---

# Cílová skupina a typ dokumentace  

## Primární uživatel: Rodinný uživatel solární elektrárny  
**Charakteristika:**  
- sleduje výrobu a spotřebu energie ve své domácnosti
- nemá hlubší technické znalosti, potřebuje **jednoduchý a přehledný návod**

**Možná dokumentace:**  
- **Stručný uživatelský manuál** s **obrázky** → jak se přihlásit, kde najít data, jak číst grafy
- **Vizuální zobrazení** s vysvětlením, co znamenají jednotlivé hodnoty (např. spotřeba vs. výroba)  


# Osnova dokumentace

## Úvod

## Přístup a přihlášení do aplikace
### Přihlášení mimo domácí síť

## Jak přidat měřicí zařízení

## Jak zobrazit naměřené údaje
### Zobrazení údajů z BMS (baterie)
### Zobrazení údajů z elektroměru

## Správa zařízení a záznamů s naměřenými údaji
### Jak zobrazit detail naměřeného záznamu
### Jak upravit naměřený záznam/informace o zařízení
### Jak smazat naměřený záznam/zařízení

## Řešení nejčastějších problémů
### Zařízení se nezobrazuje na hlavní stránce
### Grafy se nezobrazují
### Nelze se připojit z mobilu nebo jiného zařízení
### Data v tabulkách nebo grafech nevypadají správně
### Nejde se přihlásit do aplikace






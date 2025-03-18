# 🌞 Aplikace pro monitorování solární elektrárny  

## O projektu  
Tato aplikace slouží k **monitorování výkonu solární elektrárny a spotřeby elektřiny** v domácím prostředí. Data jsou získávána z **elektroměru a dvou BMS zařízení** a zobrazována v **tabulkách** nebo **grafech** podle času.  

Aplikace **nenabízí notifikace ani tipy na úsporu energie**, ale umožňuje uživatelům sledovat produkci a spotřebu elektřiny v reálném čase. Původně byla vytvořena pro potřeby konkrétní rodinné solární elektrárny, ale může ji využít i kdokoliv s podobným systémem.  

Aplikace je postavena na **ASP .NET Core Razor Pages** a používá **Microsoft SQL Server** pro ukládání dat. Je nasazena na **Intel NUC** s možností vzdáleného přístupu přes **TailScale**.  

---

# Cílové skupiny a typ dokumentace  

## 1) Primární uživatel: Rodinný uživatel solární elektrárny  
**Charakteristika:**  
- sleduje výrobu a spotřebu energie ve své domácnosti
- nemá hlubší technické znalosti, potřebuje **jednoduchý a přehledný návod**

**Možná dokumentace:**  
- **Stručný uživatelský manuál** s **obrázky** → jak se přihlásit, kde najít data, jak číst grafy
- **Vizuální zobrazení** s vysvětlením, co znamenají jednotlivé hodnoty (např. spotřeba vs. výroba)  

---

## 2) Technický uživatel (např. solární nadšenci, kteří si chtějí aplikaci sami nastavit nebo si chtějí aplikaci přizpůsobit)  
**Charakteristika:**  
- má technické znalosti a může chtít aplikaci rozšířit nebo nasadit na vlastní solární systém
- zajímá ho především **technická dokumentace** a konfigurace databáze
- chce k aplikaci přistupovat odkudkoliv mimo domácí síť

**Možná dokumentace:**  
- **Technická dokumentace** → jak aplikace funguje, jak sbírá data, jak ji rozšířit
- **Instalační příručka** → jak aplikaci nasadit (Intel NUC, TailScale, SQL Server) (video tutoriál?)
- **Komentovaný kód v repozitáři** → pro lepší pochopení struktury aplikace

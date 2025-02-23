# 🌞 Aplikace pro monitorování solární elektrárny  

## O projektu  
Tato aplikace slouží k **monitorování výkonu solární elektrárny a spotřeby elektřiny** v domácím prostředí. Data jsou získávána z **elektroměru a dvou BMS zařízení** a zobrazována v **tabulkách** nebo **grafech** podle času.  

Aplikace **nenabízí notifikace ani tipy na úsporu energie**, ale umožňuje uživatelům sledovat produkci a spotřebu elektřiny v reálném čase. Původně byla vytvořena pro potřeby konkrétní rodinné solární elektrárny, ale může ji využít i kdokoliv s podobným systémem.  

Aplikace je postavena na **ASP .NET Core Razor Pages** a používá **Microsoft SQL Server** pro ukládání dat. Je nasazena na **Intel NUC** s možností vzdáleného přístupu přes **TailScale**.  

---

# Cílové skupiny a typ dokumentace  

## 1) Primární uživatel: Rodinný uživatel solární elektrárny  
**Charakteristika:**  
- Sleduje výrobu a spotřebu energie ve své domácnosti.  
- Nemá hlubší technické znalosti, potřebuje **jednoduchý a přehledný návod**.  

**Možná dokumentace:**  
- **Stručný uživatelský manuál** s **obrázky** → Jak se přihlásit, kde najít data, jak číst grafy.  
- **Infografika** s vysvětlením, co znamenají jednotlivé hodnoty (např. spotřeba vs. výroba).  

---

## 2) Technický uživatel (např. solární nadšenci, kteří si chtějí aplikaci sami nastavit nebo si chtějí aplikaci přizpůsobit)  
**Charakteristika:**  
- Má technické znalosti a může chtít aplikaci rozšířit nebo nasadit na vlastní solární systém.  
- Zajímá ho především **technická dokumentace** a konfigurace databáze.
- Chce k aplikaci přistupovat odkudkoliv mimo domácí síť.

**Možná dokumentace:**  
- **Technická dokumentace** → Jak aplikace funguje, jak sbírá data, jak ji rozšířit.  
- **Instalační příručka** → Jak aplikaci nasadit (Intel NUC, TailScale, SQL Server).  
- **Komentovaný kód v repozitáři** → Pro lepší pochopení struktury aplikace.  

---

## 3) Administrátor systému (osoba zajišťující provoz aplikace)  
**Charakteristika:**  
- Spravuje běh aplikace a databáze.  
- Potřebuje návod, jak aplikaci **aktualizovat**, **řešit problémy** a **zálohovat data**.  

**Možná dokumentace:**  
- **Troubleshooting guide (Řešení problémů)** → Co dělat, když aplikace nefunguje, jak zkontrolovat připojení k databázi.  
- **Postup aktualizace** → Jak nasadit novou verzi aplikace.  
- **Zálohování a obnova databáze** → Jak uchovat historická data. 

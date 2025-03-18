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



# Osnova dokumentace

## 1. Úvod
- Stručný popis aplikace
- Hlavní funkce a cíle aplikace
- Termíny a piktogramy

## 2. Uživatelská dokumentace (rodinný uživatel solární elektrárny)

### 2.1 Přístup do aplikace
- Jak se přihlásit (registrace, přihlašovací údaje)

### 2.2 Navigace v aplikaci
- Hlavní obrazovka a její prvky
- Jak zobrazit aktuální stav solární elektrárny
- Jak pracovat s tabulkami a grafy

### 2.3 Význam zobrazených dat
- Spotřeba vs. výroba energie
- Stav baterií
- Možné interpretace dat

## 3. Technická dokumentace (vývojáři, uživatelé se zájmem o vlastní nasazení aplikace)

### 3.1 Přehled architektury aplikace
- Použité technologie (ASP.NET Core Razor Pages, SQL Server, TailScale)
- Struktura aplikace (databáze)
- Jak aplikace sbírá data

### 3.2 Instalace a nasazení aplikace
- Požadavky na hardware a software
- Instalace Microsoft SQL Serveru
- Konfigurace Intel NUC
- Připojení přes TailScale

### 3.3 Přístup k repozitáři a dokumentaci kódu

## 4. Řešení problémů




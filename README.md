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

1. Úvod  
2. Přístup a přihlášení do aplikace  
   2.1 Přihlášení mimo domácí síť  
3. Jak přidat měřicí zařízení  
4. Jak zobrazit naměřené údaje  
   4.1 Zobrazení údajů z BMS (baterie)  
   4.2 Zobrazení údajů z elektroměru  
5. Správa zařízení a záznamů s naměřenými údaji  
   5.1 Jak zobrazit detail naměřeného záznamu  
   5.2 Jak upravit naměřený záznam/informace o zařízení  
   5.3 Jak smazat naměřený záznam/zařízení  
6. Řešení nejčastějších problémů  
   6.1 Zařízení se nezobrazuje na hlavní stránce  
   6.2 Grafy se nezobrazují  
   6.3 Nelze se připojit z mobilu nebo jiného zařízení  
   6.4 Data v tabulkách nebo grafech nevypadají správně  
   6.5 Nejde se přihlásit do aplikace 






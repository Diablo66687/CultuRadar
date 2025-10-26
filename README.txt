<!--
 DevBrain © | www.devbrain.cz | info@devbrain.cz
 Tento soubor je chránìn licencí DevBrain.
-->

KultuRadar - Pøehled aplikace
=============================

O aplikaci
----------
KultuRadar je webová aplikace pro plánování a sdílení kulturních akcí v Praze. Umožòuje uživatelùm prohlížet akce, filtrovat je podle rùzných kritérií, vytváøet vlastní plány a sdílet je s ostatními.

Hlavní funkce
-------------
- Prohlížení a filtrování kulturních akcí (žánr, nálada, datum, cena)
- Interaktivní mapa akcí (Leaflet.js, GPS souøadnice)
- Uživatelská autentizace (registrace, pøihlášení, odhlášení)
- Plánování akcí (vytváøení, správa a sdílení plánù)
- Sdílení plánù pomocí unikátního odkazu
- Admin rozhraní pro správu akcí (CRUD)
- Seed data:20 pøedpøipravených akcí v Praze

Použité technologie
-------------------
- ASP.NET Core8.0 (Razor Pages)
- Entity Framework Core (SQLite, možnost pøepnout na SQL Server)
- ASP.NET Core Identity (role Admin, User)
- Bootstrap5 (responzivní design)
- Leaflet.js (interaktivní mapa)
- Serilog (logování do souboru a konzole)
- Google Fonts, Bootstrap Icons

Bezpeènost
----------
- Bezpeèné cookies (HttpOnly, Secure, SameSite)
- Anti-CSRF ochrana
- Silná hesla a lockout policy
- HTTPS redirect

Možnosti rozšíøení
------------------
Aplikace je navržena modulárnì a lze ji snadno rozšiøovat:
- Pøidání uploadu obrázkù v admin rozhraní
- Export plánù do kalendáøe (.ics)
- Email notifikace
- Hodnocení a recenze akcí
- Full-text vyhledávání
- API pro mobilní aplikaci
- Integrace s Facebook Events
- Dark mode, responzivní menu

Jak zaèít
---------
1. Otevøete øešení ve Visual Studiu nebo použijte pøíkazovou øádku
2. `dotnet restore` a `dotnet build`
3. `dotnet ef database update` (vytvoøení databáze)
4. `dotnet run` nebo F5

Výchozí admin úèet: admin@kulturadar.cz / Admin123!

Licence
-------
MIT License

Více informací a rychlý start najdete v souboru QUICKSTART.md.

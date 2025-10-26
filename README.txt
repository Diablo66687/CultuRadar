<!--
 DevBrain � | www.devbrain.cz | info@devbrain.cz
 Tento soubor je chr�n�n licenc� DevBrain.
-->

KultuRadar - P�ehled aplikace
=============================

O aplikaci
----------
KultuRadar je webov� aplikace pro pl�nov�n� a sd�len� kulturn�ch akc� v Praze. Umo��uje u�ivatel�m prohl�et akce, filtrovat je podle r�zn�ch krit�ri�, vytv��et vlastn� pl�ny a sd�let je s ostatn�mi.

Hlavn� funkce
-------------
- Prohl�en� a filtrov�n� kulturn�ch akc� (��nr, n�lada, datum, cena)
- Interaktivn� mapa akc� (Leaflet.js, GPS sou�adnice)
- U�ivatelsk� autentizace (registrace, p�ihl�en�, odhl�en�)
- Pl�nov�n� akc� (vytv��en�, spr�va a sd�len� pl�n�)
- Sd�len� pl�n� pomoc� unik�tn�ho odkazu
- Admin rozhran� pro spr�vu akc� (CRUD)
- Seed data:20 p�edp�ipraven�ch akc� v Praze

Pou�it� technologie
-------------------
- ASP.NET Core8.0 (Razor Pages)
- Entity Framework Core (SQLite, mo�nost p�epnout na SQL Server)
- ASP.NET Core Identity (role Admin, User)
- Bootstrap5 (responzivn� design)
- Leaflet.js (interaktivn� mapa)
- Serilog (logov�n� do souboru a konzole)
- Google Fonts, Bootstrap Icons

Bezpe�nost
----------
- Bezpe�n� cookies (HttpOnly, Secure, SameSite)
- Anti-CSRF ochrana
- Siln� hesla a lockout policy
- HTTPS redirect

Mo�nosti roz���en�
------------------
Aplikace je navr�ena modul�rn� a lze ji snadno roz�i�ovat:
- P�id�n� uploadu obr�zk� v admin rozhran�
- Export pl�n� do kalend��e (.ics)
- Email notifikace
- Hodnocen� a recenze akc�
- Full-text vyhled�v�n�
- API pro mobiln� aplikaci
- Integrace s Facebook Events
- Dark mode, responzivn� menu

Jak za��t
---------
1. Otev�ete �e�en� ve Visual Studiu nebo pou�ijte p��kazovou ��dku
2. `dotnet restore` a `dotnet build`
3. `dotnet ef database update` (vytvo�en� datab�ze)
4. `dotnet run` nebo F5

V�choz� admin ��et: admin@kulturadar.cz / Admin123!

Licence
-------
MIT License

V�ce informac� a rychl� start najdete v souboru QUICKSTART.md.

1. DevBrain © | www.devbrain.cz | info@devbrain.cz
This file is protected by the DevBrain license.

KultuRadar - Application Overview
=================================

About the App
-------------
KultuRadar is a web application for planning and sharing cultural events in Prague. It allows users to browse events, filter them by various criteria, create their own plans, and share them with others.

Main Features
-------------
- Browse and filter cultural events (genre, mood, date, price)
- Interactive event map (Leaflet.js, GPS coordinates)
- User authentication (registration, login, logout)
- Event planning (create, manage, and share plans)
- Share plans via unique link
- Admin interface for event management (CRUD)
- Seed data:20 pre-filled events in Prague

Technologies Used
-----------------
- ASP.NET Core8.0 (Razor Pages)
- Entity Framework Core (SQLite, can switch to SQL Server)
- ASP.NET Core Identity (roles: Admin, User)
- Bootstrap5 (responsive design)
- Leaflet.js (interactive map)
- Serilog (file and console logging)
- Google Fonts, Bootstrap Icons

Security
--------
- Secure cookies (HttpOnly, Secure, SameSite)
- Anti-CSRF protection
- Strong password and lockout policy
- HTTPS redirect

Extension Options
-----------------
The app is modular and easy to extend:
- Image upload in admin interface
- Export plans to calendar (.ics)
- Email notifications
- Event ratings and reviews
- Full-text search
- API for mobile app
- Facebook Events integration
- Dark mode, responsive menu

Getting Started
---------------
1. Open the solution in Visual Studio or use the command line
2. `dotnet restore` and `dotnet build`
3. `dotnet ef database update` (create the database)
4. `dotnet run` or F5

Default admin account: admin@kulturadar.cz / Admin123!

License
-------
MIT License

For more information and a quick start, see QUICKSTART.md.

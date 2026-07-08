# SocioNeed Frontend

SocioNeed is a frontend-only Vue 3 + Vite society management system with role-based portals for residents, admins, service providers, and security staff.

## Stack

- Vue 3
- Vite
- Vue Router
- Pinia for simulated auth and notifications

## Run

From the `socioneed` folder:

```bash
npm install
npm run build
```

For local development, start Vite directly from the project folder:

```bash
Set-Location c:\Users\Asus\Desktop\Socioneed\socioneed
& .\node_modules\.bin\vite.cmd --host 127.0.0.1
```

Then open `http://127.0.0.1:5173/`.

## What Is Included

- Public pages: landing, about, services, contact, how it works
- Auth pages: login and register with role-based simulation
- Resident, admin, provider, and security portal screens
- Shared layouts, reusable design tokens, and mock data
- CSS-based charts and status indicators

## Notes

- No backend integration is required.
- All content is driven by local mock data.
- Navigation is handled with Vue Router and route metadata.

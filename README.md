# StackLearn

## INSTALARE (local)

### CERINȚE
- PHP 8.2+ și extensiile necesare pentru Laravel.
- Composer.
- Node.js + npm.
- Un DB (MySQL/PostgreSQL) sau SQLite.

### PAȘI

1) Clonează proiectul:
   git clone <repo-url>
   cd StackLearn

2) Instalează dependențele PHP:
   composer install

3) Creează fișierul de configurare:
   cp .env.example .env

4) Configurează .env (minim DB + APP_URL), apoi generează cheia:
   php artisan key:generate

5) Rulează migrările (și seed, dacă ai):
   php artisan migrate

7) Instalează dependențele frontend:
   npm install

8) Pornește în development (două terminale):
   Terminal 1:
   php artisan serve

   Terminal 2:
   npm run dev

---

## BUILD (producție)
   npm run build

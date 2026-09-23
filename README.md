# Worker Report Site

## Local run
1. Install Node.js 18+
2. Open terminal in this folder
3. Run `npm install`
4. Run `npm start`
5. Open `http://localhost:3000`

## Default accounts
- Admin: `admin` / `admin123`
- Worker: `worker` / `worker`

Change these immediately after setup.

## Render
Create a Web Service, build command `npm install`, start command `npm start`.
For persistent `data.json`, attach a Render persistent disk and mount it at the project root, or replace the JSON database with PostgreSQL/Supabase for production.
Set `SESSION_SECRET` to a long random value.

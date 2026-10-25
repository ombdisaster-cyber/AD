# OMBACIANS V2

A GitHub Pages + Supabase-ready community platform for ST JOSEPH'S COLLEGE OMBACI.

## Quick publish
1. Create a Supabase project.
2. Run `database.sql` in Supabase SQL Editor.
3. Put your Project URL and publishable/anon key in `config.js`.
4. Enable Realtime replication for the `messages` table.
5. Push these files to a GitHub repository.
6. Enable GitHub Pages from `main` and the repository root.

## Important
Never put a Supabase service-role or secret key in `config.js`.
The frontend is designed to use the publishable/anon key with Row Level Security.

Footer credit: JOSH TACH

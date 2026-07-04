GW Capital Partners Full Website Rebuild

Upload everything in this ZIP to the ROOT of your GitHub repository.

Files included:
- index.html
- CNAME
- gw-capital-partners-logo.png, if available
- inventory/index.html
- inventory/app.js
- inventory/config.js
- inventory/supabase_schema.sql

GitHub Pages:
Source: Deploy from a branch
Branch: main
Folder: /root
Custom domain: gwcappartners.com

Public site:
https://gwcappartners.com/

Internal inventory:
https://gwcappartners.com/inventory/

Inventory setup:
1. Create a Supabase project.
2. Go to SQL Editor.
3. Paste inventory/supabase_schema.sql and run it.
4. Go to Supabase Project Settings > API.
5. Copy Project URL and anon public key.
6. Put them into inventory/config.js.
7. Create Jeff/Joe users in Supabase Authentication.

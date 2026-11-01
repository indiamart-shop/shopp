LAVIE WORLD - SUPABASE CONNECTED GITHUB PAGES PACKAGE

Files:
- index.html
- admin/index.html

SUPABASE PROJECT:
- Project URL: https://txekxcededtfhwvxqxno.supabase.co
- Publishable key is configured in both HTML files.

DEPLOY:
1. Extract this ZIP.
2. In GitHub repository indiamart-shop/shopp, upload/replace index.html.
3. Upload/replace admin/index.html (keep the admin folder).
4. Commit changes to the main branch.
5. Wait for GitHub Pages deployment.
6. Storefront: https://indiamart-shop.github.io/shopp/
7. Admin: https://indiamart-shop.github.io/shopp/admin/

ADMIN LOGIN:
- Use the email address and password of the Supabase Auth user you created.
- That user's UUID must already be inserted into public.lavie_admins.
- Your SQL authorization step was completed according to your confirmation.

SETTINGS:
- WhatsApp number, redirect delay, auto redirect toggle, and WhatsApp message are read/written in public.lavie_settings.
- Changes are shared with all visitors/devices after refresh.
- Product message placeholders {product} and {category} are supported.
- GitHub Pages cannot execute PHP; this package uses Supabase from browser JavaScript.

SECURITY:
- The browser code contains only the Supabase Publishable key. This is expected.
- NEVER put a Supabase Secret/service_role key in HTML/JavaScript.
- Keep your Supabase Auth admin password private.
- Supabase RLS policies must remain enabled. Do not disable RLS.
- Admin login requires an authenticated user AND a matching row in public.lavie_admins.

IMPORTANT:
- Automatic redirect is silent and follows the configured delay.
- Test first after deployment. If login or settings fail, check browser console and Supabase API logs.

LAVIE WORLD - GitHub Pages package

Folder structure:
- index.html          Main storefront
- admin/index.html    Admin panel (opens at /<repository-name>/admin/)

Publishing:
1. Upload index.html and the admin folder (containing index.html) to the root of your GitHub repository.
2. Open Settings -> Pages.
3. Select Deploy from a branch, select your main branch and /(root), then Save.
4. Your storefront URL is https://USERNAME.github.io/REPOSITORY/
5. Your admin URL is https://USERNAME.github.io/REPOSITORY/admin/

The admin layout follows the original PHP page's section order. No GitHub information panel is displayed inside the admin panel.

IMPORTANT TECHNICAL LIMITATION:
GitHub Pages cannot execute PHP. This HTML version stores settings in localStorage, so the storefront and admin share the settings in the same browser/device. Timer and silent auto-redirect are implemented. No popup, visible countdown, or Cancel button is shown on the storefront. Settings saved by the admin do not update other visitors' browsers. The local admin password is only a convenience and is not secure server-side authentication. Shared settings for all visitors and secure authentication require a backend/API or PHP-capable hosting.

Replace the sample WhatsApp number 919876543210 with your actual number before publishing. Developer support number in the admin footer is currently 917027395027; replace it if needed.

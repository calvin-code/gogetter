Hostinger Deployment Extras
============================

Included files:
- sitemap.xml — built from 5 URL(s). Update the domain inside if needed.
- robots.txt — references your sitemap URL.
- .htaccess — disables directory listing, adds HTTPS redirect, cache headers, compression, and basic security headers.

How to use:
1) Upload **sitemap.xml**, **robots.txt**, and **.htaccess** to your site's **public_html** (or the root of your domain/subdomain) in Hostinger File Manager or via FTP.
2) Replace `https://yourdomain.com` inside **sitemap.xml** and **robots.txt** with your real domain.
3) If you use a subfolder for your site, ensure the files go into that folder and domain paths are correct.
4) After upload, submit your sitemap URL to Google Search Console and Bing Webmaster Tools:
   - https://www.google.com/webmasters/tools/home
   - https://www.bing.com/webmasters/
5) To verify directory listing is disabled, try visiting a folder URL without an index file; you should NOT see a file list.
6) If your site is a Single Page App, you may want to add rewrite rules for `index.html`. Let me know and I can generate that too.

Generated on: 2025-09-26

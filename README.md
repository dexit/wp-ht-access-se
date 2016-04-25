# Crafted for Wordpress, a HTaccess file
Hardening Wordpress is a must. Reading 1000x blogs is tiresome.
Let this help you in your journey of less sleepless nights.
Use it as you wish, commit and fork, and lets make the web safer.

- .htaccess is a full working compilation
- .htaccess-extended is for developing, not fully tested

##WhaT?
- Anti- basic SQL injects through urls
- Anti- base64 execution
- Anti- Global rewritting
- Anti- Fingerprinting (just general)
- Anti- Botnet User agent list
- Anti- XSS also very simple
- Directory viewing/listing restrictions (even thou CHMOD is 755,777)
- And a lot more

# ToDo
- [HIGH] Protect also from execution of all languages not ph
- [HIGH] Protect execution from the uploads directory (but do serve the file) 
- [HIGH] Protect from execution on the plugins and themes directory.
- [HIGH] Protect wp-includes
- Add hotlinking script (http://corz.org/server/tools/auto-hot-link/)
- Add more anti's
- Optimization for SEO
- Structurize the file itself :P

#Live Action

You can see/gtmetrix a working site : http://scriptin.me

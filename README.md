#CodeIgniter-.htaccess

A .htaccess file to be used with CodeIgniter

This .htaccess file allows CodeIgniter URLs to be shortened to remove the `index.php/`
segment and all assets to be kept in `/assets` in the web root.

Allows for `robots.txt` and `favicon.ico` to be grabbed as normal.

It contains fixes for some WebFont loading issues I was having but these may not be required by all.

The www rewrite rule is from http://www.farinspace.com/codeigniter-htaccess-file/

####Remember to swap out `domain.tld` for your domain

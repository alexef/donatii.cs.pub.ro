== 2012-12-08 - Mircea Bardac ==
* (index.php) support for web browsers where the FB plugin is disbled (asynchronously replaced plugin with link to the page)
* (index.php) support for the Facebook OpenGraph Protocol (https://developers.facebook.com/docs/opengraphprotocol/) - site image displayed when sharing the website + URL, title, initiative description - verified on: https://developers.facebook.com/tools/debug
* (2010,2011,current/contact.php) removed all phone numbers
* (index.php) replaced link "anii trecuți" to point instead of "https://craciun2008.wordpress.com/" to the Facebook Page
* (index.php) added "cărți și rechizite"
* (contact.php) changed contact persons and availability intervals
* (index.php) scos "vă invităm să mergeți cu noi..."
* (all) changed fonts to Google Web Fonts: 'Noticia Text' for the headings and 'Open Sans' for the body (dropped Cambria via Cufon & Verdana)
* (all) fixed footer left/right text padding

== 2010-12-15 - Mircea Bardac ==
* added favicon.ico:
  * free for non-commercial use
  * http://www.iconarchive.com/show/standard-new-year-icons-by-aha-soft/Present-icon.html


== 2011-01-29 - Mircea Bardac ==

0. backup old ~/www to ~/www-backup-2011-01-28

1. (generic: menu.inc.php) link-ul "Donează pentru copii" din meniu indică acum către "/", înainte indica la "/index.php".

2. (index.php, craciun.php) "să realizăm ceva cel puțin la fel de frumos ca anii trecuți." => "să realizăm ceva cel puțin la fel de frumos ca în anii trecuți."

3. (index.php) "merg spre căminul Sf. Macrinadin București" => "merg spre căminul Sf. Macrina din București"

4. (index.php, craciun.php) "să ne insoțițiși să le facem o vizită celor mici" => "să ne însoțiți să le facem o vizită celor mici"

5. (index.php, craciun.php) "Ajutoarele merg spre căminul Sf. Macrina" - "Sf. Macrina" pe un rând, nu separat pe 2 rânduri

6. (index.php) "Jucării, dulciuri și hăinuțe." => "Hăinuțe, cărți, rechizite și jucării."

7. (index.php, craciun.php) făcut link "pagina de Facebook" de la "Promovați acest site"

8. (contact.php) - mici modificări de așezare în pagină a textului

9. (index.php) paragraful cu "Darurile de Crăciun i-au bucurat…" - propoziții separate câte una pe rând

10. (index.php) mutat "Automatică și Calculatoare și nu numai" pe un rând separat, să nu se mai suprapună "și" peste poză

11. (generic: style.css) adăugat ('Geneva', sans-serif) ca alternative la 'Verdana', pentru situațiile când nu există Verdana în sistem

12. (index.php)  micșorat un pic fontul pentru "Ajută-i să învețe în condiții normale" pentru a nu se suprapune peste poză

13. (index.php, craciun.php) - scos footer-ul comun într-un fișier separat: footer.inc.php

14. (contact.php) - înlocuit "Copyright © 2010 - Universitatea Politehnica București" cu footer-ul comun <?php include('footer.inc.php'); ?>


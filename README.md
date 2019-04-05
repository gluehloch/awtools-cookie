# awtools-cookie
AWTools Cookie Text

### Apache Konfiguration
Das Modul 'headers' muss aktiviert sein: `a2enmod headers`. Im Anschluss wird
der Webserver neu gestartet.

.htaccess
'''
<IfModule mod_headers.c>
    Header set Access-Control-Allow-Origin "*"
</IfModule>


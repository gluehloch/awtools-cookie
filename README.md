# awtools-cookie
AWTools Cookie Text

### Apache Konfiguration
Das Modul 'headers' muss aktiviert sein: `a2enmod headers`. Im Anschluss wird
der Webserver neu gestartet.

Die folgenden `.htaccess` Datei muss im Wurzelverzeichnis der Anwendung liegen,
damit externe Seiten auf die Resourcen zugreifen können (CORS).
```
<IfModule mod_headers.c>
    Header set Access-Control-Allow-Origin "*"
</IfModule>
```

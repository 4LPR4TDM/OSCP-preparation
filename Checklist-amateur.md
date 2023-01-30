# Reconocimiento

## OSINT
- [ ] Historial web (Cacheado de web)
- [ ] Dorks
- [ ] Enumeración de correos
	- [ ] hunter
	- [ ] theharvester
	- [ ] recon-ng
- [ ] Wayback

## Fingerprinting web server
- [ ] Consulta DNS
	- [ ] dnsmap
	- [ ] nslookup
	- [ ] dnsdumpster
- [ ] Consulta WHOIS
- [ ] Análisis de la estructura del sitio
	- [ ] Inspeccionar elemento
	- [ ] ZAP spider
- [ ] Reverse IP Lookup
	- [ ] shodan
- [ ] Tecnologías backend y frontend
	- [ ] Wappalizer
- [ ] Tipo de servidor web
	- [ ] whatweb
- [ ] Versión de servidor web
	- [ ] whatweb
	- [ ] cokiees
	- [ ] netcraft
- [ ] Headers
- [ ] Inspeccionar URL
	- [ ] Terminación de .


## Metafiles
- [ ] robots.txt
- [ ] sitemap.xml
	- [ ] Burp Suite
	- [ ] Httrack
- [ ] humans.txt
- [ ] security.txt

## Identificar entry points
- [ ] Metodos usados en el area
- [ ] Identificar posibles inyecciones
	- [ ] js

	- [ ] sql
	- [ ] html

## Escaneo activo
- [ ] Escaneo de puertos
	- [ ] nmap
	- [ ] netcat
- [ ] Enumeración de directorios
	- [ ] dirb
	- [ ] dirsearch
- [ ] Enumeración de subdominios 
	- [ ] sublister
	- [ ] dnsmap
- [ ] Identificar WAF (wafw00f)
- [ ] SSLscan
- [ ] wfuzz

# Checklist de dominios
- [ ] Autenticación 
	- [ ] Error User Harvesting
	- [ ] Brute force
- [ ] Manejo de sesiones
	- [ ] Sesiones estaticas
	- [ ] sesion fixation
- [ ] Manejo de archivos
	- [ ] LFI
	- [ ] RFI
- [ ] Validación de entradas
	- [ ] Path Traversal
	- [ ] Comand Injection
	- [ ] XSS reflected
	- [ ] XSS Storage
	- [ ] SQLi
- [ ] Criptografia
	- [ ] Valor semilla agregado
- [ ] Gestión  de configuraciones

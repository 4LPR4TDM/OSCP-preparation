## Funcionamiento del sitio

# Reconocimiento

### whois 
```sh

```
### whatweb - Headers
```sh


```
### Analisis del sitio
Inspeccionar elemento
```html

```
ZAP spider
```html

```
Formulario de logueo
```html

```

### Reverse IP - Shodan

### Tecnologias backend y frontend - Wappalizer
```plaintext

```

### Servidor web
Cookies
```plaintext

```

### Inspeccionar la URL
Terminacion en URL

### Entry points
Metodos por area
```http

```
Posibles inyecciones



## Escaneo de puertos

nmap
```sh

```

netcat
```sh

```

## Enumeración de directorios
dirb
```sh

```

## Enumeración de subdominios

sublister
```sh

```


### Identificar WAF

wafw00f
```sh

```

### Fuzzing
wfuzz
```sh

```
### Proxy
# Explotacion
si
# Dominios
## A01:2021-Broken Access Control
- [ ] IDOR
- [ ] /wp-admin
## A02:2021-Cryptographic Failures
- [ ] Archivo plano almacenado
- [ ] hash crackeado
## A03:2021-Injection
- [ ] XSS
- [ ] SQLi
- [ ] OSi
- [ ] Path Trafversal
- [ ] LFI
- [ ] RFI
## A04:2021-Insecure Design
- [ ] Preguntas de recuperacion de password
## A05:2021-Security Misconfiguration
- [ ] XXE XML Eternal Entities
- [ ] Permisos mal configurados en S3
- [ ] Cuentas por defecto sin cambios de contrase;as
- [ ] Mensajes de error detallados
- [ ] Demasiada informacion en el encabezado HTTP
- [ ] Listado de directorios
## A06:2021-Vulnerable and Outdated Components
- [ ] Exploit documentado
## A07:2021-Identification and Authentication Failures
- [ ] Ataque de fuerza bruta
- [ ] Credenciales debiles
- [ ] Cookies de sesion debiles
- [ ] Preguntas para recuperacion de contrase;as
- [ ] Identificador en URL
- [ ] Session fixation
- [ ] Sesiones estaticas
## A08:2021-Software and Data Integrity Failures
- [ ] Insecure Deserialisation
- [ ] Actualizaciones no firmadas
## A09:2021-Security Logging and Monitoring Failures
- [ ] Falta de monitoreo
## A10:2021-Server-Side Request Forgery (SSRF) 
- [ ] SSRF
# Flags

# Notas

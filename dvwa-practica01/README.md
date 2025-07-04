# Práctica 01 - Ciberseguridad con Kali + Docker

## Herramienta utilizada: Nmap

### Comando ejecutado:
```bash
nmap -sS -sV -O -p- host.docker.internal -oN escaneo_nmap.txt
#Se detectaron los puertos abiertos del servidor DVWA y su tecnología base. El reporte está en el archivo escaneo_nmap.txt

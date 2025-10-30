# Ejercicios Redes Linux

## Muestra todas las interfaces de red activas y sus direcciones IP en el sistema.

```bash
ip a
```

## ¿Cómo mostrarías solo la información de la interfaz de red `eth0` usando `ip a`?

```bash
ip a show eth
```

## Configura manualmente la dirección IP `192.168.1.100/24` en la interfaz `eth0` con `ifconfig`.

```bash
sudo ifconfig eth0 192.168.1.100 netmask 255.255.255.0 up
```

## Envía 10 paquetes ICMP a la dirección IP `8.8.8.8` usando `ping`.

```bash
ping -c 10 8.8.8.8
```

## Consulta la dirección IP de `www.example.com` usando `nslookup`.

```bash
nslookup www.example.com
```

## Muestra las conexiones TCP activas en el sistema usando `netstat`.

```bash
netstat -t
```

## Descarga el contenido de la página principal de `www.example.com` usando `curl` y guárdalo en un archivo llamado `example.html`.

```bash
curl www.example.com -o example.html
```

## Consulta el nombre del host actual del sistema.

```bash
hostname
```

## Obtén la información de registro del dominio `example.com` usando `whois`.

```bash
whois example.com
```

## Cambia temporalmente el nombre del host a `servidor01` usando `hostname`.

```bash
sudo hostname servidor01
```
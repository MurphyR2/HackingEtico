# IP
Una dirección IP es un número de 32 bits que identifica a cada computador en una red.
## Comandos
En linux puedes utilizar:

```bash
ifconfig
ip a
hostname -I
curl ifconfig.me 
```

Podemos convertir el número a binario con:
```bash
echo "$(echo "obase=2;192" | bc)"
```
## IPv6
Tenemos 
```bash
echo "2^128"|bc
```

# MAC
Es un único identificador físico.
OUI: Organizational Unique Identifier 
### Herramientas
Para hacer un escaneo de direcciones MAC:
```bash
arp-scan -I ens03
macchanger -L | grep -i vmware
```
# TCP
Para abrir wireshark
```bash
wireshar &> /dev/null &disown
```

$

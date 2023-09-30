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

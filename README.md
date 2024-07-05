# IPsVE
Lista y script para router Mikrotik de IPs Venezolanas.


## Uso del script.
- Descarga desde https://raw.githubusercontent.com/dalejos/IPsVE/main/scripts/address-list.rsc
- Instalar en /system/script
- Correr el script /system/script/run address-list

## Variables de configuracion del script

### URL de la lista de IP, segmentos, AS y dominios.
- :local urlFile "https://raw.githubusercontent.com/dalejos/IPsVE/main/listas/lista.txt";

### Nombre del archivo local donde se guardara la lista.
- :local fileName "lista.txt";

### Nombre de la lista para crear en /ip/firewall/address-list/
- :local listName "bancos";

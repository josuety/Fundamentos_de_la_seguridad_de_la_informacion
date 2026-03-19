# Reto 
### Printer Shares
# Descripción 
Oops! Someone accidentally sent an important file to a network printer—can you retrieve it from the print server?The printer is on `49246`.you can try `$ nc -vz mysterious-sea.picoctf.net 49246`
# Solución
picoCTF{5mb_pr1nter_5h4re5_b3f2f855}
# Notas adicionales
use el comando "nmap -p 49246 --script smb* mysterious-sea.picoctf.net"
lance un nmap para el escaneo de redes por el puerto 49246 usando un scrip  smb, con direccion 

Después use "smbclient //mysterious-sea.picoctf.net/shares -p 49246 -N" en donde use el comando smbclient "a la dirección especificada" -p "por dicho puerto " -N "de forma anonima"
y donde despues entre como a una maquina virual y podia ejecuar comandos y ya solo le di ls y vi la flag.txt y le hice un more y listo me dio la flag



# Referencias


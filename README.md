# IA Basica Fisica

Se sustituye el tanque npc por una torre, usando un cilindro básico como base y la torreta del tanque.

La torre reutiliza casi todo el código del tanque npc, eliminando el código que determina el movimiento, y usando como referencia de posición la torreta en lugar de la estructura principal (se añade un pequeño offset hacia arriba para compensar la diferencia de altura)

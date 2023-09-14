# allocationFrequence
On désire attribuer des fréquences à n stations émettrices. A cause des interférences, deux stations
distantes de moins de dmin km ne peuvent émettre avec la même fréquence. Connaissant la position
des stations, combien faut-il de fréquences distinctes et comment les attribuer aux différentes
stations ?

On peut représenter ce problème sous forme d’un graphe dans lequel les sommets sont les
stations et deux stations sont adjacentes si elles sont trop rapprochées pour émettre à la même
fréquence. On appellera ce graphe « graphe d’interférence ».
Il sera représenté par listes d’adjacence : chaque sommet possède la liste de ses sommets
adjacents (chaque station possède la liste des stations avec lesquelles elle interfère).

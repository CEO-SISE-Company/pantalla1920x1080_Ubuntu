# pantalla1920x1080_Ubuntu
Código de referencia para automatizar el ajuste de pantalla en Ubuntu 20.10 a 1920x1080

#para obtener la información de la pantalla
primero, ingrese en una terminal el siguiente comando: cvt <ancho> <alto>
segundo, de la segunda línea obtena la información de Modeline tal que así: "1920x1080_60.00"  173.00  1920 2048 2248 2576  1080 1083 1088 1120 -hsync +vsync
esa información es la que debe ir en la primera línea del código resizer.sh

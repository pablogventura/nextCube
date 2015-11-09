28/10/15
###Un poquito de historia, curiosidades y caprichos del Tio Steve.
NeXT Computer, Inc. fue fundada por Steve Jobs en 1985 después de su forzada renuncia a Apple, obvio después Apple la compró en 1997.
El software desarrollado por Next es la base para el sistema operativo Mac OS X.
El NeXT Computer fue usado por Tim Berners-Lee en el CERN y llegó a ser el primer servidor y el primer navegador web.
A principios de 1990 John Carmack utilizó una NeXTcube para la construcción de dos de sus juegos pioneros, Wolfenstein 3D y Doom.
"En 1987, NeXT terminó la construcción de una fábrica totalmente automatizada en Fremont para su primer producto, el NeXTcube. Las historias sobre las demandas de Jobs para la fábrica y el cubo ahora son leyenda, incluyendo repintar la fábrica varias veces para conseguir el color gris correcto, y la aplicación de una serie de cambios en la cadena de producción que traían una pérdida de tiempo de modo que la costosa caja de magnesio del cubo tuviera bordes en ángulo recto perfectos." (Textual de la wiki).

####Hardware
Funcionan todos los cables CPU-Monitor, CPU-corriente, todos los teclados (3), monitor model N4000A Part N°1403 mejor que monitor model N400B Part N°4619 (imagen distorsionada con rayas horizontales), monitor N4000 Part N°135.00 no sirve (sé ve muuuy poco y en sólo 3/4 de la pantalla).

#####CPU 0: 
 * Prende! Pero se queda en "Loading from Network". 
 * [NeXTcube Turbo](https://en.wikipedia.org/wiki/NeXTcube_Turbo)
 + Fuente: NeXT Part N° 983 serie AAB0016575.
 + Motherboard: NeXT Inc (1991) PN 4644.AA N° ADA0010168. 
   * RAM?
   * CPU: [Motorola 68040, 33MHz](https://en.wikipedia.org/wiki/Motorola_68040) with integrated [floating point unit](https://en.wikipedia.org/wiki/Floating-point_unit)
![20151106_112126.jpg](https://bitbucket.org/repo/b46q7y/images/3015795550-20151106_112126.jpg)CPU: 33 MHz 68040 with integrated floating-point unit
 + Hard drive: Maxtor corporation (1985), model XT-87605, capacidad 260Mb, N° 5850251.
 + más algo que supongo es lectora de diskette (floppy disk).

#####CPU1: 
 * No prende, estaba todo desconectado. Tampoco funciona conectando.
 + [NeXTcube](https://es.wikipedia.org/wiki/NeXTcube)
 + Fuente: Falta anotar esta info.
 + Motherboard: NeXT Inc (1990) PN-1698.AE N° AAX0011193. 
   * 16MB de RAM
   * PC: [Motorola 68040, 25 MHz](https://en.wikipedia.org/wiki/Motorola_68040)
![20151106_112059.jpg](https://bitbuchttp://www.datasheetarchive.com/PC68040-datasheet.htmlket.org/repo/b46q7y/image/4149666494-20151106_112059.jpg)
 + Hard drive: NEXT Optical Drive, model N3000, capacidad 256Mb, N° AAD0007082.
 + Hard drive: Seagate Technology Inc, model ST41650N, N°ABF0500281, capacidad SIN INFO supongo [esto](https://th99.bl4ckb0x.de/h/txt/4332.txt).

#####Cambio de hardware:
 + Motherboard PN-1698.AE + Fuente 983 + Hard drive Seagate ST41650N : Prende! Pero se queda en "Boot device not found" (en la PROM).
 + Motherboard PN-1698.AE + Fuente 983 +  Hard drive NEXT Optical Drive N3000: Prende! Pero se queda en "Boot devide not found"(en la PROM).

#####Queda para desarmar y ver:
  + Problema en la fuente de CPU1? 
  + Lectora de diskette?

####Software
Sin éxito de booteo hasta ahora. Se queda en "Loading from network" o "Boot device not found" o "Default boot device not found".


#####PROM console: 
 + Se accede con "command"+"tilde eñe".
 + h->despliega lista de monitor commands.
 + p->permite inspeccionar y cambiar algunas configuraciones.. 

####algunos links:
+ http://www.dudek.org/blog/35
+ [How to boot a NeXTCube from Linux](http://www.nextcomputers.org/forums/viewtopic.php?t=2965)
+ [NeXTCube wiki](https://es.wikipedia.org/wiki/NeXTcube)
+ [NeXT wiki](https://es.wikipedia.org/wiki/NeXT#Primera_generaci.http://www.nextcomputers.org/NeXTfiles/Software/Diagnostic_Utilities/68040_manual.pdfC3.B3n)
+ [Algo para el "Loading from Network"](http://www.nextcomputers.org/forums/viewtopic.php?t=3686&sid=4e791aba2adb2f98a71e4f8c086327e5)
+ [EL foro](http://www.nextcomputers.org/forums/index.php?sid=833c7dd986b580141ab059bbedba8997)
+ [Hardware reference](https://docs.google.com/document/d/1CmCQ5rdU69MtfVcfgxzJ5aLT7VnopSbywILZrK9B_Ko/edit)
+ [Software!!](http://www.nextcomputers.org/NeXTfiles/Software/)
+ [Artículos](http://www.nextcomputers.org/NeXTfiles/Articles/)
+ [Patentes](http://www.nextcomputers.org/NeXTfiles/Articles/)
+ [68040_manual](http://www.nextcomputers.org/NeXTfiles/Software/Diagnostic_Utilities/68040_manual.pdf)
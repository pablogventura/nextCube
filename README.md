28/10/15

####Hardware
Funcionan todos los cables CPU-Monitor, CPU-corriente, todos los teclados (3), monitor model N4000A Part N°1403 mejor que monitor model N400B Part N°4619 (imagen distorsionada con rayas horizontales).

#####CPU 0: 
 * Prende! Pero se queda en "Loading from Network". 
 + Fuente: NeXT Part N° 983 serie AAB0016575.
 + Motherboard: NeXT Inc (1991) PN 4644.AA N° ADA0010168.
 + Hard drive: Maxtor corporation (1985), model XT-87605, capacidad 260Mb, N° 5850251.
 + más algo que supongo es lectora de diskette (floppy disk).

#####CPU1: 
 * No prende, estaba todo desconectado. Tampoco funciona conectando.
 + Fuente: Falta anotar esta info.
 + Motherboard: NeXT Inc (1990) PN-1698.AE N° AAX0011193.
 + Hard drive: NEXT Optical Drive, model N3000, capacidad 256Mb, N° AAD0007082.
 + Hard drive: Seagate Technology Inc, model ST41650N, N°ABF0500281, capacidad SIN INFO supongo [esto](https://th99.bl4ckb0x.de/h/txt/4332.txt).

#####Cambio de hardware:
 + Motherboard PN-1698.AE + Fuente 983 + Hard drive Seagate ST41650N : Prende! Pero se queda en "Boot device not found" (en la PROM).
 + Motherboard PN-1698.AE + Fuente 983 +  Hard drive NEXT Optical Drive N3000: Prende! Pero se queda en "Boot devide not found"(en la PROM).

#####Queda para desarmar y ver:
  + Problema en la fuente de CPU1? 
  + Lectora de diskette?

####Software
Sin éxito de booteo hasta ahora. Se queda en "Loading from network" o "Boot device not found".

#####PROM console: 
 + Se accede con "command"+"tilde eñe".
 + h->despliega lista de monitor commands.
 + p->permite inspeccionar y cambiar algunas configuraciones.. 

####algunos links:
+ http://www.dudek.org/blog/35
+ [How to boot a NeXTCube from Linux](http://www.nextcomputers.org/forums/viewtopic.php?t=2965)
+ [NeXTCube wiki](https://es.wikipedia.org/wiki/NeXTcube)
+ [NeXT wiki](https://es.wikipedia.org/wiki/NeXT#Primera_generaci.C3.B3n)
+ [Algo para el "Loading from Network"](http://www.nextcomputers.org/forums/viewtopic.php?t=3686&sid=4e791aba2adb2f98a71e4f8c086327e5)
+ [EL foro](http://www.nextcomputers.org/forums/index.php?sid=833c7dd986b580141ab059bbedba8997)
+ [Hardware reference](https://docs.google.com/document/d/1CmCQ5rdU69MtfVcfgxzJ5aLT7VnopSbywILZrK9B_Ko/edit)
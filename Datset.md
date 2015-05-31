#Dataset del Turkey2010 obtenido de Twitter

# Introdución #


# Fuente #
Se han extraído los tweets de las 15:20 del 28-ago-2010 a las 18:15:06  del 13-sep-2010 con el **Streaming API** de Twitter seleccionando los siguientes palabras claves :

```
     basket    #basket    baloncesto    #baloncesto    basketball    #basketball
     Turkey2010    #Turkey2010    FIBA2010    #FIBA2010    
     #ang    #arg    #aus    #bra    #can    #chn    #civ    #cro    #esp    #fra
     #ger    #gre    #iri    #jor    #lib    #ltu    #nzl    #pur    #rus    #slo 
     #srb    #tun    #tur    #usa
```

Al analizar los datos se han encontrados los siguientes problemas:

  * **Ambiguación**: Los hashtag de países se utilizan para diferentes significados y los otros a veces van asociados a venta de productos
  * **Spam**: usuarios que envían siempre el mismo mensaje
  * **Exceso de información**: si se le pide al API de Twiter que me de #usa, devuelve todos los tweets que tiene la palabra usa o que tiene  una url con la palabra usa.

Se ha utilizado un filtro para excluir autores, hashtags o palabras que puedan tener distinto significado y se han extraído los tweets que cumplen exclusivamente con las búsqueda solicitada. Este es el resultado cuantitativo del filtrado:

```
                    683.289 tweets obtenidos
                    209.585 tweets seleccionados

```


# Datos elaborados #

Contenido:
  * Usuarios más activos
  * Palabras más usadas
  * Aplicaciones  utilizadas
  * Jugadores más mencionados
  * Menciones a países
Desglose:
  * Total
  * Día
  * Hora
Formatos:
  * Tabla con valores:
    * Valores por día:[turkey2010\_day\_count](https://spreadsheets.google.com/ccc?key=0AvqG-02OdbLbdE41c2RTWkRDdkx5M3NiZHB2WVhELVE&hl=en&authkey=CPHt-pcF)
    * Valores por hora: [turkey2010\_hour\_count](https://spreadsheets.google.com/ccc?key=0AvqG-02OdbLbdGVqSmVMWThBc2lNUVRyV1l2V3lkNUE&hl=en&authkey=CL6iyPsJ)
  * Tabla con porcentajes:
    * Valores por día: [turkey2010\_day\_percent](https://spreadsheets.google.com/ccc?key=0AvqG-02OdbLbdE9SREZaU3cyLVBDaThrdzFBWFRXT1E&hl=en&authkey=CNra4LYM)
    * Valores por hora: [turkey2010\_hour\_percent](https://spreadsheets.google.com/ccc?key=0AvqG-02OdbLbdFgwNm5pdl9tQ3BqMG5jeWRQcDV3b2c&hl=en&authkey=CO_Kx70O)
  * Lista con valores y porcentaje:
    * Valores totales: [Turkey2010\_total](https://spreadsheets.google.com/ccc?key=0AvqG-02OdbLbdFZKZ3k2clQ2Nkxad1NWZVJSQkJBWGc&hl=en&authkey=CIL054gM)
    * Valores por día: [turley\_day\_list](https://spreadsheets.google.com/ccc?key=0AvqG-02OdbLbdE9XRmE5UnFZLU5qQ3M4MXp1aEVFNXc&hl=en&authkey=CPrvtSk)
    * Valores por hora: Demasiado grande para google docs.
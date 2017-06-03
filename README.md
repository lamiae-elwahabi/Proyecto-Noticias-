# Proyecto Noticias
### Objectiu final: Realitzar una aplicació web de notícies que, en fer scroll fins abaix, recarregui més notícies amb html, jQuery i Bootstrap.


### Abans de començar:

Es recomana l'ús d'un quadern per fer un disseny i el seguiment del desenvolupament de l'aplicació. Recordeu que vos examinareu per escrit.

Per disssenyar i programar primer ho feim al quadern, i quan ho tenim clar, es traduiex a l'ordinador.


### Especificacions del client:

La maquetació (layer design) ha de deixar 300 px d'espai a la dreta de la pantalla per publicitat si la pantalla és suficientment ample. Tot altre diseny és lliure.
Per dispositius mòbils, la publicitat anirá fixada a la part inferior o bé només es mostrará a la part superior (i desapareixerà en fer scroll) amb un alt de 90px. Pots triar l'opció. Tot altre diseny és lliure.
Les dades són: títol (entorn a 8 paraules), imgbig (url al json, imatge a la carpeta), imgmid (url al json, imatge a la carpeta), descripció (mínim de 300 caràcters), data i hora (datetime).
Totes les notícies han de tenir el mateix format i mostrar les dades especificades de forma elegant a tot dispositiu.
Tasques:

Realitza la maquetació del projecte. Entrega un breu document amb l'análisi i la planificació al README.md (valen fotos d'esquemes del quadern).
(fins a 2 punts)
Presenta news.html amb 3 notícies (ja escrites al html, no carregar amb js) i emmagatzema 6 noticies més en dos fitxers, data/1.json data/2.json per ser carregades amb js.
(fins a 2 punts)
Codifica news.js en jQuery per fer: "botó carregar més notícies" i "scroll bottom" que, en ser activat qualsevol d'ells, faci una càrrega i presentació de més dades (fins a dues vegades 1.json, 2.json)
(fins a 1 punt)
Inclou rss.xml (especificat al tema 6)
(fins a 1 punt)
Codifica news1.html i news2.html, pàgines que corresponen a les dues primeres noticies (darreres publicades). Quan feim clic a la notícia 1 de news.html ens va a news1.html, quan feim clic a la notícia 2 de news.html ens va a news2.html (seguir no té sentit, aquesta tasca s'automatitza amb codi de servidor).
(fins a 1 punt)
La plantilla o pàgina de veure una sola notícia news1.html (news2.html és idèntica) ha de contenir una imatge i un vídeo de youtube responsive. 
(fins a 1 punt)
Cada pàgina ha de contenir les etiquetes meta (amb open graph) per compartir títol, descripció, imatge (gran), nom de l'aplicació i url de la pàgina. 
(fins a 1 punt)
Fins a + 2 punts: acabat final (o dit d'un altra forma: complir les especificacions del client o donar solucions elegants alternatives)

# Analisis y planificación de mi proyecto

Página web de noticias auto rellenable con scroll (Bootstrap, jQuery, Json, HTML, CSS)

#### Hice un dibujo de la idea principal como será mi pagina en escritorio y en movil  
![dsc_0198](https://cloud.githubusercontent.com/assets/22870341/26745635/b26be2ec-47eb-11e7-9ff6-336a471446be.jpg)

#### Después de tener más claro el diseño hice este segundo imagen
![dsc_0197](https://cloud.githubusercontent.com/assets/22870341/26745636/b26c7338-47eb-11e7-90ee-5f098ade1427.jpg)
 
 #### Trabajo realizado
 * La página principal news.html carga 3 notícias y al hacer scroll apretando el buton cargar mas noticia, carga 3 notícas más desde el   json hasta dos veces.
* Publicidad a la dercha con 300px de width para versión escritorio.
* Publicidad abajo de la página con un 90px de altura
* Las primeras dos notícias del news.html, tienen enlace a otro news1.html y news2.html, donde se muestra la nóticia en detalles (con la   image-respnsive grande y un video-responsive de 16:9)
* El news.html incluye un enlace a rss.xml,que lo valide.
* Las tres pagínas contienen etiquetas OpenGraph para compartir la notícia.
* Decide en eligir el tema de noticias sobre la ciencia y la biologia.
* La pagina le elige un background de cromosomas, intente que los colores se queden relacionados entre si y tambien relacionados con el tema.
* Fue recogiendo noticias de la pagina que mencione abajo.
* Hice un menu de diferentes ramas de biologia que son link eternos.
* Añade unos iconos de redes sociales.
# Recursos consultados

**Paginas consultadas para recoger mis noticias**

http://noticiasdelaciencia.com/sec/ciencia/biologia/   
http://noticiasdelaciencia.com/not/24187/una-inesperada-funcion-para-una-region-cerebral/

**Paginas consultadas para la ayuda**  
https://www.w3schools.com/bootstrap/default.asp

https://www.w3schools.com/jquery/default.asp

http://librosweb.es/tutoriales/pagina-2

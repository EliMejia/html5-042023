**CONTENEDORES DE VÍDEO


Un archivo de video generalmente contiene varias pistas : una pista de video (sin audio), más una o más pistas de audio (sin video). Las pistas suelen estar
interrelacionadas. Una pista de audio contiene marcadores dentro de ella para ayudar a sincronizar el audio con el video. Las pistas individuales pueden tener
metadatos, como la relación de aspecto de una pista de video o el idioma de una pista de audio. Los contenedores también pueden tener metadatos, como el título
del video en sí, la portada del video, los números de episodio.

Hay muchos formatos de contenedores de video. Algunos de los más populares incluyen

*MPEG 4 , generalmente con una extensión .mp4o . .m4vEl contenedor MPEG 4 se basa en el antiguo contenedor QuickTime de Apple ( .mov). 

*Ogg , generalmente con una .ogvextensión. Ogg es un estándar abierto, amigable con el código abierto y libre de patentes conocidas. Compatible con Firefox 3.5,
Chrome 4 y Opera 10.5, de forma nativa, sin complementos específicos de la plataforma, el formato de contenedor Ogg, video Ogg (llamado "Theora") y audio Ogg
(llamado "Vorbis"). En el escritorio, Ogg es compatible de forma inmediata con todas las principales distribuciones de Linux, y puede usarlo en Mac y Windows
instalando los componentes de QuickTime o los filtros de DirectShow , respectivamente. También se puede jugar con el excelente VLC en todas las plataformas.

*Flash Video , generalmente con una .flvextensión. Flash Video es utilizado por Adobe Flash. Antes de Flash 9.0.60.184 (también conocido como
Flash Player 9 Update 3), este era el único formato de contenedor compatible con Flash. Todas las versiones recientes de Flash también son compatibles con el contenedor
MPEG 4.

*WebM , generalmente con una .webmextensión. WebM es una compresión de video libre de regalías y de código abierto diseñada específicamente para usar con video HTML5,
aprovechando el códec de video VP8 y el códec de audio Vorbis. Es técnicamente similar a otro formato, llamado Matroska . Es compatible de forma nativa, sin complementos
específicos de la plataforma, en las últimas versiones de Chromium, Google Chrome, Mozilla Firefox y Opera.

*ASF , generalmente con una .asfextensión. El formato de contenedor ASF fue inventado por Microsoft para la transmisión de video. Incluía un delicioso esquema DRM
que restringía a los usuarios realizar copias de seguridad de sus licencias adquiridas legalmente. Entonces, si por alguna razón perdiste tu licencia para el contenido,
pensaron que deberías comprarlo nuevamente.

*Audio Video Interleave , generalmente con una .aviextensión. El formato de contenedor AVI fue inventado por Microsoft en una época más simple, cuando el hecho de que
las computadoras pudieran reproducir video se consideraba bastante sorprendente. No es compatible oficialmente con funciones de formatos de contenedor más recientes, 
como metadatos incrustados. Ni siquiera es compatible oficialmente con la mayoría de los códecs de audio y video modernos que se usan en la actualidad. 


**CÓDECS DE VÍDEO

Cuando "ve un video", su reproductor de video está haciendo al menos tres cosas a la vez:

*Interpretar el formato del contenedor para averiguar qué pistas de video y audio están disponibles y cómo se almacenan dentro del archivo para que pueda encontrar
los datos que necesita para decodificar a continuación.

*Decodificación de la transmisión de video y visualización de una serie de imágenes en la pantalla

*Decodificación de la transmisión de audio y envío del sonido a sus altavoces

Un códec de video es un algoritmo mediante el cual se codifica un flujo de video, es decir, especifica cómo hacer el #2 anterior. (La palabra "códec" es un acrónimo ,
una combinación de las palabras "codificador" y "decodificador"). Su reproductor de video decodifica la transmisión de video de acuerdo con el códec de video ., luego
muestra una serie de imágenes, o "cuadros", en la pantalla. La mayoría de los códecs de video modernos usan todo tipo de trucos para minimizar la cantidad de
información requerida para mostrar un cuadro tras otro.

Hay códecs de video con pérdida y sin pérdida. 
El video sin pérdida es demasiado grande para ser útil en la web, así que me concentraré en los códecs con pérdida.

Un códec de video con pérdidam significa que la información se pierde irremediablemente durante la codificación. Al igual que copiar una cinta de casete de audio, está
perdiendo información sobre el video de origen y degradando la calidad cada vez que codifica. En lugar del "silbido" de un casete de audio, un video
re-re-re-codificado puede parecer bloqueado, especialmente durante las escenas con mucho movimiento. (En realidad, esto puede suceder incluso si codifica directamente
desde la fuente original, si elige un códec de video deficiente o le pasa un conjunto de parámetros incorrecto). durante la reproducción, para que la pérdida sea
menos perceptible para el ojo humano.

Hay toneladas de códecs de video . Los tres códecs más relevantes son H.264 , Theora y VP8 .

                                                                              **H.264

H.264 también se conoce como "MPEG-4 parte 10", también conocido como "MPEG-4 AVC", también conocido como "MPEG-4 Advanced Video Coding". H.264 también fue
desarrollado por el grupo MPEG y estandarizado en 2003. Su objetivo es proporcionar un códec único para dispositivos de bajo ancho de banda y bajo CPU
(teléfonos celulares); dispositivos de alto ancho de banda y alta CPU (computadoras de escritorio modernas); y todo lo demás. Para lograr esto, el estándar
H.264 se divide en " perfiles ", cada uno de los cuales define un conjunto de características opcionales que intercambian complejidad por tamaño de archivo.
Los perfiles más altos usan más funciones opcionales, ofrecen una mejor calidad visual en tamaños de archivo más pequeños, tardan más en codificarse y requieren
más potencia de CPU para decodificar en tiempo real.

YouTube ahora usa H.264 para codificar videos de alta definición , reproducibles a través de Adobe Flash; YouTube también ofrece videos codificados en H.264 para
dispositivos móviles, incluidos el iPhone de Apple y los teléfonos que ejecutan el sistema operativo móvil Android de Google . Además, H.264 es uno de los códecs
de video exigidos por la especificación Blu-Ray; Los discos Blu-Ray que lo usan generalmente usan el perfil Alto.


                                                                             **Theora

Theora evolucionó a partir del códec VP3 y posteriormente fue desarrollado por la Fundación Xiph.org . Theora es un códec libre de regalías y no está gravado por 
ninguna otra patente conocida que no sean las patentes VP3 originales, que se han licenciado sin regalías. Aunque el estándar ha estado "congelado" desde 2004, 
el proyecto Theora (que incluye un codificador y decodificador de referencia de código abierto) solo lanzó la versión 1.0 en noviembre de 2008 y la versión 1.1
en septiembre de 2009 .

El video de Theora se puede incrustar en cualquier formato de contenedor, aunque se ve con mayor frecuencia en un contenedor Ogg. Todas las principales distribuciones
de Linux son compatibles con Theora desde el primer momento, y Mozilla Firefox 3.5 incluye soporte nativo para video de Theora en un contenedor Ogg. Y por "nativo",
me refiero a "disponible en todas las plataformas sin complementos específicos de la plataforma". También puede reproducir videos de Theora en Windows o en Mac OS X 
después de instalar el software decodificador de código abierto de Xiph.org.

                                                                                  **VP8
                                                                                  
VP8 es otro códec de video de On2, la misma compañía que desarrolló originalmente VP3 (más tarde Theora). Técnicamente, produce una salida a la par con H.264 High 
Profile, mientras mantiene una baja complejidad de decodificación a la par con H.264 Baseline.
A partir del 19 de mayo de 2010, VP8 es un códec moderno y libre de regalías y no está gravado por ninguna patente conocida , aparte de las patentes que On2 
(ahora Google) ya tiene licencia libre de regalías.

**CÓDECS DE AUDIO

Al igual que los códecs de video , los códecs de audio son algoritmos mediante los cuales se codifica una transmisión de audio. Al igual que los códecs de video,
hay códecs de audio con pérdida y sin pérdida. Y al igual que el video sin pérdida, el audio sin pérdida es realmente demasiado grande para ponerlo en la web.
Así que me concentraré en los códecs de audio con pérdida.

Como mencioné anteriormente , cuando “ve un video”, su computadora está haciendo al menos tres cosas a la vez:

*Interpretando el formato del contenedor

*Decodificación de la transmisión de video

*Decodificación de la transmisión de audio y envío del sonido a sus altavoces

El códec de audio especifica cómo hacer el n.º 3: decodificar la transmisión de audio y convertirla en formas de onda digitales que luego sus altavoces convierten
en sonido. Al igual que con los códecs de video, existen todo tipo de trucos para minimizar la cantidad de información almacenada en la transmisión de audio. Y dado
que estamos hablando de códecs de audio con pérdida, la información se pierde durante el ciclo de vida de grabación → codificación → decodificación → escucha.

La mayoría de los códecs de audio de propósito general pueden manejar dos canales de sonido. Durante la grabación, el sonido se divide en canales izquierdo y derecho;
durante la codificación, ambos canales se almacenan en el mismo flujo de audio; durante la decodificación, ambos canales se decodifican y cada uno se envía al altavoz
apropiado. Algunos códecs de audio pueden manejar más de dos canales y realizan un seguimiento de qué canal es cuál, por lo que su reproductor puede enviar el sonido
correcto al altavoz correcto.

Hay montones y montones de códecs de audio , pero en la web, en realidad solo hay tres que se deben conocer: MP3 , AAC y Vorbis.

                                                                       **CAPA 3 DE AUDIO MPEG-1

MPEG-1 Audio Layer 3 se conoce coloquialmente como "MP3". 
Los MP3 pueden contener hasta 2 canales de sonido. Se pueden codificar a diferentes tasas de bits : 64 kbps, 128 kbps, 192 kbps y una variedad de otras desde 32 a 320.
Las tasas de bits más altas significan tamaños de archivo más grandes y una mejor calidad de audio, aunque la relación entre calidad de audio y tasa de bits no es
lineal. Además, el formato MP3 permite la codificación de tasa de bits variable, lo que significa que algunas partes del flujo codificado se comprimen más que otras.

El estándar MP3 no define exactamente cómo codificar MP3 (aunque sí define exactamente cómo decodificarlos); diferentes codificadores usan diferentes modelos
psicoacústicos que producen resultados muy diferentes, pero todos pueden ser descifrados por los mismos jugadores. 

El formato MP3 (estandarizado en 1991) está gravado por patentes , lo que explica por qué Linux no puede reproducir archivos MP3 de fábrica. Prácticamente todos los 
reproductores de música portátiles admiten archivos MP3 independientes, y las secuencias de audio MP3 se pueden incrustar en cualquier contenedor de video . 
Adobe Flash puede reproducir archivos MP3 independientes y transmisiones de audio MP3 dentro de un contenedor de video MP4.

                                                                      **CODIFICACIÓN DE AUDIO AVANZADA

La codificación de audio avanzada se conoce cariñosamente como "AAC". Estandarizado en 1997, saltó a la fama cuando Apple lo eligió como su formato predeterminado
para iTunes Store. Originalmente, todos los archivos AAC "comprados" en iTunes Store estaban encriptados con el esquema DRM patentado de Apple, llamado FairPlay .
Las canciones seleccionadas en iTunes Store ahora están disponibles como archivos AAC sin protección, que Apple llama "iTunes Plus" porque suena mucho mejor que llamar
a todo lo demás "iTunes Minus". El formato AAC está gravado por patente ; las tasas de licencia están disponibles en línea .

AAC se diseñó para brindar una mejor calidad de sonido que el MP3 con la misma tasa de bits y puede codificar audio con cualquier tasa de bits. (MP3 está limitado 
a un número fijo de tasas de bits, con un límite superior de 320 kbps). AAC puede codificar hasta 48 canales de sonido , aunque en la práctica nadie hace eso. 
El formato AAC también se diferencia del MP3 en la definición de múltiples perfiles , de forma muy similar a H.264 , y por las mismas razones. 

Adobe Flash es compatible con todos los perfiles de AAC en MP4, al igual que los reproductores de vídeo MPlayer y VLC de código abierto. 

                                                                               **VORBIS

Vorbis a menudo se llama "Ogg Vorbis", aunque esto es técnicamente incorrecto. ("Ogg" es solo un formato de contenedor , y las transmisiones de audio de Vorbis se
pueden incrustar en otros contenedores). Vorbis no está gravado por ninguna patente conocida y, por lo tanto, es compatible de fábrica con todas las principales
distribuciones de Linux y dispositivos portátiles. ejecutando el firmware Rockbox de código abierto . Mozilla Firefox 3.5 admite archivos de audio Vorbis en un
contenedor Ogg o videos Ogg con una pista de audio Vorbis. Los teléfonos móviles con Android también pueden reproducir archivos de audio Vorbis independientes. 
Los flujos de audio de Vorbis generalmente están incrustados en un contenedor Ogg o WebM, pero también pueden estar incrustados en un MP4 o MKVcontenedor 
(o, con algo de piratería, en AVI ). Vorbis admite un número arbitrario de canales de sonido .

**LO QUE FUNCIONA EN LA WEB

Bueno, HTML5 incluye un <video> elemento para incrustar video en una página web. No hay restricciones sobre el códec de video, el códec de audio o el formato contenedor
que puede usar para su video. Un <video> elemento puede vincularse a varios archivos de video y el navegador elegirá el primer archivo de video que realmente puede
reproducir. Depende de usted saber qué navegadores admiten qué contenedores y códecs.

Al escribir estas líneas, este es el panorama del video HTML5 :

*Firefox 3.5+ admite video Theora y audio Vorbis en un contenedor Ogg. Firefox 4+ también es compatible con WebM.
  
Opera 10.5+ admite video Theora y audio Vorbis en un contenedor Ogg. Opera 10.60 (y posterior) también es compatible con WebM.
  
Chrome 3.0+ es compatible con H.264, Theora video y Vorbis audio en un contenedor Ogg. Chrome 6.0+ también es compatible con WebM.
  
*Safari en Mac y PC con Windows 3.0 o superior admitirá todo lo que admita QuickTime. En teoría, podría solicitar a sus usuarios que instalen complementos de QuickTime
de terceros. 
  
*Los teléfonos móviles como el iPhone de Apple y los teléfonos con Android de Google admiten video H.264 (perfil básico) y audio AAC (perfil de "baja complejidad") en
un contenedor MP4.
  
Adobe Flash (9.0.60.184 y posterior) admite video H.264 (todos los perfiles) y audio AAC (todos los perfiles) en un contenedor MP4.
  
*Internet Explorer 9+ admite todos los perfiles de video H.264 y audio AAC o MP3 en un contenedor MP4. También reproducirá video WebM si instala un códec de terceros,
que no está instalado de manera predeterminada en ninguna versión de Windows. IE no es compatible con otros códecs de terceros (a diferencia de Safari, que reproducirá
cualquier cosa que QuickTime pueda reproducir).
  
*Internet Explorer 8 no admite video HTML5 en absoluto, pero prácticamente todos los usuarios de Internet Explorer tendrán el complemento Adobe Flash.
  
  
Para obtener la máxima compatibilidad, así es como debe ver su flujo de trabajo de video:

                     1.-Haz una versión que use WebM (VP8 + Vorbis).
                     2.-Cree otra versión que use video básico H.264 y audio AAC de "baja complejidad" en un contenedor MP4.
                     3.-Haz otra versión que use el video de Theora y el audio de Vorbis en un contenedor Ogg. *
Vincule los tres archivos de video desde un solo <video> elemento y recurra a un reproductor de video basado en Flash.

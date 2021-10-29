# Clase Introductoria a SAR

<h1>Introducción al Radar de Apertura Sintética (SAR)</h1> 
<h2>Por: Cristian Aguilar-Barboza</h2> 


<p>Este material está destinado para los estudiantes del curso de Teledetección de la Escuela de Geografía de la UCR 2021.</p>
<p>Ante cualquier duda o sugerencia: andresaguilarba20@gmail.com</p>

<p>Índice</p> 

<p><li><a href="#Sección1">1. Sensores activos vs sensores pasivos</a></li>
 <li><a href="#Sección2">2. Las microondas y RADAR </a></li>
<li><a href="#Sección3">2. Parametros del sensor</a></li>
<li><a href="#Sección4">3. Parametros de la cobertura</a></li>
<li><a href="#Sección5">4. Errores y distorciones geométricas y radiométricas</a></li>
<li><a href="#Sección6">5. Interpretando una imágen SAR</a></li>


<p><h2 id="Sección1">1. Sensores activos vs sensores pasivos</h2></p>

<p>En los sensores pasivos se aprovecha la energía solar. Miden la energía reflejada por las coberturas en la superficie terrestre en múltiples longitudes de onda o bandas. </p> 
<img src="fi1.png" />
<h4 id="Sección1">Fig 1.Sistema de teledetección pasiva (Weng, 2012).</h4>

<p>Los sensores activos tienen la capacidad de emitir su propia energía en forma de un pulso electromagnético y medir la señal reflejada por el área iluminada.  </p> 
<img src="fig2.png" />
<h4 id="Sección1">Fig 2.Sistema de teledetección activa (Weng, 2012).</h4>

<p> Todo sistema activo se basa en el principio de <strong>ecolocalización</strong>, mismo que utilizan las poblaciones de murciélagos y delfines, o el que podemos encontrar en sonares o en radares meteorológicos. Con esta técnia podemos averiguar la distancia entre un punto emisor y un objetivo a partir del tiempo que dura el pulso en ir y volver. Más adelante, aprenderemos que también es posible obtener otro tipo de información de este mecanismo y que es vital para la formación de imagenes SAR.</p> 
<img src="fig3.jpg" />
<h4 id="Sección1">Fig 3.Principio de ecolocalización.</h4>

<p><h2 id="Sección2">2. Las microondas</h2></p>

<p> La <strong>energía electromagnética</strong>,se transmite de un lugar a otro siguiendo un modelo armónico y continuo a la velocidad de la luz. Esta energia electromagnética está compuesta por dos campos o fuerzas ortogonales:<strong> el campo eléctrico y el campo magnético</strong>. Esta energía se propaga en forma de ondas</p> 

<p> Describimos una onda mediante su longitud de onda (λ) y su frecuencia (F). No obstante, en SAR nos interesan dos parámetros más: la amplitud de la onda (A) y la fase de la onda (φ).</p> 

<p> λ: El periodo espacial sobre el que se repite la función (la distancia entre crestas)</p>
<p>F: Número de ciclos por unidad de tiempo.</p>
<p>A: La potencia o fuerza de la onda.</p>
<p>φ: Describe en qué fase de ciclo se encuentra la onda. La fase inicial define la etapa de la que sale la onda. El uso de la fase no lo evaluaremos acá, pero  es importante que es un parámetro importante.</p>

<img src="fig4.png" />
<h4 id="Sección2">Fig 4. Caracteristicas de una onda (Weng, 2012).</h4>
<p>Las ondas electromagnéticas en el espectro de las microondas suelen tener λ superior a los 3 cm (10 GHz). Mucho mayores que las utilizadas en el espectro visible e infrarrojo. 

Esto implica también que estas ondas tienen una menor frecuencia y menor energía.</p>

<img src="fig5.png" />
<h4 id="Sección2">Fig 5. Espectro electromagnético (Chuvieco, 2007).</h4>

<p>En estas longitudes de onda la atmósfera es "transparente", por lo que la nubosidad u otras distorsiones atmosféricas no son un problema al adquirir imágenes radar independientemente de si es un sensor activo o pasivo.</p>

<p>El espectro del microondas se encuentra en una ventana atmosférica, lo que permite que gran parte de la señal se transmita hasta la superficie terrestre. Estas ventanas atmosféricas son el equivalente de lo que llamamos bandas y es una de las principales razones por la que existe la teledetección orientada a la observación de la tierra.</p> 

<img src="fig6.png" />
<h4 id="Sección2">Fig 6. Espectro electromagnético (Chuvieco, 2007).</h4>

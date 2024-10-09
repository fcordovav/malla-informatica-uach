# Malla-Informática-Uach-interactiva

<p><b>Motivo/Propósito:</b> Viendo las mallas de otras Universidades e Instituciones la gran mayoría, por no decir todas, presentaban una mejor estética y funcionalidad en cuanto al manejo de información y su presentación.<br><br>Se obviaban factores como:</p>
<a href="https://www.uach.cl/dw/admision/plandeestudio.php?car=1708">Visitar Malla Informática Uach<a>
<ul>
  <li><strong>Ramos prerequisitos</strong></li>
  <li><strong>Ramos desbloqueables</strong></li>
  <li><strong>Si son semestrales o no</strong></li>
</ul>

<a href="https://alexbgh1.github.io/malla-informatica-uach/web/">Visitar propuesta Malla Informática Uach</a>
<img src="https://github.com/alexbgh1/malla-informatica-uach/blob/main/img_README/img_muestra.png?raw=true">
<small>La imágen al ser referencial, está propensa a cambios</small>

<h2>Contribuciones</h2>
<b>Gracias a:</b>
<p><a href="https://github.com/fcordovav">Felipe Córdova</a> por actualizar el json con los ramos del 2023 👋</p>

<h2>Proceso</h2>
<h3>Creación de datos</h3>

<p>El primer paso, el más importante y a la vez engorroso, fue la creación de los datos que se almacenan en <b>malla_uach.json</b>, se requería un archivo de lectura capaz de diferenciar los datos de cada semestre, con los respectivos ramos y entre estos, los respectivos pre-requisitos y ramos desbloqueables.</p>
<p>Con la información adecuada el <b>proceso de creación json</b> es claramente automatizable ya que el formato es repetitivo, pero por esta vez tocó hacerlo a mano.</p>

<h3>Testeo</h3>
<p>Una vez con los datos listos, había que revisar y probar la lógica de "consultas" hacia este archivo json, para ello se ejecutó en python jupyter<b>(.ipynb)</b></p>

<h3>Comenzando la página</h3>
<p>Ya arreglando ciertos errores de sintáxis y comprendiendo un poco el como manejar el archivo, se dio paso al uso de <b>Javascript</b> y <b>HTML</b>, estudiando un poco los tipos de eventos, el funcionamiento y uso de funciones en Javascript, ya sea para la lectura del archivo JSON, como el accionar hover <b>(hover:pasar el mouse por un elemento y visualizar un cambio)</b>, lo que da la sensación de interactividad.</p>
<p>A lo anterior se suma algunos elementos de <b>CSS</b> para que se vea un poco mejor.</p>

<h2>Errores y mejoras</h2>
<p>El código creado <b>no está optimizado</b> y probablemente existen <b>malas prácticas</b> en el código. <del><b>No es responsive</b> a teléfonos o pantallas medianas/pequeñas en general.</del></p>
<p>A pesar de estos errores, no los considero tan graves dado el tamaño de la página y el tipo de uso, ya que cumple con el propósito dado al inicio.</p>

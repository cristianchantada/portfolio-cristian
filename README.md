# Práctica HTML y CSS - Bootcamp Web 14 .

## Portfolio de Cristian Varela Casas.

**Leer este readme completo antes de proceder a la corrección.**

### EL proyecto ha sido dividido en:

    * Navbar.
    * Header.
    * Main, el cual a su vez se compone de:
        * Sección Proyectos.
        * Sección Skills.
        * Sección Formulario de contacto.
    * Footer.

### Puntos de ruptura para el diseño responsive:

    Se ha optado por los siguientes:

    * Los puntos de ruptura del **ancho** para el diseño responsive del proyecto son:

        # En el index.html:

            1. **240px**: el proyecto cobra sentido, por debajo de esta cifra no se ha tenido en cuenta.  
            2. **300px**: aparecen las imágenes.
            3. **400px**: el grid de la sección Skills se redimensiona a 2 columnas.
            4. **600px**: Aparece la barra de navegación; cambia la imagen del Header; en la sección Proyectos cambia el tamaño de fuentes y la dimensión de la caja; el grid de la sección Skills se redimensiona a 3 columnas; en el footer cambia el tamaño de las imágenes y de las fuentes.
            5. **875px**: el grid de los datos personales del formulario se redimensiona a 2 columnas. 

        # En el projects.html:

            1. **800px**: El grid pasa a redimensionarse de 1 a 2 columnas.

### Análisis de los pormenores: 

    * Los enlaces e inputs han sido transicionados a cambio del color del borde y de la fuente (de dorado a rojo).

    * En la sección Proyectos, mediante su enlace (role= "button") accedemos a la página de projects.html.

    * La página de projects.html contiene en su parte inferior un enlace de retorno a index.html.

    * Los enlaces del footer se abren en contexto de navegación diferente.

    * Hay contenido multimedia sorpresa en proyects.html .

    * La imagen del header cambia conscientemente, de felino chico, en mobile, a felino grandecito en desktop. Me ha parecido más simpático luego de haber escalado la misma imagen en las pruebas.


### Importante:

    Pese a que, de manera previa a la corrección y con permiso del formador, creo cumplidos los requisitos de la actividad, no puedo considerar el proyecto finalizado debido a que no he llegado a los objetivos auto-exigidos. A fecha de expiración del plazo de entrega no he podido llevarlos a cabo:
    
        * Falta una **refactorización completa del código**, principalmente de todos los .css, pero también de los .html (sobran id's y clases que posteriormente no se han utilizado, alteraría sus nombres ya que la estructura a cambiado a lo largo del proyecto, etc...).

        * No me ha dado tiempo a hacer una revisión completa del código: etiquetas, propiedades, atibutos, etc..

        * Ahora habiendo aprendido ya, con esta práctica, grid y flex bien, alteraría varios de ellos: algunos serían cambiados de flez a grid o viceversa; la estructura interna de cada uno también variaría.

        * Se hubiese buscado una solución adecuada para aquellos dispositivos con display de 240px e inferior.

        * En lo que respecta a las imágenes responsive, en el header se hubiera optado además de por escalar la imagen, combinarla con densidad.

        * Las barras de progreso animadas con CSS comienzan la animación al recargar la página. No me gusta demasiado como ha quedado esto, hubiese preferido al hacer scroll o :hover sobre su sección, ya que de este modo al entrar en la página seguramente no veas la animación porque ya haya finalizado, pero no me ha dado tiempo a más.

        * Hubiese buscado solución para que uno de los audios, incluido en el proyecto pero no referenciado en el index.html, hubiese comenzado a sonar cuando hiciésemos **:hover** sobre las animaciones y estas fuesen aumentando poquito a poquito ("cresce piano piano). 


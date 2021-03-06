---
layout: post
title: Guía de Entregas – Trabajo Práctico Individual
permalink: /guia-entregas-tp-individual
author: admin
date: 20/08/2010
tags: [Trabajos Prácticos] 
hide_post_meta: true
snippets: none

---
## Consideraciones acerca de los ejercicios semanales.

La entrega de los trabajos prácticos consta de dos partes: la <a href="/guia-entregas-tp-individual#EE">entrega electrónica</a> y la <a href="/guia-entregas-tp-individual#EP">entrega en papel</a>. Ambas son necesarias para la corrección del trabajo y no puede realizarse la entrega en papel si no se entregó correctamente en forma electrónica. Es muy importante leer la guía de entrega completa para evitar inconvenientes.

Para el caso del trabajo práctico grupal existe <a href="/guia-entregas-tp-final" target="_self">una guía particular</a>.

<a name="EP"></a>
## Entrega en papel

El informe del ejercicio semanal debe ser entregado impreso en <strong>hoja A4</strong> dentro de un folio (también <strong>A4</strong>). Por favor <strong>NO</strong> entreguen los informes en carpeta ni abrochados o en tamaños de hoja diferentes.

El informe <strong>debe</strong> contener carátula oficial, informe, diagrama y el código fuente devuelto por el sistema de entregas. Opcionalmente podrá contener aclaraciones del alumno.

En caso de tratarse de una reentrega, se <strong>debe</strong> incluir la entrega anterior con las correcciones del docente.

A continuación se detallan cada uno de los puntos mencionados anteriormente.

### Carátula

Debe ser la oficial de la materia. Y no debe cambiarse cuando un trabajo es entregado en segunda oportunidad. Es decir que debe mantenerse en la caratula la primera nota y la lista de correcciones original del trabajo.

<img class="alignnone size-full wp-image-71" title="Archivo PDF" src="/assets/2010/08/file-pdf.gif" alt="Archivo PDF" width="39" height="38"><a href="/assets/2010/08/caratula.pdf">Carátula</a>

### Informe

Una descripción textual de al menos una carilla donde se describa un tema relevante relacionado con la solución del trabajo. Puede tratarse de la forma en la que se solucionó el problema más complejo que presentaba el ejercicio o una lista descriptiva de las funciones o clases más importantes.

### Esquema del diseño

Debe ser una descripción gráfica (se espera un diagrama) de cómo esta constituido y/o resuelto el ejercicio, con una breve descripción coloquial sólo de ser necesario. Se apreciará que el diagrama demuestre una parte especifica de la solución. Por ejemplo no tiene mucho sentido que se imprima un diagrama completo de treinta clases. En cambio aporta información un gráfico que centra la atención en una clase de alta importancia y aquellas relacionadas con la primera.

En aplicaciones que no ameriten un diagrama de clases o secuencia por su escasa complejidad, o por no poder identificar clases u objetos en un programa estructurado, se recomienda explorar otro tipo de diagramas. Una posibilidad es el empleo de diagramas de flujo o gráficos sobre las estructuras de datos utilizadas y la lógica utilizada para su recorrido.

<strong>Nota: El esquema de diseño o diagrama aclaratorio es obligatorio para la aprobación de un trabajo práctico.</strong>

### Aclaraciones del alumno

En el caso excepcional en que no se haya cumplido con la totalidad de los requerimientos de la entrega es indispensable incluir una hoja titulada <em>Aclaraciones del alumno</em> donde se explique la excepción y la justificación pertinente. También es necesario que se informe a un ayudante al momento de entregar el trabajo. Todo esto no garantiza la aceptación de la excepción por parte de la cátedra, pero es condición necesaria.

<a name="CF"></a>
### Código fuente

Se requiere que el código fuente sea prolijo y contenga los comentarios pertinentes. Asimismo es obligatorio incluir sangría (<em>indent</em>) en el código fuente con longitud de entre dos y cuatro espacios. Esto puede hacerse utilizando utilizando espacios o el caracter TAB (tabulación). En el último caso el sistema de entregas ajustará el tamaño del TAB automáticamente.

En caso de tratarse de una reentrega, se <strong>debe</strong> incluir el código fuente de la entrega anterior con las correcciones del docente.

Se debe utilizar el conjunto de caracteres <a href="http://es.wikipedia.org/wiki/UTF8" target="_blank">UTF-8</a> para la codificación de los archivos que conforman el código fuente. Si no dispone de un editor que permita seleccionar la codificación puede recurrir al utilitario <a href="http://en.wikipedia.org/wiki/Iconv" target="_blank">iconv</a> para procesar los archivos antes de crear el paquete ZIP y enviarlo.

El código fuente debe ser impreso en base al PDF que devuelve el sistema de entregas electrónicas de la cátedra. Deben imprimirse dos carillas de código por cada carilla de papel. Es decir que cada hoja contendrá cuatro carillas de código fuente; dos por cada faz. Esto se debe a la intención de reducir el uso de papel.

NOTA: Cuando el enunciado no mencione el tratamiento de errores, el programa deberá retornar al sistema operativo cero en caso de ejecución exitosa y uno ante una situación de error. Si el alumno decidiera retornar varios código de error para diferentes situaciones deberán enumerarlos en el informe.

<a name="EE"></a>
## Entrega Electrónica

La entrega electrónica se realiza a través del sitio <a href="{{ site.sercom_url }}" target="_blank">{{ site.sercom_url }}</a> que cuenta con su propio sistema de registro de usuarios. Una vez correctamente identificado se dispone de un menú en forma de combo en la esquina superior derecha. En el mismo se selecciona la opción <strong>Mis entregas</strong> que nos lleva al listado de entregas realizadas y donde, presionando la opción <strong>Agregar</strong>, se puede realizar la entrega del trabajo. El formulario contiene las instrucciones específicas.

## Corrección

Con el objetivo de lograr un criterio uniforme de corrección y calificación, se estableció el siguiente modo de corrección:

Una vez comprobado que el trabajo práctico cumpla (en forma parcial o total) el objetivo enunciado, se supondrá un trabajo práctico perfecto (10 puntos) y se restarán puntos por cada error encontrado, en base a una tabla general y una particular para cada trabajo práctico.

Entre otros serán evaluados en los siguientes puntos generales:

<ul>
<li>Cumplimiento de los objetivos planteados</li>
<li>Código ordenado y eficiente</li>
<li>Documentación del código fuente</li>
<li>Claridad del informe del trabajo práctico</li>
<li>Presentación correcta de código fuente (impresión legible y ordenada)</li>
<li>Conceptos de programación utilizados</li>
<li>Perdida de memoria y/o recursos
<ul>
<li>No se permite el uso de variables globales</li>
</ul>
</li>
<li>Eficiencia de la solución adoptada
<ul>
<li>No se permite la carga completa de archivos de entrada a memoria (1)</li>
<li>No se permite limitar las entradas a tamaños arbitrarios (1)</li>
</ul>
</li>
</ul>

<em>(1) Salvo indicación explícita del enunciado o del profesor</em>

<a name="compilar"></a>
## ¿Cómo compilar en Linux?


Para compilar en Linux (o cualquier otro <em>sabor</em> de Unix) se utiliza el comando <strong>make</strong> en conjunto con uno de los siguientes archivos de <em>scripts</em>:

<blockquote><em><em><a href="/assets/2010/08/file-zip.gif"><img title="Archivo ZIP" src="/assets/2010/08/file-zip.gif" alt="Archivo ZIP" width="37" height="37"></a></em> <a href="/assets/2016/09/Makefile.zip">Makefile</a><br>
</em>
<em><a href="/assets/2010/08/file-zip.gif"><img title="Archivo ZIP" src="/assets/2010/08/file-zip.gif" alt="Archivo ZIP" width="37" height="37"></a> <a href="/assets/2016/09/Makefile_client_server.zip">Makefile Cliente/Servidor</a><br>
</em></blockquote>

Ambos Makefiles deben descomprimirse en el directorio donde se encuentran todos los fuentes del ejercicio. Luego se edita el <tt>Makefile</tt> con tu editor de texto para configurar la sección llamada&nbsp; <strong><tt>#CONFIGURACION</tt></strong> para indicar el nombre del ejecutable, si se trata de un ejercicio en C o C++, si usa GTK+, gtkmm o la biblioteca matemática (math.h).
En la sección de <strong><tt>#CONFIGURACION "AVANZADA"</tt></strong> se encuentra el detalle de los valores de configuración que puede ser modificado si la configuración simple no es suficiente.
Una vez hecho esto sólo tenés que ejecutar, en la línea de comandos y dentro del directorio de fuentes, el comando&nbsp;<strong><strong>make</strong></strong> (si el archivo de scripts se llama&nbsp;<strong>Makefile</strong> y encuentra en dicho directorio) o <strong>make -f &lt;ruta-archivo-makefile&gt;</strong> (para especificar de forma explícita al archivo de scripts)

<strong>¡Prestar particular atención a los errores y/o advertencias!</strong>

Notas

<ul>
<li>Que compile bien con estas instrucciones no significa que el ejercicio esté perfecto, ni siquiera que sea ISO C/C++ puro. Es sólo una herramienta más (y bastante buena) pero no es garantizala calidad del código.</li>
<li>Si querés aprender más del comando <strong><tt>make</tt></strong> y el <strong><tt>Makefile</tt></strong> ejecutá en la línea de comandos: <strong><tt>man make</tt></strong> o <strong><tt>info make</tt></strong>.</li>
<li>Obviamente necesitás un compilador de C y C++. La cátedra recomienda el GCC/G++ (versiones 4.9 o superior).</li>
</ul>

### Utilizando Makefile Cliente/Servidor

Para compilar programas cliente-servidor, podes usar el Makefile especial para Cliente/Servidor. Para usarlo tenes que renombrarlo como <strong><tt>Makefile </tt></strong>y ponerle nombres especiales a tus archivos:

<ul>
<li><strong><tt>client*</tt></strong> a los archivos especificos para el cliente (por ejemplo: <tt>client_main.cpp</tt>).</li>
<li><strong><tt>server*</tt></strong> a los archivos especificos para el servidor (por ejemplo: <tt>server_main.cpp</tt>).</li>
<li><strong><tt>common*</tt></strong> a los archivos generales, compartidos por ambos procesos, cliente y servidor (por ejemplo: <tt>common_socket.cpp</tt> o <tt>common_thread.cpp</tt>).</li>
<li>Luego, compilas tambien con <tt>make</tt> y te genera los ejecutables <strong><tt>client</tt></strong> con el cliente y <strong><tt>server</tt></strong> con el servidor.</li>
</ul>

## Estándares de Codificación

La cátedra adopta las guías de codificación propuestas por Google para sus herramientas y proyectos públicos. A fin de controlar el cumplimiento de estas normas, los alumnos deben ejecutar el <em>script</em> de verificación <strong>Cpplint</strong> provisto por la cátedra.
Para más información, consultar el instructivo sobre <a title="Normas de Codificación – CPPLint" href="/normas-cpplint">Normas de Codificación y Cpplint</a>.

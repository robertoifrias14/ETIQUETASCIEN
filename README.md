<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lista de Cien Etiquetas HTML</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            background-color: #f5f5f5;
        }
        h1 {
            text-align: center;
            color: #333;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-top: 20px;
            background-color: #fff;
        }
        th, td {
            border: 1px solid #ccc;
            padding: 8px 12px;
            text-align: left;
            vertical-align: top;
        }
        th {
            background-color: #f0f0f0;
        }
        tr:nth-child(even) {
            background-color: #fafafa;
        }
        code {
            background-color: #eee;
            padding: 2px 4px;
            border-radius: 3px;
            font-family: monospace;
        }
    </style>
</head>
<body>
    <h1>Lista de 100 Etiquetas HTML</h1>
    <table>
        <thead>
            <tr>
                <th>Nombre de la Etiqueta</th>
                <th>Descripción</th>
                <th>Ejemplo de Uso</th>
                <th>Elemento Adicional</th>
            </tr>
        </thead>
        <tbody>
            
            <tr><td>&lt;a&gt;</td><td>Define un hipervínculo. Se utiliza para enlazar a otra página o recurso.</td><td><code>&lt;a href="https://www.example.com"&gt;Visita Ejemplo&lt;/a&gt;</code></td><td>Se puede usar <code>target="_blank"</code> para abrir en nueva pestaña.</td></tr>
            <tr><td>&lt;p&gt;</td><td>Define un párrafo de texto.</td><td><code>&lt;p&gt;Este es un párrafo.&lt;/p&gt;</code></td><td>Puede contener otros elementos en línea como &lt;a&gt;, &lt;strong&gt;, &lt;em&gt;.</td></tr>
            <tr><td>&lt;img&gt;</td><td>Incrusta una imagen en la página.</td><td><code>&lt;img src="imagen.jpg" alt="Descripción"&gt;</code></td><td>Alt obligatorio para accesibilidad; se puede usar width y height.</td></tr>
            <tr><td>&lt;div&gt;</td><td>Define una sección o contenedor genérico.</td><td><code>&lt;div&gt;Contenido del div&lt;/div&gt;</code></td><td>Útil para aplicar CSS o agrupar elementos.</td></tr>
            <tr><td>&lt;h1&gt;</td><td>Encabezado de nivel 1, el más importante.</td><td><code>&lt;h1&gt;Encabezado Principal&lt;/h1&gt;</code></td><td>Los niveles van de &lt;h1&gt; a &lt;h6&gt;.</td></tr>
            <tr><td>&lt;h2&gt;</td><td>Encabezado de nivel 2.</td><td><code>&lt;h2&gt;Subencabezado&lt;/h2&gt;</code></td><td>Para estructurar jerarquía de contenido.</td></tr>
            <tr><td>&lt;h3&gt;</td><td>Encabezado de nivel 3.</td><td><code>&lt;h3&gt;Sección&lt;/h3&gt;</code></td><td>Menos importante que &lt;h2&gt;.</td></tr>
            <tr><td>&lt;h4&gt;</td><td>Encabezado de nivel 4.</td><td><code>&lt;h4&gt;Subsección&lt;/h4&gt;</code></td><td>Útil en documentos largos.</td></tr>
            <tr><td>&lt;h5&gt;</td><td>Encabezado de nivel 5.</td><td><code>&lt;h5&gt;Título Menor&lt;/h5&gt;</code></td><td>Generalmente usado en contenido muy específico.</td></tr>
            <tr><td>&lt;h6&gt;</td><td>Encabezado de nivel 6, el menos importante.</td><td><code>&lt;h6&gt;Encabezado pequeño&lt;/h6&gt;</code></td><td>Último nivel de jerarquía de encabezados.</td></tr>
            <tr><td>&lt;ul&gt;</td><td>Lista desordenada.</td><td><code>&lt;ul&gt;&lt;li&gt;Item 1&lt;/li&gt;&lt;li&gt;Item 2&lt;/li&gt;&lt;/ul&gt;</code></td><td>Contiene elementos &lt;li&gt;.</td></tr>
            <tr><td>&lt;ol&gt;</td><td>Lista ordenada.</td><td><code>&lt;ol&gt;&lt;li&gt;Primero&lt;/li&gt;&lt;li&gt;Segundo&lt;/li&gt;&lt;/ol&gt;</code></td><td>Puede usar <code>type</code> para cambiar numeración.</td></tr>
            <tr><td>&lt;li&gt;</td><td>Elemento de lista.</td><td><code>&lt;li&gt;Elemento de lista&lt;/li&gt;</code></td><td>Solo puede estar dentro de &lt;ul&gt;, &lt;ol&gt; o &lt;menu&gt;.</td></tr>
            <tr><td>&lt;strong&gt;</td><td>Texto en negrita con énfasis semántico.</td><td><code>&lt;strong&gt;Importante&lt;/strong&gt;</code></td><td>Diferente de &lt;b&gt;, que es solo visual.</td></tr>
            <tr><td>&lt;em&gt;</td><td>Texto en cursiva con énfasis semántico.</td><td><code>&lt;em&gt;Énfasis&lt;/em&gt;</code></td><td>Diferente de &lt;i&gt;, que es solo visual.</td></tr>
            <tr><td>&lt;span&gt;</td><td>Contenedor en línea para estilos o scripts.</td><td><code>&lt;span style="color:red"&gt;Texto rojo&lt;/span&gt;</code></td><td>No genera salto de línea.</td></tr>
            <tr><td>&lt;br&gt;</td><td>Salto de línea.</td><td><code>Línea 1&lt;br&gt;Línea 2</code></td><td>Etiqueta vacía, no necesita cierre.</td></tr>
            <tr><td>&lt;hr&gt;</td><td>Línea horizontal.</td><td><code>&lt;hr&gt;</code></td><td>Separador visual entre secciones.</td></tr>
            <tr><td>&lt;meta&gt;</td><td>Define metadatos del documento.</td><td><code>&lt;meta charset="UTF-8"&gt;</code></td><td>Se coloca dentro del &lt;head&gt;.</td></tr>
            <tr><td>&lt;title&gt;</td><td>Título de la página en el navegador.</td><td><code>&lt;title&gt;Mi Página&lt;/title&gt;</code></td><td>Solo dentro del &lt;head&gt;.</td></tr>
            <tr><td>&lt;link&gt;</td><td>Enlaza recursos externos, como CSS.</td><td><code>&lt;link rel="stylesheet" href="estilos.css"&gt;</code></td><td>Solo dentro del &lt;head&gt;.</td></tr>
            <tr><td>&lt;style&gt;</td><td>Contiene CSS interno.</td><td><code>&lt;style&gt;p {color:red;}&lt;/style&gt;</code></td><td>Puedes colocarlo en &lt;head&gt; o &lt;body&gt;.</td></tr>
            <tr><td>&lt;script&gt;</td><td>Contiene o enlaza JavaScript.</td><td><code>&lt;script src="script.js"&gt;&lt;/script&gt;</code></td><td>Se puede colocar en &lt;head&gt; o al final de &lt;body&gt;.</td></tr>
            <tr><td>&lt;header&gt;</td><td>Encabezado de la página o sección.</td><td><code>&lt;header&gt;&lt;h1&gt;Bienvenido&lt;/h1&gt;&lt;/header&gt;</code></td><td>Puede contener navegación y logotipo.</td></tr>
            <tr><td>&lt;footer&gt;</td><td>Pie de página de la página o sección.</td><td><code>&lt;footer&gt;Derechos reservados 2025&lt;/footer&gt;</code></td><td>Contiene información legal o contacto.</td></tr>
            <tr><td>&lt;main&gt;</td><td>Contenedor principal del contenido de la página.</td><td><code>&lt;main&gt;&lt;p&gt;Contenido principal&lt;/p&gt;&lt;/main&gt;</code></td><td>Solo debe haber un &lt;main&gt; por página.</td></tr>
            <tr><td>&lt;section&gt;</td><td>Define una sección genérica del documento.</td><td><code>&lt;section&gt;&lt;h2&gt;Noticias&lt;/h2&gt;&lt;/section&gt;</code></td><td>Útil para dividir contenido temático.</td></tr>
            <tr><td>&lt;article&gt;</td><td>Contenido independiente y autocontenido.</td><td><code>&lt;article&gt;&lt;h3&gt;Artículo 1&lt;/h3&gt;&lt;/article&gt;</code></td><td>Ideal para blogs o noticias.</td></tr>
            <tr><td>&lt;aside&gt;</td><td>Contenido lateral o complementario.</td><td><code>&lt;aside&gt;Publicidad&lt;/aside&gt;</code></td><td>No forma parte del flujo principal.</td></tr>
            <tr><td>&lt;nav&gt;</td><td>Área de navegación de la página.</td><td><code>&lt;nav&gt;&lt;a href="#"&gt;Inicio&lt;/a&gt;&lt;/nav&gt;</code></td><td>Contiene enlaces de menú principal.</td></tr>
            <tr><td>&lt;figure&gt;</td><td>Contenedor para imágenes y su pie de foto.</td><td><code>&lt;figure&gt;&lt;img src="foto.jpg"&gt;&lt;figcaption&gt;Foto&lt;/figcaption&gt;&lt;/figure&gt;</code></td><td>&lt;figcaption&gt; es opcional.</td></tr>
            <tr><td>&lt;figcaption&gt;</td><td>Pie de figura para &lt;figure&gt;.</td><td><code>&lt;figcaption&gt;Descripción de la imagen&lt;/figcaption&gt;</code></td><td>Acompaña imágenes o diagramas.</td></tr>
            <tr><td>&lt;address&gt;</td><td>Información de contacto.</td><td><code>&lt;address&gt;Correo@ejemplo.com&lt;/address&gt;</code></td><td>Normalmente en el &lt;footer&gt;.</td></tr>
            <tr><td>&lt;blockquote&gt;</td><td>Cita larga.</td><td><code>&lt;blockquote&gt;“Texto citado largo”&lt;/blockquote&gt;</code></td><td>Se puede usar <code>cite</code> para fuente.</td></tr>
            <tr><td>&lt;q&gt;</td><td>Cita corta en línea.</td><td><code>&lt;q&gt;Texto citado&lt;/q&gt;</code></td><td>Se renderiza entre comillas.</td></tr>
            <tr><td>&lt;code&gt;</td><td>Fragmento de código en línea.</td><td><code>&lt;code&gt;console.log('Hola')&lt;/code&gt;</code></td><td>Útil en tutoriales o documentación.</td></tr>
            <tr><td>&lt;pre&gt;</td><td>Texto preformateado.</td><td><code>&lt;pre&gt;   Espacios y saltos   &lt;/pre&gt;</code></td><td>Mantiene espacios y saltos de línea.</td></tr>
            <tr><td>&lt;mark&gt;</td><td>Resalta texto.</td><td><code>&lt;mark&gt;Resaltado&lt;/mark&gt;</code></td><td>Color amarillo por defecto.</td></tr>
            <tr><td>&lt;del&gt;</td><td>Texto eliminado o tachado.</td><td><code>&lt;del&gt;Texto viejo&lt;/del&gt;</code></td><td>Para mostrar cambios.</td></tr>
            <tr><td>&lt;ins&gt;</td><td>Texto insertado.</td><td><code>&lt;ins&gt;Texto nuevo&lt;/ins&gt;</code></td><td>Útil para ediciones o correcciones.</td></tr>
            <tr><td>&lt;sub&gt;</td><td>Subíndice.</td><td><code>H&lt;sub&gt;2&lt;/sub&gt;O</code></td><td>Ideal para fórmulas químicas.</td></tr>
            <tr><td>&lt;sup&gt;</td><td>Superíndice.</td><td><code>10&lt;sup&gt;2&lt;/sup&gt;</code></td><td>Ideal para exponentes.</td></tr>
            <tr><td>&lt;b&gt;</td><td>Texto en negrita visual.</td><td><code>&lt;b&gt;Negrita&lt;/b&gt;</code></td><td>No aporta significado semántico.</td></tr>
            <tr><td>&lt;i&gt;</td><td>Texto en cursiva visual.</td><td><code>&lt;i&gt;Cursiva&lt;/i&gt;</code></td><td>No aporta significado semántico.</td></tr>
            <tr><td>&lt;u&gt;</td><td>Texto subrayado.</td><td><code>&lt;u&gt;Subrayado&lt;/u&gt;</code></td><td>Evitar confusión con enlaces.</td></tr>
            <tr><td>&lt;small&gt;</td><td>Texto más pequeño.</td><td><code>&lt;small&gt;Pequeño&lt;/small&gt;</code></td><td>Para notas o aclaraciones.</td></tr>
            <tr><td>&lt;abbr&gt;</td><td>Abreviatura o acrónimo.</td><td><code>&lt;abbr title="Cascading Style Sheets"&gt;CSS&lt;/abbr&gt;</code></td><td>Al pasar el mouse muestra el título.</td></tr>
            <tr><td>&lt;bdi&gt;</td><td>Aísla la dirección del texto.</td><td><code>&lt;bdi&gt;Texto&lt;/bdi&gt;</code></td><td>Útil para idiomas bidireccionales.</td></tr>
            <tr><td>&lt;bdo&gt;</td><td>Controla dirección del texto.</td><td><code>&lt;bdo dir="rtl"&gt;Texto&lt;/bdo&gt;</code></td><td>dir puede ser ltr o rtl.</td></tr>
            <tr><td>&lt;cite&gt;</td><td>Referencia a obra.</td><td><code>&lt;cite&gt;El Quijote&lt;/cite&gt;</code></td><td>Semántico para títulos.</td></tr>
            <tr><td>&lt;data&gt;</td><td>Asocia contenido con valor legible.</td><td><code>&lt;data value="123"&gt;Artículo 123&lt;/data&gt;</code></td><td>Valor accesible para scripts.</td></tr>
            <tr><td>&lt;time&gt;</td><td>Fecha u hora legible por máquina.</td><td><code>&lt;time datetime="2025-09-05"&gt;5 Septiembre 2025&lt;/time&gt;</code></td><td>Útil para SEO y microformatos.</td></tr>
            <tr><td>&lt;progress&gt;</td><td>Barra de progreso.</td><td><code>&lt;progress value="70" max="100"&gt;&lt;/progress&gt;</code></td><td>Visualiza progreso de tareas.</td></tr>
            <tr><td>&lt;meter&gt;</td><td>Medidor de un valor escalar.</td><td><code>&lt;meter value="0.7" min="0" max="1"&gt;&lt;/meter&gt;</code></td><td>Útil para mediciones y estadísticas.</td></tr>
            <tr><td>&lt;form&gt;</td><td>Formulario para enviar datos.</td><td><code>&lt;form action="/submit"&gt;&lt;input type="text"&gt;&lt;/form&gt;</code></td><td>Puede usar method="post" o get.</td></tr>
            <tr><td>&lt;input&gt;</td><td>Campo de entrada de datos.</td><td><code>&lt;input type="text" name="nombre"&gt;</code></td><td>Diferentes tipos: text, password, email, checkbox.</td></tr>
            <tr><td>&lt;textarea&gt;</td><td>Área de texto multilinea.</td><td><code>&lt;textarea&gt;Escribe aquí&lt;/textarea&gt;</code></td><td>Se puede definir rows y cols.</td></tr>
            <tr><td>&lt;button&gt;</td><td>Botón interactivo.</td><td><code>&lt;button&gt;Enviar&lt;/button&gt;</code></td><td>Puede ser type="submit", reset, button.</td></tr>
            <tr><td>&lt;select&gt;</td><td>Lista desplegable.</td><td><code>&lt;select&gt;&lt;option&gt;Opción 1&lt;/option&gt;&lt;/select&gt;</code></td><td>Contiene &lt;option&gt; como hijos.</td></tr>
            <tr><td>&lt;option&gt;</td><td>Opción dentro de &lt;select&gt;.</td><td><code>&lt;option value="1"&gt;Opción 1&lt;/option&gt;</code></td><td>Puede usar selected por defecto.</td></tr>
            <tr><td>&lt;label&gt;</td><td>Etiqueta de un control de formulario.</td><td><code>&lt;label for="nombre"&gt;Nombre&lt;/label&gt;</code></td><td>for debe coincidir con id del input.</td></tr>
            <tr><td>&lt;fieldset&gt;</td><td>Agrupa controles de formulario.</td><td><code>&lt;fieldset&gt;&lt;legend&gt;Datos&lt;/legend&gt;&lt;/fieldset&gt;</code></td><td>&lt;legend&gt; describe el grupo.</td></tr>
            <tr><td>&lt;legend&gt;</td><td>Título de un &lt;fieldset&gt;.</td><td><code>&lt;legend&gt;Información personal&lt;/legend&gt;</code></td><td>Solo dentro de &lt;fieldset&gt;.</td></tr>
            <tr><td>&lt;datalist&gt;</td><td>Lista de sugerencias para &lt;input&gt;.</td><td><code>&lt;input list="opciones"&gt;&lt;datalist id="opciones"&gt;&lt;option value="1"&gt;&lt;/datalist&gt;</code></td><td>Mejora UX con autocompletado.</td></tr>
            <tr><td>&lt;output&gt;</td><td>Muestra resultados de un formulario.</td><td><code>&lt;output name="resultado"&gt;0&lt;/output&gt;</code></td><td>Se puede actualizar con JS.</td></tr>
            <tr><td>&lt;iframe&gt;</td><td>Incrusta otra página.</td><td><code>&lt;iframe src="https://example.com"&gt;&lt;/iframe&gt;</code></td><td>Se puede usar width y height, y sandbox para seguridad.</td></tr>
            <tr><td>&lt;embed&gt;</td><td>Incrusta contenido externo como multimedia.</td><td><code>&lt;embed src="video.mp4" type="video/mp4"&gt;</code></td><td>Alternativa a &lt;object&gt; y &lt;iframe&gt;.</td></tr>
            <tr><td>&lt;object&gt;</td><td>Contenedor para recursos externos.</td><td><code>&lt;object data="archivo.pdf" type="application/pdf"&gt;&lt;/object&gt;</code></td><td>Puede usar &lt;param&gt; para parámetros.</td></tr>
            <tr><td>&lt;param&gt;</td><td>Define parámetros para &lt;object&gt;.</td><td><code>&lt;param name="autoplay" value="true"&gt;</code></td><td>Solo dentro de &lt;object&gt;.</td></tr>
            <tr><td>&lt;video&gt;</td><td>Reproduce videos.</td><td><code>&lt;video src="video.mp4" controls&gt;&lt;/video&gt;</code></td><td>Se puede usar autoplay, loop, muted.</td></tr>
            <tr><td>&lt;audio&gt;</td><td>Reproduce audio.</td><td><code>&lt;audio src="audio.mp3" controls&gt;&lt;/audio&gt;</code></td><td>Soporta múltiples formatos y atributos.</td></tr>
            <tr><td>&lt;source&gt;</td><td>Fuente de multimedia para &lt;video&gt; o &lt;audio&gt;.</td><td><code>&lt;source src="video.mp4" type="video/mp4"&gt;</code></td><td>Permite definir varios formatos.</td></tr>
            <tr><td>&lt;track&gt;</td><td>Subtítulos o pistas para &lt;video&gt; o &lt;audio&gt;.</td><td><code>&lt;track kind="subtitles" src="sub.vtt" srclang="es"&gt;</code></td><td>default indica pista predeterminada.</td></tr>
            <tr><td>&lt;canvas&gt;</td><td>Área para gráficos dinámicos con JS.</td><td><code>&lt;canvas id="miCanvas" width="300" height="150"&gt;&lt;/canvas&gt;</code></td><td>Se manipula con JavaScript.</td></tr>
            <tr><td>&lt;svg&gt;</td><td>Contenedor de gráficos vectoriales.</td><td><code>&lt;svg width="100" height="100"&gt;&lt;circle cx="50" cy="50" r="40" fill="red"/&gt;&lt;/svg&gt;</code></td><td>Escalable y manipulable con CSS y JS.</td></tr>
            <tr><td>&lt;picture&gt;</td><td>Contenedor de imágenes adaptativas.</td><td><code>&lt;picture&gt;&lt;source srcset="img.webp" type="image/webp"&gt;&lt;img src="img.jpg" alt=""&gt;&lt;/picture&gt;</code></td><td>Permite imágenes responsivas y formatos alternativos.</td></tr>
            <tr><td>&lt;template&gt;</td><td>Contenido HTML que no se renderiza automáticamente.</td><td><code>&lt;template&gt;&lt;p&gt;Plantilla&lt;/p&gt;&lt;/template&gt;</code></td><td>Se muestra solo con JS.</td></tr>
            <tr><td>&lt;slot&gt;</td><td>Inserta contenido en Web Components.</td><td><code>&lt;slot name="contenido"&gt;&lt;/slot&gt;</code></td><td>Solo dentro de Custom Elements.</td></tr>
            <tr><td>&lt;details&gt;</td><td>Elemento que crea un panel desplegable.</td><td><code>&lt;details&gt;&lt;summary&gt;Más info&lt;/summary&gt;Contenido oculto&lt;/details&gt;</code></td><td>&lt;summary&gt; indica el título del panel.</td></tr>
<tr><td>&lt;summary&gt;</td><td>Título visible de &lt;details&gt;.</td><td><code>&lt;summary&gt;Ver detalles&lt;/summary&gt;</code></td><td>Siempre dentro de &lt;details&gt;.</td></tr>
<tr><td>&lt;menu&gt;</td><td>Lista de comandos o menú.</td><td><code>&lt;menu&gt;&lt;li&gt;Opción 1&lt;/li&gt;&lt;/menu&gt;</code></td><td>Puede ser de tipo toolbar o context.</td></tr>
<tr><td>&lt;menuitem&gt;</td><td>Elemento de menú individual.</td><td><code>&lt;menuitem label="Guardar" icon="guardar.png"&gt;</code></td><td>Deprecado en HTML5, usar alternativas.</td></tr>
<tr><td>&lt;map&gt;</td><td>Define un mapa de imagen.</td><td><code>&lt;img src="mapa.jpg" usemap="#mapa"&gt;&lt;map name="mapa"&gt;&lt;/map&gt;</code></td><td>Usa &lt;area&gt; para zonas clicables.</td></tr>
<tr><td>&lt;area&gt;</td><td>Define área clicable dentro de &lt;map&gt;.</td><td><code>&lt;area shape="rect" coords="0,0,50,50" href="pagina.html"&gt;</code></td><td>Se usa con &lt;map&gt; y &lt;img usemap&gt;.</td></tr>
<tr><td>&lt;iframe&gt;</td><td>Incrusta otra página dentro de la actual.</td><td><code>&lt;iframe src="pagina.html" width="300" height="200"&gt;&lt;/iframe&gt;</code></td><td>Se puede usar sandbox para seguridad.</td></tr>
<tr><td>&lt;colgroup&gt;</td><td>Define un grupo de columnas en tabla.</td><td><code>&lt;colgroup&gt;&lt;col span="2"&gt;&lt;/colgroup&gt;</code></td><td>Permite aplicar estilos a varias columnas.</td></tr>
<tr><td>&lt;col&gt;</td><td>Define una columna dentro de &lt;colgroup&gt;.</td><td><code>&lt;col span="1"&gt;</code></td><td>Se puede usar style para ancho o color.</td></tr>
<tr><td>&lt;caption&gt;</td><td>Título de una tabla.</td><td><code>&lt;caption&gt;Tabla de Usuarios&lt;/caption&gt;</code></td><td>Debe ser el primer hijo de &lt;table&gt;.</td></tr>
<tr><td>&lt;thead&gt;</td><td>Encabezado de tabla.</td><td><code>&lt;thead&gt;&lt;tr&gt;&lt;th&gt;Nombre&lt;/th&gt;&lt;/tr&gt;&lt;/thead&gt;</code></td><td>Separa semánticamente las cabeceras.</td></tr>
<tr><td>&lt;tbody&gt;</td><td>Cuerpo de la tabla.</td><td><code>&lt;tbody&gt;&lt;tr&gt;&lt;td&gt;Dato&lt;/td&gt;&lt;/tr&gt;&lt;/tbody&gt;</code></td><td>Contiene filas de datos.</td></tr>
<tr><td>&lt;tfoot&gt;</td><td>Pie de la tabla.</td><td><code>&lt;tfoot&gt;&lt;tr&gt;&lt;td&gt;Total&lt;/td&gt;&lt;/tr&gt;&lt;/tfoot&gt;</code></td><td>Opcional, se coloca al final.</td></tr>
<tr><td>&lt;tr&gt;</td><td>Fila de tabla.</td><td><code>&lt;tr&gt;&lt;td&gt;Dato&lt;/td&gt;&lt;/tr&gt;</code></td><td>Debe estar dentro de &lt;thead&gt;, &lt;tbody&gt; o &lt;tfoot&gt;.</td></tr>
<tr><td>&lt;td&gt;</td><td>Celda de datos.</td><td><code>&lt;td&gt;Dato&lt;/td&gt;</code></td><td>Dentro de &lt;tr&gt;.</td></tr>
<tr><td>&lt;th&gt;</td><td>Celda de encabezado.</td><td><code>&lt;th&gt;Título&lt;/th&gt;</code></td><td>Texto centrado y en negrita por defecto.</td></tr>
<tr><td>&lt;colgroup&gt;</td><td>Grupo de columnas en tabla.</td><td><code>&lt;colgroup&gt;&lt;col&gt;&lt;/colgroup&gt;</code></td><td>Define ancho o estilo conjunto de columnas.</td></tr>
<tr><td>&lt;track&gt;</td><td>Subtítulos para multimedia.</td><td><code>&lt;track kind="subtitles" src="sub.vtt" srclang="es"&gt;</code></td><td>Permite mostrar subtítulos o descripciones.</td></tr>
<tr><td>&lt;template&gt;</td><td>Plantilla HTML no renderizada.</td><td><code>&lt;template&gt;&lt;p&gt;Contenido&lt;/p&gt;&lt;/template&gt;</code></td><td>Se activa con JS.</td></tr>
<tr><td>&lt;slot&gt;</td><td>Marcador de contenido en Web Components.</td><td><code>&lt;slot name="contenido"&gt;&lt;/slot&gt;</code></td><td>Reemplazable desde componente padre.</td></tr>
<tr><td>&lt;dialog&gt;</td><td>Ventana modal o cuadro de diálogo.</td><td><code>&lt;dialog open&gt;Mensaje&lt;/dialog&gt;</code></td><td>Se puede abrir o cerrar con JS.</td></tr>
<tr><td>&lt;picture&gt;</td><td>Imágenes adaptables según tamaño o formato.</td><td><code>&lt;picture&gt;&lt;source srcset="img.webp" type="image/webp"&gt;&lt;img src="img.jpg"&gt;&lt;/picture&gt;</code></td><td>Soporta responsive y webp.</td></tr>
<tr><td>&lt;mark&gt;</td><td>Resalta texto.</td><td><code>&lt;mark&gt;Resaltado&lt;/mark&gt;</code></td><td>Color amarillo por defecto.</td></tr>
<tr><td>&lt;wbr&gt;</td><td>Indica posible salto de línea.</td><td><code>EstaEsUnaPalabra<wbr>MuyLarga</code></td><td>No genera espacio visual.</td></tr>
<tr><td>&lt;noscript&gt;</td><td>Contenido alternativo si JS está deshabilitado.</td><td><code>&lt;noscript&gt;Activa JS para ver el contenido&lt;/noscript&gt;</code></td><td>Solo se renderiza sin JS.</td></tr>
<tr><td>&lt;base&gt;</td><td>URL base para enlaces relativos.</td><td><code>&lt;base href="https://ejemplo.com"&gt;</code></td><td>Se coloca en &lt;head&gt;.</td></tr>
<tr><td>&lt;meta&gt;</td><td>Metadatos de la página.</td><td><code>&lt;meta name="description" content="Página ejemplo"&gt;</code></td><td>SEO y compatibilidad.</td></tr>

        </tbody>
    </table>
</body>
</html>

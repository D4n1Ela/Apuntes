### *PRÁCTICA 1: Listas desordenadas y anidadas* ###
*Realizamos una lista desordenada **ul** transcribiendo el menú del Sublime Text: Cada item del menú principal tiene que mostrar tres items de su correspondiente menú contextual.*

    <!DOCTYPE html>
    <html>
    <head>
        <title>Menú de Sublime Text</title>
    </head>
    <body>
        <div>
            <h1>Menú de Sublime Text</h1>
            <ul>
                <li>File</li>
                    <ul>
                        <li>New File</li>
                        <li>Open File...</li>
                        <li>Open Folder...</li>
                    </ul>

                <li>Edit</li>
                    <ul>
                        <li>Undo</li>
                        <li>Redo</li>
                        <li>Undo Selection</li>
                    </ul>

                <li>Selection</li>
                    <ul>
                        <li>Split into Lines</li>
                        <li>Add Previous Line</li>
                        <li>Add Next Line</li>
                    </ul>

                <li>etc ...</li>

            </ul>
        </div>
    </body>
    </html>

---



&nbsp;
### *PRÁCTICA 2: Combinamos listas ordenadas y listas ordenadas* ###
*Codeamos lo siguiente con la finalidad de mostrar en el navegador el menú ejemplificado en el pizarrón.*


    <!DOCTYPE html>
    <html>
    <head>
        <title>Menú de Sublime Text</title>
    </head>
    <body>
    <div>
            <hr/>
            <h2> Lenguajes de Programación</h2>
            <ol>
                <li>HTML</li>
                    <ul>
                        <li>Etiquetas Centrales</li>
                            <ol>
                                <li>HEAD</li>
                                <li>BODY</li>
                            </ol>
                        <li>Atributos</li>
                    </ul>

                <li>CSS</li>
                    <ul>
                        <li>Responsive Design</li>
                        <li>Class /ID</li>
                        <li>FlexBox</li>
                            <ol>
                                <li>Propiedades del Padre</li>
                                <li>Propiedades de los hijos</li>
                            </ol>
                    </ul>

                <li>JavaScript</li>
                    <ul>
                        <li>JQUERY</li>
                        <li>NODEJS</li>
                    </ul>

            </ol>
        </div>
    </body>
    </html>
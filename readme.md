            - Objeto documento(DOM) (document)
            Permite al javascript modificar y manipular dinámicamente el contenido de un documento HTML

            - Obtener Elementos o Elementos
                --getElementById
                    const message = document.getElementById('message');

                --querySelector
                    const message2 = document.querySelector('.parrafo');
                    const message3 = document.querySelector('#message');

                --querySelectorAll
                    const linksMessage = document.querySelectorAll('.NavBar ul li a'); 

            - Nodos( que cosa son los nodos )
                    son los elementos fundamentales que conforman la estructura de un documento HTML

            - TextContent (contenido elemento)
                    divElement.textContent = "Hola soy un div creado por JavaScript";

            - Estilos
                    message.style.color = 'red';
                    message.style.backgroundColor = 'blue';
                    message.style.margin = '0';
                    message.style.textTransform = 'uppercase';

            - DomTraversing
                    const parentlink = linkElement.parentElement.parentElement.parentElement;

            - createElement
                    const divElement = document.createElement('div');

            - innerHTML
                    divElement.innerHTML = '<h1 class="hola">Hola soy un div creado por javascript</h1>';

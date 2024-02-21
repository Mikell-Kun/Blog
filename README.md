# Gabriel Miguel Cabrera Samano
<b>Proyecto base de un Blog personal</b>
<b>Fecha de creacion:</b> <p>21 de febrero del 2024<p>
<b>Descripcion:</b> <p>es una interfaz fácil de interactuar para conocer a los autores que deseen crear y publicar contenido en línea. La estructura básica del blog incluye páginas hacia otros articulos que muestra las últimas publicaciones, y posiblemente una página "Acerca de nosotros" que brinda información sobre los autores o el propósito del blog.</p>

Novedades en la implementacion de diseño en HTML:
- nav: 
- section: 
- main: 
- footer: 
- article:
- aside:

detalles generales:
<body>
    <!-- contenido del documento -->
    <div class="container">
        <!-- encabezado principal de la pagina -->
        <header>
            <div class="profile_picture">
                <img src="f1.jpg" alt="" width="100" height="100">
            </div>
            <h1>Miguel Cabrera</h1>
        </header>
        <!-- navegacion semi-personalizada sin funciones -->
        <nav>
            <ul>
                <li>Principal</li>
                <li>Detalles</li>
                <li>ayuda</li>
            </ul>
        </nav>
        <!-- punto de partida para el programa -->
        <main>
            <section>
                <!-- articulo descriptivo sobre una cuenta en spootify -->
                <article>
                    <h2><a href="https://open.spotify.com/user/mikell100?si=4c92413dbcc24cf3">Cuenta de Spootify</a> </h2>
                    <p>"¡Bienvenido a tu pasaporte musical personalizado en Spotify! Con nuestra cuenta premium, tienes acceso ilimitado a millones de canciones de todos los géneros imaginables."</p>
                </article>
                <!-- articulo descriptivo sobre un correo electronico -->
                <article>
                    <h2><a href="mailto:a20491199@itmexicali.edu.mx">Correo Electronico</a></h2>
                    <p>"¡Bienvenido a tu bandeja de entrada digital en nuestro servicio de correo electrónico! Con nuestra plataforma, gestionar tu correo electrónico nunca ha sido tan fácil y eficiente. Ya sea que estés trabajando en proyectos importantes, organizando eventos sociales o simplemente manteniéndote en contacto con amigos y familiares, nuestra herramienta te ofrece todas las funciones necesarias para mantener tu comunicación en línea fluida y segura."</p>
                </article>
                <!-- articulo descriptivo sobre una cuenta en facebook -->
                <article>
                    <h2><a href="https://www.facebook.com/miguel.cabrera.5249">Perfil de facebook</a></h2>
                    <p>"¡Bienvenido a tu espacio social en línea en Facebook! Con tu cuenta, puedes conectarte con amigos, familiares y personas de todo el mundo de una manera fácil y divertida. Comparte momentos especiales de tu vida a través de publicaciones, fotos y videos, y mantente al tanto de lo que están haciendo tus seres queridos mediante sus actualizaciones."</p>
                </article>
            </section>
            <!-- Seccion del documento que maneja un buscador-->
            <aside>
                <h3>Busqueda:</h3>
                <form>
                    <input type="text" />
                    <input type="submit" value="buscar" />
                </form>
            </aside>
        </main>
        <!-- pie de pagina -->
        <footer>
            Gabriel Miguel Cabrera Samano &copy; 2024
        </footer>
    </div>
</body>

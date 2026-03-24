<section>
    <h1 align="center">Tunel Local: El Bodegón del Backend</h1>
    <p align="center"><i>"Un repositorio es solo código para probar, es como una buena carne que si no la sabes cocinar, se arrebata."</i></p><hr>

<h2>Resumen de la Parrillada</h2>
<p>Este proyecto es como un <b>asado de domingo en Google Colab</b>. Agarramos un repositorio crudo que viene de GitHub, lo tiramos a la parrilla de los servidores de Google y lo sacamos jugoso para que lo veas desde cualquier lado. No importa si el bicho es <b>Python</b> o si es <b>Java</b>; acá le damos fuego parejo a los dos para que se doren y queden a punto.</p>

<blockquote>"El backend es como el choripán: un montón de lógica condimentada, picada y metida dentro de un servidor... todo eso cocido a fuego lento y servido en un pan de URL pública para que te lo comas de un bocado. Si te da la gana, le ponés el chimichurri de tus propias rutas."
</blockquote><hr>

<h2>🛠️ Modo de Uso (El Paso a Paso)</h2>

<details>
    <summary><b>1. El Gancho (Clonar el Repo)</b></summary>
    <p>Primero hay que traer la mercadería. Bajamos los cortes desde el repo de Aldo para tener qué cocinar.</p>
    <pre>!git clone https://github.com/manfredialdo/UTN-TUPaD-P3.git</pre>
</details>

<details>
    <summary><b>2. Opción Python (El Chorizo al Plato)</b></summary>
    <p>Si lo tuyo es el <b>Flask</b>, esta celda levanta el servidor, busca el <code>index.html</code> entre las carpetas y te lo sirve caliente con un túnel de Localtunnel. Es rápido, eficaz y no falla.</p>
    <pre>
# Instalamos la batería de cocina
        !pip install flask --quiet
        !npm install -g localtunnel --quiet
        </pre>
    </details>

    <details>
        <summary><b>3. Opción Java (La Costilla con Hueso)</b></summary>
        <p>Para los que les gusta renegar más pero con más sabor. Acá compilamos el <code>.java</code> con <code>javac</code>, lo hacemos hervir en el puerto 8080 y te damos la llave de paso (IP Password) para que entres al túnel sin pedir permiso.</p>
        <pre>
# Compilamos y mandamos a la parri
!javac *.java
!java Main
        </pre>
    </details>

    <hr>

    <div align="center">
        <h3>🧂 Condimentos Finales</h3>
        <p>
            Copiás la IP que te escupe el <code>curl</code>, abrís el link que te da el <code>npx localtunnel</code> y ¡listo! Ya tenés el backend funcionando, servido en tabla de madera y con el ping bien bajo.
        </p>
        <p><b>© 2026 · Aldo Manfredi · Maestro Parrillero de Código</b></p>
    </div>
</section>

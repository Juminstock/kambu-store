<h1 align="center">Rust-start</h1>
<p>
  Aprenderemos inicialmente a instalar <a href="https://www.rust-lang.org/es">Rust</a>, el clasico Hello, world!, y algunas consideraciones sobre <a href="https://www.rust-lang.org/es">rustc</a> y <a href="https://www.rust-lang.org/es">cargo</a>.
</p>
<h2 align="center">Instalación</h2>
<p>
  Es sencilla, en mi caso, como usuario de Linux basta con ejecutar este comando en la terminal: <br>
  <code> curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh </code> Este comando descargará un script e iniciará la instalación de rustup, una herramienta que instalará la última versión estable de Rust. Para el caso de Windows te recomiendo revisar la <a href="https://rust-book.cs.brown.edu/ch01-01-installation.html">documentación oficial.</a>
  
  Un posible error puede ser la ausencia de un linker, para solucionarlo instalamos el paquete <code>build-essential</code> en     Linux.
</p>
<h3> Algunas opciones útiles de rustup son: </h3>
<ul>
  <li><code>rustup update</code> para actualizar nuestra versión de Rust.</li>
  <li><code>rustup self uninstall</code> para desinstalar Rust.</li>
  <li><code>rustup doc</code> para abrir una copia offline de la documentación.</li>
</ul>
<h3>Hello, world!</h3>
<p>Creemos nuestro primer "Hola, mundo" en Rust. Así es cómo se vería:</p>
  <img src="https://github.com/Juminstock/rust-start/blob/main/assets/hello_world.png">
<p>
  Para crearlo ejecutemos este comando en la terminal: <code>cargo new <em>nombre_de_tu_proyecto</em></code> Este comando te creará toda una estructura de carpetas con archivos incorporados, la estructura se verá así: <br><br>
  <img src="https://github.com/Juminstock/rust-start/blob/main/assets/estructura_carpetas.png"> <br><br>
  Dentro de la carpeta <em>src</em> encontraremos un archivo nombrado como <code>main.rs</code> en él se encontrará un "Hello, world" creado por Rust. Luego nos preocupamos por el resto de archivos. <em>Dato interesante 👀: La extensión de un archivo Rust es </em><strong>.rs</strong>
</p>
<h4>Compilemos nuestro primer código: </h4>
<p>
  Hay dos formas de compilar código creado con Rust, una es a través de <a href="https://doc.rust-lang.org/rustc/what-is-rustc.html"><strong>rustc</strong></a>, adecuado para programas sencillos, pero para proyectos más grandes no es tan eficiente, en su lugar usamos <a href="https://doc.rust-lang.org/cargo/index.html"><strong>cargo</strong></a>, el cual es la segunda forma de compilar. Usemos <a href="https://doc.rust-lang.org/cargo/index.html"><strong>cargo</strong></a> para este primer código ya que es la forma común de hacerlo.
</p>
<p>En nuestra terminal coloquemos el siguiente comando: <code>cargo run</code></p>
<p>
  Al hacerlo, veremos nuestro código impreso en la pantalla. Así, habremos creado nuestro primer programa usando Rust, ¡bienvenido, rustacean!
</p>
<p>
  Dato: Notemos que el macro que imprime el <em>hello world</em> se ejecuta dentro de la función <em>main(){}</em>, por regla general los programas en Rust comienzan con la función <em>main()</em> la cúal se traduce como la <em>función principal</em>, el compilador de Rust ejecutará todo lo que esté en ella.
</p>
dwdw}w
wdwd

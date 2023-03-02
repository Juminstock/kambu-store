<h1 align="center">Rust-start</h1>
<p>
  Aprenderemos inicialmente a instalar <a href="https://www.rust-lang.org/es">Rust</a>, el clasico Hello, world!, y algunas consideraciones sobre <a href="https://www.rust-lang.org/es">rustc</a> y <a href="https://www.rust-lang.org/es">cargo</a>.
<h2 align="center">Instalación</h2>
<p>
  Es sencilla, en mi caso, como usuario de Linux basta con ejecutar este comando en la terminal: <br>
  <code> curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh </code> <br>
  Este comando descarga un script e inicia la instalación de rustup, una herramienta que instalará la última versión estable de     Rust. Para el caso de Windows te recomiendo revisar la <a href="https://rust-book.cs.brown.edu/ch01-01-installation.html">documentación oficial.</a>
  
  Un posible error puede ser la ausencia de un linker, para solucionarlo instalamos el paquete <code>build-essential</code> en     Linux.
</p>
<h3> Algunas opciones útiles de rustup son: </h3>
<ul>
  <li><code>rustup update</code> para actualizar nuestra versión de Rust.</li>
  <li><code>rustup self uninstall</code> para desinstalar Rust.</li>
  <li><code>rustup doc</code> para abrir una copia offline de la documentación.</li>
</p>
<h3>Hello, world!</h3>
<p>
  Creemos nuestro primer "Hola, mundo" en Rust. Así es como se vería: <br>
  <img src="https://github.com/Juminstock/rust-start/blob/main/assets/hello_world.png"> <br>
  <em>Dato interesante</em> 👀: La extensión de un archivo Rust es <strong>.rs</strong>
</p>
<h4>Compilemos nuestro primer código: </h4>
<p>
  Hay dos formas de compilar código creado con Rust, una es a través de <a href="https://doc.rust-lang.org/rustc/what-is-rustc.html"><strong>rustc</strong></a>, adecuado para programas sencillos, pero para proyectos más grandes no es tan eficiente, en su lugar usamos <a href="https://doc.rust-lang.org/cargo/index.html"><strong>cargo</cargo></a>, el cual es la segunda forma de compilar. Usemos cargo para este primer código ya que es la forma común de hacerlo.

  En nuestra terminal coloquemos el siguiente comando: <code>cargo run</code> al hacerlo, veremos nuestro código impreso. Así, habremos creado nuestro primer programa usando Rust, ¡bienvenido, rustacean!

Notemos que el macro que imprime el hello world se ejecuta dentro de la función main(){}, por regla general los programas en Rust comienzan con la función main().
</p>

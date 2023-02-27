<h1 align="center">Rust-start</h1>
<p>
  En el primer capítulo del libro aprenderemos a instalar <a href="https://www.rust-lang.org/es">Rust</a>, el clasico Hello, world!, y algunas consideraciones sobre <a href="https://www.rust-lang.org/es">rustc</a> y <a href="https://www.rust-lang.org/es">cargo</a>.
<h2 align="center">Instalación</h2>
<p>
  Es sencilla, en mi caso, como usuario de Linux basta con ejecutar este comando en la terminal: <br>
  <code> curl --proto '=https' --tlsv1.2 -sSf https://sh.rustup.rs | sh </code> <br>
  Este comando descarga un script e inicia la instalación de rustup, una herramienta que instalará la última versión estable de     Rust. Para el caso de Windows te recomiendo revisar la documentación oficial.
  
  Un posible error puede ser la ausencia de un linker, para solucionarlo instalamos el paquete <code>build-essential</code> en     Linux.
</p>
<h3> Algunas opciones útiles de rustup son: </h3>
<ul>
  <li><code>rustup update</code> para actualizar nuestra versión de Rust.</li>
  <li><code>rustup self uninstall</code> para desinstalar Rust.</li>
  <li><code>rustup doc</code> para abrir una copia offline de la documentación.</li>
</p>

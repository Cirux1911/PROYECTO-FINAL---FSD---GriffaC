# Álbum de Figuritas - Star Wars

El proyecto está basado en la saga de Star Wars. Esta hecho para simular un álbum completo de figuritas, clasificando los elementos de este universo en cuatro secciones: Películas de la saga (Episodios I al IX), Usuarios de la Fuerza del Lado Luminoso (los jedis), Usuarios de la Fuerza del Lado Oscuro (los sith), y Naves o Estaciones Espaciales.

Es una aplicación web estática e interactiva con 5 páginas conectadas. El usuario entra y puede avanzar o retroceder página por página utilizando los botones de navegación en la parte de abajo de la página.

Las secciones de jedis, sith y naves tienen colores que representan a cada uno, jedis azul, sith rojo, y naves gris. Además, tiene efectos interactivos al pasar el mouse por encima de las figuritas y un diseño que automáticamente permite que el álbum se vea bien tanto en computadoras como en teléfonos.

**Algunas tecnologías utilizadas en este proyecto son:**

-HTML Semántico: Se creó cada página utilizando etiquetas como <main> para el contenedor principal, <section> para delimitar las páginas del álbum, <nav> para agrupar los botones de navegación y <footer> para el pie de página.

-CSS:

CSS Box Model: Gestión exacta de dimensiones, desbordamientos, espaciados internos (padding), externos (margin) y bordes de las figuritas con box-sizing: border-box.

Flexbox: Aplicado para la estructura vertical del sitio y para la alineación del contenido de la portada.

CSS Grid: Para distribuir las figuritas de forma simétrica en filas y columnas.

Position: Combinación estratégica de position: relative en el pie de página y position: absolute en los contenedores de navegación para anclar los botones de dirección a las esquinas izquierda y derecha.

Efectos Visuales e Interactividad: Implementación de selectores :hover, transition, efectos de escalado suave (transform: scale()).

Diseño Responsivo: Uso de Media Queries (@media) para adaptar la interfaz a pantallas pequeñas.

**Cómo abrir y ejecutar el proyecto**

El proyecto está construido con tecnologías web estándar y no requiere de ninguna instalación o compilación previa. Se puede ejecutar de dos formas:

Método con Visual Studio Code:

Abrir la carpeta raíz del proyecto en un editor de código como Visual Studio Code.

Asegurarse de tener instalada la extensión Live Server.

Hacer clic derecho sobre el archivo index.html y seleccionar "Open with Live Server" (Abrir con Live Server). El proyecto se ejecutará automáticamente en el navegador web.

Otro método sin Visual Studio Code:

Ir a la carpeta donde están guardados los archivos mediante el explorador de archivos de la computadora.

Hacer doble clic directamente sobre el archivo index.html. Este se abrirá de manera inmediata en el navegador web predeterminado.

**Organización de carpetas**

├── .vscode/
│   └── settings.json
│
├── assets/            Carpeta contenedora de todos los recursos visuales
│   ├── Jedis/         Fotos de los personajes del Lado Luminoso
│   ├── Naves/         Fotos de las naves y estaciones
│   ├── Posters/       Posters correspondientes a las películas
│   ├── Sith/          Fotos de los personajes del Lado Oscuro 
│   └── LOGO.PNG       Logo oficial de Star Wars para la portada 
│      
├── index.html         Portada del álbum (Página de inicio)
├── peliculas.html     Sección 1: Colección de figuritas de las Películas (Episodios I-IX)
├── jedis.html         Sección 2: Colección de figuritas del Lado Luminoso (Jedis)
├── sith.html          Sección 3: Colección de figuritas del Lado Oscuro (Sith)
├── naves.html         Sección 4: Colección de figuritas de Naves y Estaciones
├── README.md          Este archivo
└── styles.css         Hoja de estilos global
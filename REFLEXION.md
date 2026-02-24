# Reflexión Grupal - Práctica Git y GitHub

### 1. ¿Qué ventajas tiene trabajar con ramas?  
Trabajar con ramas nos permite desarrollar nuevas funciones o probar cambios en un entorno aislado, sin afectar al código principal, que es la rama `main`. Como hemos visto en la práctica, cada miembro del equipo ha podido trabajar a su ritmo en su propia parte, como contenido y estilos, en paralelo. Esto evita interferencias y errores en la versión oficial del proyecto hasta que el código está listo.

### 2. ¿Por qué son útiles los Pull Requests en un equipo?  
Los Pull Requests (PR) actúan como un filtro de calidad y un punto de comunicación. No solo sirven para fusionar código, sino que también nos permiten revisar el trabajo de nuestros compañeros antes de integrarlo, sugerir mejoras, como cuando tuvimos que añadir la lista de miembros, y asegurarnos de que el nuevo código no causa problemas. Fomentan la colaboración y mantienen el historial del proyecto claro.

### 3. ¿Qué aprendisteis al resolver el conflicto?  
Aprendimos que los conflictos en Git no son errores serios; son medidas de seguridad. Git nos avisa cuando dos personas modifican exactamente la misma línea de un archivo, como ocurrió con la etiqueta `<h1>`, porque no sabe qué versión elegir. Aprendimos a leer las marcas de conflicto (`<<<<<<<`, `=======`, `>>>>>>>`), a comunicarnos con el equipo para decidir qué versión es la correcta y a limpiar el archivo antes de completar la fusión.

### 4. Dificultades encontradas durante la práctica  
* *(Nota: Aquí podéis borrar esto y poner vuestras dificultades reales. Os dejo un par de ejemplos comunes)*:  
* Entender la diferencia entre nuestro ordenador local (la terminal) y el repositorio remoto (GitHub).  
* Recordar hacer `git pull` para actualizar nuestro ordenador antes de empezar a trabajar y evitar problemas.  
* Saber exactamente en qué rama estábamos antes de hacer un commit.
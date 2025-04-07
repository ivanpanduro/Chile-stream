# ChileStream – Centro de Entretenimiento

**Autor:** Iván Panduro  
**Sprint del 25 de marzo al 6 de abril**

---

## 1. Resumen 

ChileStream es una plataforma de streaming hecha con puro 🔥 HTML, CSS y JavaScript Vanilla.  
No es solo un clon de Netflix... es una experiencia personalizada.  
Aquí el usuario no solo ve películas, ¡vive emociones!

---

## 2. Captura de pantalla del proyecto

### Login de Chilestream

![Login](imagen/login.jpg)

---

### Pantalla Principal

![Home](imagen/home.jpg)




## 3. Mockup inicial

> Aquí va una imagen de tu mockup inicial (puedes subir una a la carpeta `img/`)

---

## 4.Instrucciones de uso 

1.- Iniciar Sesiòn 

    -Abre la página principal (login.html).
    -Ingresa un correo y contraseña simulados (no se valida contra una base de datos).
    -Haz clic en el botón "Iniciar sesión".
    -Serás redirigido automáticamente a la página principal de películas (home.html).

2.- Navegaciòn General 

  Navbar:
  
    -Modo aleatorio: elige una película al azar y la muestra en un modal.
    -Estado de ánimo: te permite seleccionar cómo te sientes (triste, risa, adrenalina, etc.) y recomienda una película según eso.

3.- Tecnologìa utilizada

    -HTML5 y CSS3
    -JavaScript Vanilla
    -Bootstrap 5
    -Git y GitHub


4.- Descripciòn de como se hizo 

  ChileStream fue desarrollado como parte de un sprint del semillero MEGA,
  con el objetivo de crear una plataforma tipo Netflix utilizando solo tecnologías base
  (HTML, CSS y JavaScript Vanilla), añadiendo toques personales para mejorar la experiencia del usuario.
  
   1. Planificación del proyecto
    Se definió el nombre tentativo del proyecto: ChileStream.
  
    Se establecieron los requisitos funcionales y técnicos exigidos:
    
    -Login simulado
    -Página principal con cards de películas
    -Sistema de recomendaciones (aleatorio y por estado de ánimo)
    -Secciones comentables por usuarios
    -GitHub como repositorio obligatorio
    -No copiar exactamente la interfaz de Netflix
  
   2. Desarrollo del login
       
    -Se creó un formulario de inicio de sesión básico.
    -Se usó JavaScript para simular el acceso y redirigir a home.html.
    -Se validó que los campos no estén vacíos antes de permitir el ingreso.
  
    
  
  3. Maquetación de la página principal (home.html)
     
    -Se estructuró el catálogo de películas en tarjetas (cards) con Bootstrap.
    -Cada tarjeta contiene:
    -Imagen de la película
    -Título
    -Descripción
    -Botones de acción (Ver / Opinar)
  
  4. Funcionalidades interactivas (JavaScript)
     
    -Modo aleatorio:
    -Se generó una función que selecciona una película al azar de un arreglo y la muestra en un modal.
    -Estado de ánimo:
    -Se añadió una selección emocional que filtra películas según cómo se siente el usuario


5.- Problemas Conocidos 

    -No se reproduce contenido multimedia real 
    -No hay validaciòn real en el login
    -Las imagenes son cargadas localmente 
    -diseño responsivo pero mejorable

6.- Retrospectiva

  ¿Que hice bien?

    -Cumplí con todos los requisitos funcionales del sprint: login simulado, cards, funcionalidades únicas, etc
    -Usé correctamente HTML, CSS y JavaScript Vanilla, sin frameworks externos.
    -Apliqué Bootstrap para crear un diseño responsive y estructurado.
    -Implementé funciones personalizadas que diferencian mi clon de Netflix
  ¿Qué no salio bien?

      -El diseño visual podría mejorar aún más en pantallas muy pequeñas.
      -Me tomó tiempo entender cómo manejar errores 
  ¿Qué puedo hacer diferente?
  
      -Organizar mejor los archivos y carpetas desde el inicio.
      -Planificar un diseño responsive más sólido antes de escribir código.
      -Usar herramientas como Figma para diseñar el mockup visual antes del HTML.
  
        

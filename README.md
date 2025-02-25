# proweb_petroskill

Proyecto de programación web

PASOS PARA LA CREACIÒN DE REPOSITORIO
Este repositorio contiene la configuración inicial y el flujo de ramas (branches) "main", "staging", y "develop".

Pasos para Crear el Repositorio

1. Crear el Repositorio en GitHub:
   - Accede a GitHub, selecciona (New repository) y elige un nombre con el prefijo "proweb\_".
   - Marca la opción Add a README file y haz clic en Create repository.
   - https://github.com/omarcitol/proweb_petroskill/blob/main/PROWEB.png
   - https://github.com/omarcitol/proweb_petroskill/blob/main/PROWEB2.png
2. Agregar Colaborador:

   - Ve a Settings > Collaborators, busca el usuario "wilfredvasquez" y agrégalo como colaborador.
   - https://github.com/omarcitol/proweb_petroskill/blob/main/PROWEB%203.png
   - https://github.com/omarcitol/proweb_petroskill/blob/main/PROWEB4.png
   - https://github.com/omarcitol/proweb_petroskill/blob/main/PROWEB%205.png
   - https://github.com/omarcitol/proweb_petroskill/blob/main/PROWEB6.png

3. Crear Ramas "staging" y "develop":

   - En el menú desplegable de ramas de la página principal del repositorio, selecciona "main".
   - En el campo de búsqueda, escribe "staging" y selecciona Create branch: staging para crear la rama "staging".
   - Repite el proceso para crear la rama "develop".
   - https://github.com/omarcitol/proweb_petroskill/blob/main/PROWEB7.png
   - https://github.com/omarcitol/proweb_petroskill/blob/main/PROWEB8.png
   - https://github.com/omarcitol/proweb_petroskill/blob/main/PROWEB9.png
   - https://github.com/omarcitol/proweb_petroskill/blob/main/PROWEB10.png

4. Confirmar Ramas:

   - Verifica en el menú desplegable de ramas que las ramas "main", "staging", y "develop" están creadas.
   - https://github.com/omarcitol/proweb_petroskill/blob/main/PROWEB11.png

   # Evaluación Nro. 2

## Descripción

Esta rama contiene una landing page simple desarrollada solo con HTML. La estructura incluye secciones de "Sobre Nosotros", "Servicios", "Proyectos Recientes" y "Contacto".
Adjunto codigo

 <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page Simple</title>
</head>
<body>
    <!-- Sección: Sobre Nosotros -->
    <section id="sobre-nosotros">
        <h2>Sobre Nosotros</h2>
        <p>
            Somos una empresa líder en servicios de inspección y control de calidad para la industria del petróleo y gas. 
            Con más de 20 años de experiencia, nos especializamos en garantizar la seguridad y eficiencia de las operaciones 
            mediante ensayos no destructivos y soluciones innovadoras.
        </p>
    </section>

    <!-- Sección: Servicios -->
    <section id="servicios">
        <h2>Nuestros Servicios</h2>
        <div>
            <h3>Inspección de Estructuras</h3>
            <p>Evaluación de estructuras y recipientes para garantizar su integridad y seguridad.</p>
        </div>
        <div>
            <h3>Control de Calidad</h3>
            <p>Aseguramiento de calidad en herramientas y tuberías para operaciones de perforación.</p>
        </div>
        <div>
            <h3>Ensayos No Destructivos</h3>
            <p>Técnicas avanzadas para evaluar materiales sin dañarlos.</p>
        </div>
    </section>

    <!-- Sección: Proyectos Recientes -->
    <section id="proyectos">
        <h2>Proyectos Recientes</h2>
        <div>
            <h3>Inspección de Plataformas Offshore</h3>
            <p>Realizamos inspecciones en plataformas marinas para garantizar su seguridad y eficiencia.</p>
        </div>
        <div>
            <h3>Control de Calidad en Tuberías</h3>
            <p>Implementamos protocolos de calidad en tuberías para operaciones de producción.</p>
        </div>
    </section>

    <!-- Sección: Contacto -->
    <section id="contacto">
        <h2>Contacto</h2>
        <p>Si deseas obtener más información sobre nuestros servicios, no dudes en ponerte en contacto con nosotros:</p>
        <p>Email: <a href="mailto:InversionesRalex@gmail.com">InversionesRalex@gmail.com</a></p>
    </section>

</body>
</html>

## Archivos

- **`index.html`**: El archivo principal de la landing page.

## Estructura del Proyecto

El proyecto está organizado de la siguiente manera:

## Evaluación Nro. 3

En esta evaluación se agregó dinamismo a la landing page utilizando el framework CSS **Bootstrap**. La rama utilizada es `evaluacion_3`.

### Cambios realizados

- Integración de Bootstrap.
- Uso de clases de Bootstrap para mejorar el diseño y la responsividad.
- Se agregó una barra de navegación responsive.
- Se utilizaron componentes de Bootstrap como tarjetas (`cards`) y listas (`list-group`).

- Evaluación Nro. 4
  Descripción
  En esta evaluación se alojó la landing page en una plataforma de hosting utilizando GitHub Pages. Se configuró correctamente la rama y los archivos necesarios para que la página sea accesible en línea.

📌 URL del sitio web: https://omarcitol.github.io/proweb_petroskill/

Pasos realizados

Habilitación de GitHub Pages

Se accedió a la configuración del repositorio (Settings > Pages).
Se seleccionó la rama main como fuente de la página.
Se guardaron los cambios y se generó la URL del sitio.
Verificación de despliegue

Se verificó que la página se cargue correctamente sin errores.
Se probaron los enlaces y la navegación para confirmar su correcto funcionamiento.
Correcciones y ajustes

Se revisaron y corrigieron posibles errores en la estructura HTML.
Se optimizó el código para asegurar compatibilidad con GitHub Pages.
📌 Estado actual: ✅ La landing page está funcionando correctamente en GitHub Pages.

Evaluación Nro. 5

Descripción

Se agregó una nueva sección API en la landing page.

Esta sección muestra una lista de elementos obtenidos desde una API pública.

Se implementó paginación para visualizar los datos de manera organizada.

Funcionalidades

Listado de datos: Se obtiene información en tiempo real desde una API.

Paginación: Los datos se dividen en páginas para una mejor navegación.

(Opcional) Ver detalles: Al hacer clic en un elemento, se despliega más información sobre él.

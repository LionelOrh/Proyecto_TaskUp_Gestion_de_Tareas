<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Informe - Gestión de Tareas</title>
</head>
<body>
    <h1>INSTITUTO SUPERIOR TECNOLÓGICO PRIVADO CIBERTEC</h1>
    <h2>GESTIÓN DE TAREAS</h2>
    <p><strong>Curso:</strong> Desarrollo de Aplicaciones Móviles</p>
    <p><strong>Profesor:</strong> Jorge Luis Mayta Guillermo</p>
    <p><strong>Ciclo:</strong> Sexto Ciclo</p>
    <p><strong>Semestre:</strong> 2024 - II</p>
    <p><strong>Coordinador:</strong> Fernando Enrique Manrique Solano</p>
    <p><strong>Integrantes:</strong></p>
    <ul>
        <li>Lionel Erix Orihuela Cabrera</li>
        <li>Marco Antonio Ñañez Viera</li>
        <li>Luis Enrique Huaranga Huaman</li>
        <li>Astrid Jahaira Yovera Tinoco</li>
    </ul>
    <h2>Tabla de contenido</h2>
    <ol>
        <li><a href="#resumen">Resumen</a></li>
        <li><a href="#introduccion">Introducción</a></li>
        <li><a href="#diagnostico">Diagnóstico</a>
            <ul>
                <li>Social</li>
                <li>Ecológico</li>
                <li>Político</li>
                <li>Económico</li>
                <li>Tecnológico</li>
            </ul>
        </li>
        <li><a href="#objetivos">Objetivos</a></li>
        <li><a href="#justificacion">Justificación de Proyecto</a></li>
        <li><a href="#definicion-alcance">Definición y Alcance</a></li>
        <li><a href="#productos-entregables">Productos y Entregables</a></li>
        <li><a href="#conclusiones">Conclusiones</a></li>
        <li><a href="#recomendaciones">Recomendaciones</a></li>
        <li><a href="#glosario">Glosario</a></li>
        <li><a href="#bibliografia">Bibliografía</a></li>
        <li><a href="#anexos">Anexos</a></li>
    </ol>
    <h2 id="resumen">1. Resumen</h2>
    <p>El proyecto de “Gestión de Tareas” tiene como objetivo desarrollar una aplicación para la plataforma IOS que permita a los usuarios organizar y gestionar sus actividades diarias de manera eficiente. La aplicación incluye una pantalla principal donde se muestra una lista de tareas pendientes agrupadas por categorías o fechas con indicadores de prioridad y opciones para marcar tareas como completadas. Además cuenta con un botón flotante para la creación de nuevas tareas que abre un formulario con campos para el título, descripción, fecha límite y prioridad.</p>
    <p>El proyecto también incluye una pantalla para gestionar categorías de tareas permitiendo al usuario visualizarlas de forma separada según su tipo (Trabajo, Personal, Hogar, etc.). Otra funcionalidad clave es la visualización de tareas completadas donde se pueden restaurar o eliminar permanentemente. El alcance del proyecto abarca desde la interfaz de usuario hasta la funcionalidad completa de gestión de tareas integrando recordatorios y opciones de personalización de prioridades.</p>
    <h2 id="introduccion">2. Introducción</h2>
    <p>El proyecto “Gestión de Tareas” surge como respuesta a la creciente demanda de herramientas digitales que faciliten la organización y planificación de actividades diarias. En un mundo donde las personas manejan múltiples responsabilidades tanto en el ámbito personal como profesional, resulta crucial contar con aplicaciones que permitan gestionar el tiempo de manera eficiente. Tras un análisis del mercado, se ha diagnosticado que muchas de las aplicaciones actuales carecen de simplicidad en su uso o presentan una sobrecarga de funcionalidades que lejos de ayudar, complican la experiencia del usuario.</p>
    <p>Este proyecto tiene como objetivo principal desarrollar una aplicación sencilla y accesible para IOS que permita a los usuarios crear, organizar y realizar un seguimiento de sus tareas de manera intuitiva y eficiente. A través de una interfaz amigable, la aplicación ofrece la posibilidad de clasificar tareas en categorías como Trabajo, Personal y Hogar, así como establecer niveles de prioridad (Alta, Media, Baja) y fechas límite. Además, incorpora un sistema de recordatorios que ayudará a los usuarios a no perder de vista sus actividades más importantes.</p>
    <h2 id="diagnostico">3. Diagnóstico</h2>
    <h3>3.1 Social</h3>
    <p>Hoy en día hay un creciente interés en la gestión del tiempo y el equilibrio entre la vida laboral y personal. Las personas buscan herramientas que les ayuden a organizar sus tareas de manera efectiva. La interfaz de la aplicación, que incluye funcionalidades como la vista de tareas agrupadas por categorías y la posibilidad de establecer prioridades, responde a esta necesidad social ayudando a reducir el estrés asociado con la sobrecarga de tareas.</p>
    <h3>3.2 Ecológico</h3>
    <p>La digitalización de la gestión de tareas contribuye a la reducción del uso de papel, lo que es beneficioso para el medio ambiente. La aplicación, al centralizar la información y permitir la restauración de tareas completadas en lugar de eliminarlas, promueve un enfoque más sostenible en la gestión del tiempo y las tareas.</p>
    <h3>3.3 Político</h3>
    <p>En el contexto actual, la gestión del tiempo y la organización personal son prioritarias para mejorar la productividad laboral y educativa. Las políticas gubernamentales fomentan el uso de tecnologías que optimicen la eficiencia en el trabajo, lo que crea un entorno favorable para la implementación de aplicaciones de gestión de tareas.</p>
    <h3>3.4 Económico</h3>
    <p>La ineficiencia en la gestión del tiempo puede traducirse en pérdidas económicas significativas tanto a nivel personal como empresarial. La implementación de herramientas digitales como la aplicación de gestión de tareas puede optimizar procesos y reducir costos, al facilitar la priorización y organización de actividades, lo que a su vez potencia la productividad y potencialmente el rendimiento financiero.</p>
    <h3>3.5 Tecnológico</h3>
    <p>El avance tecnológico permite la creación de aplicaciones intuitivas que integran funcionalidades avanzadas como recordatorios y gestión de prioridades. La disponibilidad de dispositivos móviles facilita el acceso a estas herramientas en cualquier momento y lugar. Sin embargo, es fundamental diferenciarse en un mercado saturado de aplicaciones similares, ofreciendo una experiencia de usuario fluida y atractiva como el uso de íconos de prioridad y un botón flotante para agregar tareas fácilmente.</p>
    <h2 id="objetivos">4. Objetivos</h2>
    <h3>4.1 OBJ 1</h3>
    <p>Desarrollar una aplicación de gestión de tareas para IOS que permita a los usuarios crear, organizar y priorizar sus actividades de manera intuitiva. El objetivo es que al menos el 90% de los usuarios pueda registrar y gestionar sus tareas dentro de los primeros cinco minutos de su uso para enero de 2025.</p>
    <h3>4.2 OBJ 2</h3>
    <p>Incrementar la productividad personal de los usuarios facilitando el seguimiento de las tareas completadas y pendientes. El objetivo es que al menos el 80% de los usuarios experimente una mejora en la organización de sus tareas dentro de los 30 días posteriores al inicio del uso de la aplicación.</p>
    <h2 id="justificacion">5. Justificación de Proyecto</h2>
    <p>El proyecto de “Gestión de Tareas” para IOS nace de la creciente necesidad que tienen muchas personas de manejar sus responsabilidades de manera más eficiente tanto en sus vidas personales como profesionales. Hoy en día, la vida puede ser abrumadora con tantas cosas que hacer, es fácil sentirse desbordado. La dificultad para organizarse y priorizar actividades diarias puede generar ansiedad y afectar nuestra productividad.</p>
    <p>Esta aplicación se propone ser una solución sencilla y efectiva ofreciendo una interfaz intuitiva que permite a los usuarios categorizar tareas y asignar prioridades. Con esto buscamos ayudar a las personas a tomar el control de su tiempo y compromiso. Al facilitar el seguimiento de las tareas y enviar recordatorios para eventos importantes, la aplicación no solo mejora la productividad sino que también reduce la tendencia a procrastinar.</p>
    <h3>5.1 Los beneficiarios directos</h3>
    <p>Usuarios: Principalmente aquellos que usarán la aplicación para gestionar su día a día. Esta herramienta les permitirá ser más productivos y tener un mejor control sobre sus actividades.</p>
    <p>Desarrolladores del proyecto: El equipo detrás de la aplicación también se beneficiará perfeccionando sus habilidades de diseño y desarrollo de aplicaciones móviles además de ganar experiencia en crear soluciones digitales para la gestión del tiempo.</p>
    <h3>5.2 Los beneficiarios indirectos</h3>
    <p>Entornos profesionales y personales: Los jefes, colegas y compañeros de trabajo de los usuarios también se verán impactados ya que una mejor gestión del tiempo por parte de los usuarios puede llevar a un mejor desempeño laboral. Asimismo, familiares y amigos podrán notar un cambio positivo ya que los usuarios podrán dedicar más tiempo y atención a sus vidas personales y sociales.</p>
    <h2 id="definicion-alcance">6. Definición y Alcance</h2>
    <p>El alcance del proyecto abarca desde la interfaz de usuario hasta la funcionalidad completa de gestión de tareas, integrando recordatorios y opciones de personalización de prioridades.</p>
    <h2 id="productos-entregables">7. Productos y Entregables</h2>
    <p>Se desarrollará una aplicación IOS que permite crear, gestionar y organizar tareas de manera eficiente, con funcionalidades como la categorización de tareas, gestión de prioridades y recordatorios.</p>
    <h2 id="conclusiones">8. Conclusiones</h2>
    <p>La aplicación permitirá a los usuarios gestionar su tiempo de manera efectiva, ayudándolos a cumplir sus metas personales y profesionales con mayor organización.</p>
    <h2 id="recomendaciones">9. Recomendaciones</h2>
    <p>Se recomienda continuar desarrollando mejoras en la interfaz y agregar más funcionalidades como integración con calendarios y herramientas colaborativas.</p>
    <h2 id="glosario">10. Glosario</h2>
    <p><strong>IOS:</strong> Sistema operativo móvil de Apple.</p>
    <p><strong>Procrastinación:</strong> Acción de posponer o retrasar actividades importantes.</p>
    <h2 id="bibliografia">11. Bibliografía</h2>
    <ul>
        <li><a href="https://asana.com/es">Asana</a></li>
        <li><a href="https://clickup.com/es-ES/blog/109039/trello-frente-a-todoist">ClickUp</a></li>
        <li><a href="https://developers.google.com/calendar/api/concepts/reminders?hl=es-419">Google Calendar API</a></li>
    </ul>
    <h2 id="anexos">12. Anexos</h2>
    <p>No se incluyen anexos en este informe.</p>
</body>
</html>

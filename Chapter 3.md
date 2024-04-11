Capítulo III: Requirements Specification
3.1. To-Be Scenario Mapping.



3.2. User Stories.

 <table>
      <thead>
         <tr>
            <th style="text-align: center;">Epic / Story ID</th>
            <th style="text-align: center;">Titulo</th>
            <th style="text-align: center;">Descripcion</th>
            <th style="text-align: center;">Criterios de aceptacion</th>
            <th style="text-align: center;">Relacionado con (Epic ID)</th>
         </tr>
      </thead>
      <tbody>
         <tr>
            <td style="text-align: center;">EP01</td>
            <td style="text-align: center;">Solicitud de cambio de horario laboral</td>
            <td tyle="text-align: justify;"> Como empleado, quiero poder solicitar cambios en mi horario laboral para acomodarme a situaciones personales o emergencias inesperadas</td>
            <td style="text-align: center;">Criterio de aceptación 1:
Dado que ingresé a mi cuenta de empleado, 
cuando selecciono la opción de "Solicitar cambio de horario" y proporciono una justificación válida, 
entonces la solicitud se registra correctamente en el sistema y se envía a mi supervisor para su aprobación.
Criterio de aceptación 2:
Dado que mi supervisor aprueba mi solicitud de cambio de horario, cuando reviso mi calendario de trabajo, entonces veo que mi horario se actualiza según lo solicitado.
</td>
         </tr>
         <tr>
            <td style="text-align: center;">EP02</td>
            <td style="text-align: center;">Generación de informes de asistencia</td>
            <td style="text-align: justify;">Como gerente de recursos humanos, quiero poder generar informes de ausencias y tardanzas para monitorear el cumplimiento del horario laboral de los empleados.</td>
            <td style="text-align: center;">Criterio de aceptación 1:
Dado que estoy en la página de generación de informes de asistencia, cuando selecciono un rango de fechas y presiono el botón de "Generar informe", entonces el sistema genera un informe detallado que muestra las ausencias y tardanzas de los empleados durante ese período.
Criterio de aceptación 2:
Dado que reviso el informe de asistencia generado, cuando selecciono a un empleado específico, entonces veo una lista detallada de las fechas y horas de las ausencias o tardanzas del empleado.</td>
         </tr>
         <tr>
            <td style="text-align: center;">EP03</td>
            <td style="text-align: center;">Creación y asignación de equipo para proyectos</td>
            <td style="text-align: justify;">Como supervisor de proyecto, quiero poder crear proyectos nuevos en el sistema y asignarles un equipo de trabajo para gestionar las tareas asociadas.</td>
            <td style="text-align: center;">Criterio de aceptación 1:
Dado que estoy en la página de gestión de proyectos, cuando selecciono la opción de "Crear nuevo proyecto" y lleno el formulario con la información del proyecto, entonces el proyecto se crea correctamente en el sistema.
Criterio de aceptación 2:
Dado que he creado un proyecto nuevo, cuando asigno miembros del equipo a las diferentes tareas del proyecto, entonces los miembros del equipo reciben notificaciones sobre sus asignaciones.</td>
         </tr>
         <tr>
            <td style="text-align: center;">EP04</td>
            <td style="text-align: center;">Recepción de notificaciones importantes</td>
            <td style="text-align: justify;">Como empleado, quiero recibir notificaciones sobre actualizaciones importantes en el sistema, como cambios en el horario laboral o nuevas tareas asignadas.</td>
            <td style="text-align: center;">Criterio de aceptación 1:
Dado que el sistema ha realizado cambios en mi horario laboral, cuando el sistema envía una notificación automática al empleado, entonces el empleado recibe la notificación por correo electrónico o mensaje en la aplicación.
Criterio de aceptación 2:
Dado que se me asigna una nueva tarea en el sistema, cuando el sistema envía una notificación automática al empleado, entonces el empleado recibe la notificación y puede ver los detalles de la nueva tarea.</td>
         </tr>
        <tr>
            <td style="text-align: center;">EP05</td>
            <td style="text-align: center;">Realización de copias de seguridad automáticas</td>
            <td style="text-align: justify;">Como administrador del sistema, quiero poder realizar copias de seguridad de los datos del sistema regularmente para garantizar la seguridad y la integridad de la información.</td>
            <td style="text-align: center;">Criterio de aceptación 1:
Dado que estoy en la página de configuración de copias de seguridad, cuando programo una copia de seguridad automática para que se realice semanalmente, entonces el sistema programa la copia de seguridad correctamente.
Criterio de aceptación 2:
Dado que se programó una copia de seguridad automática, cuando llega el momento programado, entonces el sistema realiza la copia de seguridad de los datos del sistema correctamente y notifica al administrador sobre el éxito de la operación.</td>
         </tr>
       <tr>
            <td style="text-align: center;">EP06</td>
            <td style="text-align: center;">Acceso a manuales de políticas y procedimientos</td>
            <td tyle="text-align: justify;">Como empleado, quiero poder acceder a manuales de políticas y procedimientos de la empresa para obtener información sobre las políticas internas y los procesos de trabajo.</td>
            <td style="text-align: center;">Criterio de aceptación 1:
Dado que ingresé a mi cuenta de empleado, cuando selecciono la opción de "Ver manuales de políticas y procedimientos", entonces puedo acceder a una biblioteca de documentos que contiene manuales y guías de la empresa.
Criterio de aceptación 2:
Dado que estoy leyendo un manual específico, cuando selecciono un tema o sección dentro del manual, entonces puedo navegar fácilmente por el contenido y encontrar la información relevante que necesito.</td>
         </tr>
       <tr>
            <td style="text-align: center;">EP07</td>
            <td style="text-align: center;">Programación de reuniones virtuales</td>
            <td tyle="text-align: justify;">Como supervisor de proyecto, quiero poder realizar reuniones virtuales con mi equipo a través del sistema para discutir el progreso del proyecto y tomar decisiones importantes.</td>
            <td style="text-align: center;">Criterio de aceptación 1:
Dado que estoy en la página de programación de reuniones, cuando elijo la opción de "Crear nueva reunión" y configuro los detalles de la reunión, entonces el sistema programa la reunión correctamente y envía invitaciones al equipo.
Criterio de aceptación 2:
Dado que llega el momento programado para la reunión, cuando los miembros del equipo hacen clic en el enlace de la reunión, entonces pueden unirse a la reunión virtual a través de la plataforma integrada en el sistema.</td>
         </tr>
       <tr>
            <td style="text-align: center;">EP08</td>
            <td style="text-align: center;">Solicitud de vacaciones o días libres</td>
            <td tyle="text-align: justify;"> Como empleado, quiero poder solicitar vacaciones o días libres a través del sistema y recibir confirmación de aprobación o rechazo por parte del supervisor.</td>
            <td style="text-align: center;">Criterio de aceptación 1:
Dado que ingresé a mi cuenta de empleado, cuando selecciono la opción de "Solicitar vacaciones" y selecciono las fechas deseadas, entonces el sistema registra mi solicitud y la envía automáticamente a mi supervisor para su revisión.
Criterio de aceptación 2:
Dado que mi supervisor revisa mi solicitud de vacaciones, cuando toma una decisión de aprobación o rechazo, entonces el sistema me notifica automáticamente sobre el resultado de la solicitud.</td>
         </tr>
       <tr>
            <td style="text-align: center;">EP09</td>
            <td style="text-align: center;">Gestión de cuentas de usuario y permisos de acceso</td>
            <td tyle="text-align: justify;"> Como administrador del sistema, quiero poder gestionar las cuentas de usuario y los permisos de acceso para garantizar la seguridad de los datos y la privacidad de la información confidencial.</td>
            <td style="text-align: center;">Criterio de aceptación 1:
Dado que estoy en la página de administración de usuarios, cuando selecciono un usuario específico y modifico sus permisos de acceso, entonces el sistema actualiza los permisos de usuario correctamente y refleja los cambios en el acceso a las funciones del sistema.
Criterio de aceptación 2:
Dado que necesito agregar un nuevo usuario al sistema, cuando lleno el formulario de registro con la información del nuevo usuario y asigno sus roles y permisos, entonces el sistema crea una cuenta de usuario nueva y funcional.</td>
         </tr>
       <tr>
            <td style="text-align: center;">EP010</td>
            <td style="text-align: center;">Registro de horas trabajadas y actividades realizadas</td>
            <td tyle="text-align: justify;">Como empleado, quiero poder registrar horas trabajadas y actividades realizadas a través del sistema para mantener un registro preciso de mi desempeño laboral y contribuciones al proyecto.</td>
            <td style="text-align: center;">Criterio de aceptación 1:
Dado que ingresé a mi cuenta de empleado, cuando selecciono la opción de "Registrar horas trabajadas" y completo el formulario con las horas y las actividades realizadas, entonces el sistema registra la información correctamente en mi historial laboral.
Criterio de aceptación 2:
Dado que necesito editar un registro de horas trabajadas previamente registrado, cuando accedo a mi historial laboral y selecciono el registro específico, entonces puedo modificar las horas o las actividades y guardar los cambios correctamente.</td>
         </tr>
   </tr>
   </tbody>
   </table>

3.3. Impact Mapping.




3.4. Product Backlog.

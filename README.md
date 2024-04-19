# IPOP-
La actividad en Ansible se lleva a cabo mediante la creación de "playbooks", que son archivos YAML que describen los pasos que Ansible debe seguir para realizar una tarea específica. Estos playbooks pueden incluir tareas como la instalación de paquetes de software, la configuración de archivos de configuración y la ejecución de comandos en los servidores remotos.

Ansible utiliza un enfoque basado en agentes para la gestión remota, lo que significa que no requiere instalar ningún software adicional en los servidores que va a administrar. En su lugar, utiliza SSH (Secure Shell) para conectarse a los sistemas remotos y ejecutar las tareas especificadas en los playbooks.

Además de los playbooks, Ansible también proporciona módulos que pueden utilizarse para realizar tareas específicas, como la gestión de usuarios y grupos, la configuración de firewalls y la gestión de servicios.

En resumen, la actividad en Ansible implica la creación de playbooks y la ejecución de tareas automatizadas en sistemas remotos para gestionar y configurar infraestructuras de TI de manera eficiente.


Autenticación de usuarios: Cuando un usuario intenta acceder a recursos de red, como archivos compartidos o impresoras, el controlador de dominio valida las credenciales del usuario. Esto garantiza que solo los usuarios autorizados puedan acceder a los recursos en función de sus permisos y políticas de seguridad definidas en el dominio.
Gestión de usuarios y grupos: Los administradores de red pueden crear, modificar y eliminar cuentas de usuario y grupos desde el controlador de dominio. Esto proporciona una forma centralizada de administrar la identidad de los usuarios y sus permisos de acceso a diferentes recursos en la red.
Políticas de grupo: Los controladores de dominio permiten la configuración de políticas de grupo que se aplican a los usuarios y equipos dentro del dominio. Estas políticas pueden controlar una amplia variedad de configuraciones, como la imposición de contraseñas seguras, la configuración de restricciones de acceso, la configuración de políticas de seguridad local, entre otros.
Replicación de datos: En entornos con varios controladores de dominio, la actividad de replicación garantiza que la información de directorio, incluidas las cuentas de usuario y las políticas, se mantenga consistente en todos los controladores de dominio. Esto asegura la disponibilidad y la redundancia de los datos del dominio.
Gestión de servicios de red: Además de la autenticación y la gestión de identidades, un controlador de dominio también puede proporcionar otros servicios de red, como servicios de resolución de nombres (DNS) y servicios de configuración de clientes (DHCP), dependiendo de la configuración y los roles asignados.

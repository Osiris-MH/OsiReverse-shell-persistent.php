OsiReverse-shell-persistent.php
================================================

Es una reverse shell avanzada escrita en PHP diseñada para ser utilizada en entornos de pruebas de penetración. Este script establece una conexión con un servidor remoto (IP y puerto configurables) y ejecuta un shell interactivo. Además, incluye características de persistencia, lo que permite que el script se ejecute automáticamente tras un reinicio del sistema. Utiliza stream\_select para manejar la comunicación, lo que lo hace eficiente y resistente a los bloqueos.

Características Principales:
----------------------------

* Persistencia:▶️Copia el script a /tmp/.ld.php y lo agrega a .bashrc para asegurar que se ejecute automáticamente tras cada reinicio.
  
* Auto-discovery del entorno:▶️Detecta información del sistema como el usuario, UID, GID, versión de OS y la shell en uso.
  
* Uso de stream_select:▶️Permite una comunicación eficiente y sin bloqueos entre el servidor remoto y el shell.
  
* Daemonización:▶️Puede correr en segundo plano como un demonio, útil para operaciones encubiertas.
  
* Compatibilidad:▶️Compatible con sistemas que ejecuten PHP y proporcionen un entorno adecuado.

⚠️ Advertencia
===============================

Este script esta destinado exclusivamente para fines educativos, pruebas de penetracion autorizadas y auditorias de seguridad. El uso no autorizado puede ser ilegal. Usalo bajo tu propia responsabilidad.

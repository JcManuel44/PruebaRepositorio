Problema: Botón de confirmación bloqueado en Visual Studio Code
Descripción

Al intentar confirmar cambios directamente en la rama main usando Visual Studio Code, el botón de commit aparece bloqueado. Esto ocurre incluso cuando hay cambios visibles en el editor.

Pasos para reproducir
Crear o modificar un archivo en la rama main.
Ir al panel de control de código fuente.
Intentar confirmar cambios sin hacer "stage".
Comportamiento esperado

El botón de commit debería indicar que no hay cambios en staging o guiar al usuario a agregar los cambios.

Contexto adicional

Visual Studio Code versión X.X, Git integrado, plataforma Windows 10 (o la que sea), etc.

Posible solución

Una alerta o mensaje que indique la necesidad de hacer "stage" antes de confirmar.
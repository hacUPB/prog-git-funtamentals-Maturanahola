# Pasos para crear un repositorio remoto

1. Crear el repositorio en GitHub

Antes de tocar la consola, debes preparar el destino:

Inicia sesión en GitHub.

Haz clic en el botón "+" (arriba a la derecha) y selecciona "New repository".

Ponle un nombre a tu proyecto.

Haz clic en "Create repository".


2. Conectar el repositorio local con el remoto

Una vez creado, GitHub te mostrará una URL (que termina en .git). Copia esa URL y vuelve a tu terminal dentro de la carpeta de tu proyecto.

Ejecuta el siguiente comando para decirle a tu Git local dónde está su "pareja" en la nube:

git remote add origin https://github.com/tu-usuario/tu-repositorio.git
remote add: Indica que vas a añadir una conexión remota.

origin: Es el nombre estándar que se le da al servidor remoto principal.

La URL: Es la dirección que acabas de copiar.


3. Cambiar el nombre de la rama principal (Opcional pero recomendado)

GitHub utiliza por defecto el nombre main para la rama principal, mientras que algunas versiones de Git local usan master. Para evitar confusiones, asegúrate de estar en main:

git branch -M main


4. Subir tus archivos (git push)

Ahora que están conectados, es hora de enviar tus commits locales a la nube:

git push -u origin main
-u: Crea una relación de seguimiento entre tu rama local y la remota (solo tendrás que usarlo la primera vez).

origin main: Dice "envía mis cambios al servidor 'origin' a la rama 'main'".


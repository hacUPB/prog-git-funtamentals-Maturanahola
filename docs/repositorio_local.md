# Pasos para crear un repositorio local

1. Preparar el terreno
Primero, debes estar dentro de la carpeta de tu proyecto. Si aún no la tienes, créala y entra en ella:

mkdir mi-proyecto

cd mi-proyecto

2. Inicializar el repositorio (git init)

Este es el comando mágico. Al ejecutarlo, Git crea una carpeta oculta llamada .git donde guardará todo el historial.

git init

3. Rastrear archivos (git add)

Git no guarda archivos automáticamente; tú debes decirle cuáles quieres incluir en la próxima "foto" (commit).

Para añadir un archivo específico: git add mi-archivo.py

4. Guardar los cambios (git commit)

Una vez que los archivos están en el "área de preparación" (staging area), debes confirmar el cambio con un mensaje descriptivo.

git commit -m "Mi primer commit: estructura inicial del proyecto"

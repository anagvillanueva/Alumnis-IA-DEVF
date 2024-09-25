

### Pasos para los Alumnos:

1. **Hacer un Fork del Repositorio:**
   - Ve al repositorio del instructor en GitHub.
   - Haz clic en el botón "Fork" en la esquina superior derecha. Esto creará una copia del repositorio en tu cuenta de GitHub.

2. **Clonar el Repositorio Forkeado:**
   - En tu cuenta de GitHub, ve al repositorio que acabas de forkar.
   - Haz clic en el botón "Code" y copia la URL del repositorio.
   - Abre tu terminal o línea de comandos y ejecuta el siguiente comando para clonar el repositorio a tu computadora:
     ```bash
     git clone https://github.com/TU_USUARIO/nombre-del-repo.git
     ```
   - Esto descargará el repositorio a tu máquina local.
   - Asegúrate de dar a la rama un nombre descriptivo, como `agregar-cards`.

3. **Hacer Cambios y Confirmarlos:**
   - Realiza los cambios que te pidió el instructor (por ejemplo, agregar nuevas cards).
   - Guarda los cambios y agrégalos al área de preparación:
     ```bash
     git add .
     ```
   - Haz un commit de los cambios:
     ```bash
     git commit -m "Descripción de los cambios realizados"
     ```

4. **Empujar la Rama a GitHub:**
   - Envía la rama con tus cambios a tu repositorio en GitHub:
     ```bash
     git push origin nombre-de-la-rama
     ```

5. **Crear un Pull Request:**
   - Ve a tu repositorio en GitHub.
   - Verás un mensaje que te sugiere crear un Pull Request. Haz clic en el botón correspondiente.
   - Completa el formulario del Pull Request con una descripción clara de los cambios que hiciste.
   - Envía el Pull Request.

6. **Revisar y Resolver Comentarios:**
   - El instructor revisará tu Pull Request. Si hay comentarios o solicitudes de cambios, realiza esos ajustes en tu rama local y haz otro push para actualizar el PR.

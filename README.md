# Equipo_1_code_review


## Adivina el número

Juego de consola en Python donde el jugador intenta adivinar un número secreto. Al comenzar, se solicita el nombre y se elige una dificultad: fácil, media o difícil. Durante la partida se reciben pistas para saber si el intento fue demasiado alto o bajo. Al final se calcula la puntuación y se muestran los mejores resultados de la sesión; también se puede jugar otra ronda.

### Cómo ejecutarlo

1. Asegúrate de tener Python 3 instalado.
2. Abre una terminal en la carpeta del proyecto.
3. Ejecuta:

   ```bash
   python adivina_numero.py
   ```

En algunos sistemas, puede ser necesario usar `python3` en lugar de `python`.

Anoten al menos tres observaciones: una sobre comportamiento, una sobre entradas del usuario y una sobre legibilidad o estructura.
## Anotaciones
### Cpmportamiento 
1. Se nos hizo muy interesante y acertado que el programa gestione de forma adecuada los errores y entradas incorrectas por parte del usuario, ya que esto evita que la aplicación falle y mejora la usabilidad de la interfaz de consola.
2. Nos pareció un detalle muy acertado que el programa solicite tanto el nombre del jugador como el nivel de dificultad al comienzo de la ejecución, ya que este elemento crea una personalización que mejora en gran medida la experiencia del usuario.
3. Encontramos muy adecuada la estructura del código, ya que separa correctamente la lógica en funciones independientes y evita el uso de literales mágicas mediante la definición de constantes, lo que hace que el programa sea mucho más legible, comprensible y fácil de mantener.
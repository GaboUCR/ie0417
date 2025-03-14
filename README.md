# ie0417

## Cómo agregar cambios

1. **Clonar el repositorio**:
   ```sh
   git clone https://github.com/GaboUCR/ie0417.git
   ```
2. **Hacer un fork del repositorio**:
   - Ve al repositorio en GitHub: [ie0417](https://github.com/GaboUCR/ie0417)
   - Haz clic en el botón **Fork** en la esquina superior derecha.
   - Esto creará una copia del repositorio en tu cuenta de GitHub.
3. **Hacer cambios y subirlos**:
   ```sh
   git checkout -b nombre-de-la-rama
   # Realiza los cambios en el código
   git add .
   git commit -m "Descripción de los cambios"
   git push origin nombre-de-la-rama
   ```
4. **Crear un Pull Request (PR)**:
   - Ve a tu repositorio en GitHub.
   - Haz clic en **Compare & pull request**.
   - Agrega una descripción y envía la solicitud de PR.

## Cómo ejecutar programas

### Python
Ejecutar un script de Python:
```sh
python nombre_del_archivo.py
```
Si usas Python 3:
```sh
python3 nombre_del_archivo.py
```
Para entornos virtuales:
```sh
source venv/bin/activate  # En Linux/Mac
env\Scripts\activate     # En Windows
```

### C
Compilar y ejecutar un programa en C:
```sh
gcc nombre_del_archivo.c -o programa
./programa
```
En Windows:
```sh
gcc nombre_del_archivo.c -o programa.exe
programa.exe
```

### C++
Compilar y ejecutar un programa en C++:
```sh
g++ nombre_del_archivo.cpp -o programa
./programa
```
En Windows:
```sh
g++ nombre_del_archivo.cpp -o programa.exe
programa.exe
```

## Descripción del curso
Este curso está orientado a que la persona estudiante comprenda que el desarrollo de software es
una industria, y que por lo tanto se deben aplicar sólidos principios de ingeniería y buenas prácticas
de gestión. Es decir, para obtener un producto de calidad con un tiempo y costo determinado se
deben aplicar de forma sistemática un conjunto de métodos, técnicas y herramientas.

Este curso de Diseño de Software para Ingeniería se centra en el aprendizaje de las tareas vinculadas
a la construcción del producto software y se da una introducción a aspectos relacionados con la
gestión del proceso de construcción. Para ello la persona estudiante va a aprender a determinar los
requisitos de un software a construir, realizar el análisis del sistema, transformar el análisis en el
diseño de una solución concreta, y planificar y ejecutar un conjunto de pruebas que permitan
verificar y validar el software construido.

Además, a partir de un enfoque práctico basado en laboratorios y proyectos, la persona estudiante
se familiariza con una serie de herramientas modernas y técnicas avanzadas de programación para
afrontar exitosamente el desarrollo de proyectos de ingeniería de software en el ámbito profesional.
